
# Praktikum GIT & GITHUB

Nama    : Adam Maurizio Winata
NIM     : 162012133045
Kelas   : Algoritma Pemrograman SD-A1

# Langkah-Langkah:
- Mendownload aplikasi Git pada alamat berikut : <https://git-scm.com/downloads>.
- Setelah proses download selesai, lanjutkan dengan proses instalasi.
- Buka aplikasi Git yang sudah diinstall.
- Lanjutkan dengan melakukan beberapa konfigurasi awal seperti username dan email.
- Buat akun Github di alamat berikut : <https://github.com/> (Bisa di-skip apabila sudah mempunyai akun Github).
- Buat sebuah folder kosong bernama **PRAKTIKUM_GIT** di Desktop
- Buka Git Anda dan cek lokasi direktori yang saat ini diakses oleh Git dengan menggunakan perintah **$ pwd**
- Karena folder **PRAKTIKUM_GIT** yang kita punya ada di dalam Desktop, maka kita perlu terlebih dahulu untuk mengakses Desktop dan masuk ke foldernya dengan perintah **$ cd Desktop** dan **$ cd PRAKTIKUM_GIT**.
- Setelah itu, kita buat repositori baru di dalam folder **PRAKTIKUM_GIT** dengan menggunakan perintah **$ git init**.
- Selanjutnya, kita cek status dari repository kita dengan **$ git status**.
- Kita copy file yang akan kita commit nantinya yaitu file **README .md**.
- Kita cek lagi status dari repository-nya.
- Setelah itu, kita akan menambahkan file tersebut dengan perintah **$ git add nama_file**.
- Lanjutkan untuk mengerjakan file **README .md** dan apabila sudah selesai, kita bisa cek lagi statusnya menggunakan **$ git status**.
- Setelah itu, kita add lagi filenya ke dalam **staging area** dan melakukan commit. Pada tahap ini, Git sudah berhasil menyimpan 2 jenis versi file yaitu file sebelum penambahan dan file akhir yang sudah selesai.
- Berikutnya, kita akan membuat clonenya di Github. Perlu kita perhatikan bahwa clone yang dimaksud di sini adalah membuat repository baru di Github berdasarkan repository lokal yang kita miliki. Kita bisa melakukannya dengan menggunakan perintah berikut **$ git remote add origin git@github.com:USERNAME/REPO_NAME.git**.
- Setelah itu, kita akan melakukan **push** dengan menggunakan perintah **$ git push origin master**.
- Terakhir, untuk memastikan saja, kita buka akun Github dan pastikan bahwa repository-nya sudah ada.