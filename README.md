LANGKAH LAHNGKAH MEMBUAT REPOSITORY LOCAL DAN REPOSITORY PADA GITHUB DAN MEMBUAT FILE README.md

YANG DI BUTUHKAN ANTARA LAIN
- AKUN GITHUB
-SOFTWARE GIT

1.BUAT AKUN GITHUB DI https://github.com
   ISI DATA DIRI LALU KLIK SIGN UP
 






2. LALU VERFIY YOUR ACCOUNT DENGAN MEMASUKAN CHAPTA
 
3. LALU PILIH FREE $0 USD
 


4. PILIH "A LITTLE " DAN KLIK COMPLETE SETUP ATAU BISA DI SKIP
 
5. CEK DI GMAIL ANDA AKAN ADA PESAN BARU DARI GITHUB DAN KLIK VERFIY EMAIL ADDRESS
 


6. LALU AKAN DI ALIHKAN KE TAB BARU UNTUK CREATE A NEW REPOSITORY ISI REPOSITORY NAME LALU KLIK CREATE REPOSITORY
 
TAMPILAN REPOSITORY YANG BARU
  


7. DOWNLOAD SOFTWARE GIT DI “git-scm.com” DAN  INSTALL SOFTWARE GIT TERLEBIH DAHULU 
Untuk Anda pengguna Windows, berikut ini cara mengginstall Git di Windows.
Download Git versi Windows terbaru 
Selesai di download, maka double click file tersebut untuk menginstall.
Muncul tampilan mengenai lisensi seperti dibawah ini, lalu klik NEXT.

 

Selanjutnya tentukan lokasi folder untuk menginstall Git.
 
Pilih komponen yang akan di install 
 


Menentukan nama folder shortcuts di Start menu nantinya 
 
Pilih editor untuk menggunakan Git nantinya. 
 

Mengatur PATH environment 
 
Memilih jenis koneksi ke server 
 


Mengatur baris akhir file teks nantinya. 
 
Mengatur terminal emulator yang akan digunakan dengan Git Bash 
 


Memilih opsi tambahan yang mungkin diperlukan  
Proses instalasi akan dijalankan, tunggu hingga proses selesai 100% 
 
Proses instalasi Git di Windows sudah selesai dilakukan  
Cek apakah Git sudah bisa digunakan akan belum dengan cara membuka Command Prompt dan ketik git --version, jika muncul versi Git maka proses yang dilakukan sudah berjalan dengan baik dan Git siap untuk digunakan. 
 
8. LALU BUKA DOCUMENT DAN BUAT FOLDER BARU KLIK KANAN PADA FOLDER LALU PILIH ” GIT BASH HERE “ 
MAKA AKAN MUNCUL JENDELA TERMINAL ( CMD ) 
LALU KONFIGURASI DENGAN MEMASUKAN PERINTAH " git config --global user.name “nama_user” " DAN " git config --global user.email “nama_user” " INI DIGUNAKAN AGAR TIDAK TERJADI KEGAGALAN SAAT MEMASUKAN PERINTAH " git commit "
 
9. BUAT DIREKTORI BARU DENGAN MENGGUNAKAN PERINTAH " mkdir latihan1" LALU " cd latihan1 "
 
10.JALAN KAN PERINTAH " git init " UNTUK MEMBUAT FILE KOSONG BERFORMAT .GIT
 

11.LALU BUAT 1 FILE BERNAMA README.md DENGAN MEMASUKAN PERINTAH " echo "#latihanpytn1" >> README.md “ LALU KETIKAN PERINTAH " ls -l " UNTUK MELIHAT FILE
 
12. MENAMBAHKAN FILE README. md PADA REPOSITORY LOCAL  DENGAN MENGGUNAKAN PERINTAH " git add "
 
13. KETIK PERINTAH " git commit -m " komentar saya " UNTUK MENYIMPAN PERUBAHAN YANG ADA KE DALAM DATABASE REPOSITORY
 

14. MASUK LAGI KE WEBSITE GITHUB LALU MASUK KE REPOSITORI YANG SEBELUM NYA DI BUAT... PADA BAGIAN QUICK SETUP TERDAPAT URL GITHUB KITA... URL INI NANTINYA AKAN DI GUNAKAN MENGGUNAKAN PERINTAH “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “
 



15. LALU KETIKAN PERINTAH " git remote add origin [url] " CONTOH
 " git remote add origin https://github.com/robisubagja/LATIHAN_PYTHON.git "
 
16. UNTUK MENGIRIM PERUBAHAN LOCAL REPOSITORY KE SERVER GUNAKAN PERINTAH GIT PUSH " git push -u origin master "
 
17. DAN UNTUK MELIHAT HASIL NYA CEK DI github DAN LIHAT DI REPOSITORY NYA
 
18. JIKA INGIN MELAKUKAN CLONE REPOSITORY GUNAKAN PERINTAH " git clone [ url ] " CONTOH " git clone https://github.com/robisubagja/LATIHAN_PYTHON.git " LALU JIKA INGIN MASUK KE DALAM DIREKTORI GUNAKAN PERINTAH                " cd [ nama direktori ] " CONTOH " cd LATIHAN_PYTHON " LALU JIKA INGIN MELIHAT SEMUA ISI DIREKTORI GUNAKAN PERINTAH " ls " 

