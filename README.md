# UTS-Ver.1
UTS Praktikum Pemrograman Web (update ke versi 2)
--------------------------------------------

Buatlah sebuah form untuk mengisi data-data sebagai berikut:
- Nama Mahasiswa  
- NIM 
- Kelas
- Mata Kuliah Pilihan
- Unggah file KHS (Kartu Hasil Studi) 

Ketentuan validasi input data  adalah:
- semua field wajib diisi (required)
- Nama hanya boleh berisi huruf
- NIM hanya boleh berisi angka dan panjangnya harus 10 digit
- Kelas hanya diisi dengan satu pilihan, yaitu: 5A, 5B, 5C, 5D atau 5E
- Mata Kuliah Pilihan, dapat diisi lebih dari satu pilihan, dari daftar 5 mata kuliah yang tersedia yaitu:
  - Web Application Development,
  - Mobile Application Development,
  - UI/UX Design,
  - Software Engineering, dan
  - Data Engineering.
- File yang diunggah harus bertipe PDF, ukuran maksimal 2M
Simpan data tersebut dalam tabel pada database. Nama tabel: **krs** dan nama database: **uts5d**.
Direktori penyimpanan unggahan file diberi nama: **uploadKHS**
Proses pembuatan database dan tabel dilakukan menggunakan _script_ PHP. 

Lengkapi **operasi CRUD** (_Create, Read, Update, Delete_) untuk mengelola data tersebut.
