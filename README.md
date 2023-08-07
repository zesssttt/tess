1. install paket vnstati2 dan vnstat2
2. copy file vnstati.zip ekstar pada folder www
3. buat scheduled */5 * * * * /www/vnstati/vnstati.sh >/dev/null 2>&1

Mengubah Konfigurasi Database Vnstat

Untuk mengubah konfigurasi database vnstat sangatlah mudah, namun untuk lebih mempermudah, kami sudah menyediakan file yang sudah terkonfigurasi. Jadi kalian hanya perlu mengganti filenya saja.

1. Pertama, pastikan internet kalian sudah jalan. Kemudian buka terminal lalu paste perintah berikut ini:

   cd /etc

   rm vnstat.conf

   wget https://raw.githubusercontent.com/zesssttt/vnstat/main/vnstat.conf

3. Selanjutnya silahkan ketik perintah untuk restart vnstat berikut ini:

   service vnstat restart
