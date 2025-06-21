# Sistem-Operasi-

Nama : I MADE ARY WIDNYANA 

NIM : 1202230004

**DESKRIPSI MENU**
1. Menu Info Jaringan

Menu Jaringan adalah skrip bash interaktif yang dijalankan di terminal Linux. Program ini dirancang untuk membantu pengguna dalam memantau informasi jaringan dan isi direktori dengan antarmuka berbasis teks yang ramah pengguna. Skrip ini berjalan terus-menerus hingga pengguna memilih untuk keluar.

Ketika opsi 1 dipilih, skrip akan menampilkan informasi lengkap mengenai jaringan lokal yang sedang digunakan. Informasi yang ditampilkan antara lain:

Alamat IP lokal: Diambil dari hasil parsing perintah ip addr show.

Gateway: Diperoleh menggunakan ip route dan awk.

Netmask: Diambil dari hasil ipcalc.

DNS: Didapatkan dari nmcli.

Status koneksi internet: Diuji dengan melakukan ping ke 8.8.8.8.

Status koneksi LAN/WIFI: Ditampilkan melalui nmcli dev status.

Lokasi berdasarkan IP: Diambil secara otomatis dari layanan ipinfo.io menggunakan curl dan jq.

Jika semua koneksi aktif, pengguna akan diberi tahu bahwa koneksi internet berhasil. Jika tidak, akan ada notifikasi bahwa koneksi tidak tersedia. Seluruh informasi ditampilkan secara terstruktur dan berwarna.

2. Menu tampilkan isi direktori

Opsi 2 akan menampilkan semua file dan folder yang ada di direktori tempat skrip dijalankan. Informasi yang diberikan meliputi:

Hak akses file

Pemilik dan grup

Ukuran file

Tanggal modifikasi

Nama file (dengan pewarnaan otomatis)

Perintah yang digunakan untuk ini adalah ls -l --color=auto, memberikan tampilan yang terstruktur dan berwarna secara otomatis.

3. Menu keluar

Jika opsi 3 dipilih, skrip akan menampilkan pesan “Keluar dari program...” dan keluar dari perulangan sehingga pengguna kembali ke prompt terminal. Ini memastikan skrip berakhir dengan rapi.

**DOKUMENTASI MENU**

1. Tampilan awal

![Image](https://github.com/user-attachments/assets/447056df-f199-4b68-b7d4-a930203d1048)

2. Menu info Jaringan

![Image](https://github.com/user-attachments/assets/59178252-9b90-4d4e-8357-f27b66d07408)

3. Menu Tampilkan isi direktori

![Image](https://github.com/user-attachments/assets/ae84191b-38ec-4d2c-adfe-e33e4be80cf2)

4. Menu keluar

![Image](https://github.com/user-attachments/assets/692e501a-1ca1-4612-9d81-3fe6d9e3d09a)
