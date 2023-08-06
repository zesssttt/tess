Mengubah Konfigurasi Database Vnstat

Untuk mengubah konfigurasi database vnstat sangatlah mudah, namun untuk lebih mempermudah, kami sudah menyediakan file yang sudah terkonfigurasi. Jadi kalian hanya perlu mengganti filenya saja.

1. Pertama, pastikan internet kalian sudah jalan. Kemudian buka terminal lalu paste perintah berikut ini:
cd /etc
rm vnstat.conf
wget https:

2. Selanjutnya silahkan ketik perintah untuk restart vnstat berikut ini:
service vnstat restart
