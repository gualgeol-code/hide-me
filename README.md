#Akses Free Shell 
1. layanan vps dengan docker aktif bisa gunakan perintah => docker run -p 8080:8080 gcd212/safecode:2
2. Layanan vps tanpa docker bisa gunakan perintah : 
   1. pip3 install udocker
   2. udocker --allow-root docker run -p 8080:8080 gcd212/safecode:2
3. akses langsung shell via output dari shell tmate dari docker
4. atau bisa akses via codeserver jika layanan memberikan akses externa public ip di port 8080
5. di shell hasil runing docker tersebut sudah di include hider process 
6. ganti nama aplikasi yang ingin di tutup proses nya di sistem monitoring 
7. berikut nama-nama yang bisa digunakan :
   1. pythonc
   2. bhmax
   3. bmx
   4. python
