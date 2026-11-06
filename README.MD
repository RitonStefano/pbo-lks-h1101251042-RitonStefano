# PBO LKS — Portofolio Praktikum

- Nama : Riton Stefano
- NIM : H1101251042
- Kelas: B

## Daftar Pertemuan

- [X] Pertemuan 1 — Setup & Database
- [X] Pertemuan 2 — Core OOP
- [X] Pertemuan 3 — Framework & Routing
- [X] Pertemuan 4 — Testing Backend
- [X] Pertemuan 5 — CRUD Kategori
- [X] Pertemuan 6 — Frontend
- [X] Pertemuan 7 — Integrasi & Finalisasi

Untuk menjalankan proyek Sistem Informasi Perpustakaan, backend dan frontend perlu dijalankan secara terpisah. Pertama, jalankan aplikasi Laragon dan pastikan layanan MySQL sudah aktif. Selanjutnya, buat database dengan nama perpustakaan melalui phpMyAdmin, kemudian impor file database/schema.sql yang terdapat pada folder rest-api-perpustakaan untuk membuat tabel database.

Setelah database siap, buka terminal pada folder rest-api-perpustakaan, kemudian jalankan perintah composer install untuk memastikan seluruh dependency backend tersedia. Selanjutnya, jalankan server backend menggunakan perintah php -S localhost:8000 -t public public/index.php. Backend akan berjalan pada alamat http://localhost:8000.

Setelah backend aktif, jalankan frontend dengan membuka folder frontend-perpustakaan menggunakan Visual Studio Code. Buka file index.html, kemudian jalankan menggunakan ekstensi Live Server. Frontend akan ditampilkan melalui browser, biasanya pada alamat http://127.0.0.1:5500.

Pastikan backend dan frontend tetap berjalan secara bersamaan agar aplikasi dapat berfungsi dengan baik. Frontend akan berkomunikasi dengan backend melalui REST API yang telah dikonfigurasi pada file js/config.js dengan alamat http://localhost:8000/api. Setelah kedua bagian berhasil dijalankan, sistem informasi perpustakaan siap digunakan untuk mengelola data buku dan kategori.

[Link](pertemuan-01)
[Link](pertemuan-02)
[Link](pertemuan-03)
[Link](pertemuan-04)
[Link](pertemuan-05)
[Link](pertemuan-06)
[Link](pertemuan-07)