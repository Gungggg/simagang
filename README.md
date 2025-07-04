# SIMAGANG - Sistem Informasi Magang

<p align="center">
  <img src="https://uin-alauddin.ac.id/themes//images/favicon.png" width="100" alt="Logo UIN Alauddin">
</p>
<h3 align="center">Fakultas Sains dan Teknologi <br> Universitas Hasanuddin</h3>

---

> **DISCLAIMER:** Proyek ini adalah **proyek fiktif** yang dibuat untuk menyelesaikan mata kuliah **Analisis Perancangan Sistem Informasi**. Ini **bukan** merupakan sistem resmi yang digunakan oleh UIN Alauddin Makassar. Semua data yang ditampilkan adalah data tiruan (dummy data). Desain dan fungsionalitas dikembangkan sebagai bagian dari proses belajar-mengajar mengenai pengembangan antarmuka web modern.

## 📝 Deskripsi Proyek

**SIMAGANG** adalah prototipe Sistem Informasi Magang berbasis web yang dirancang untuk memfasilitasi dan mengelola seluruh proses kegiatan magang bagi mahasiswa di lingkungan Fakultas Sains dan Teknologi, UIN Alauddin Makassar. Sistem ini bertujuan untuk menjadi platform terpusat bagi mahasiswa, dosen pembimbing, dan sekretaris jurusan untuk berinteraksi dan mengelola semua dokumen serta progres terkait magang.

## 🔐 Hak Akses & Akun Demo

Proyek ini memiliki 3 peran utama dengan kredensial login sebagai berikut:

| Peran                  | Username     | Password | Halaman Tujuan                        |
| :--------------------- | :----------- | :------- | :------------------------------------ |
| **Mahasiswa**          | `mahasiswa`  | `12345`  | `./mahasiswa/dashboard.html`          |
| **Dosen Pembimbing**   | `dosen`      | `12345`  | `./dosen-pembimbing/dashboard.html`   |
| **Sekretaris Jurusan** | `sekretaris` | `12345`  | `./sekretaris-jurusan/dashboard.html` |

## 🚀 Teknologi yang Digunakan

Prototipe ini dibangun murni menggunakan teknologi front-end untuk memfokuskan pada desain antarmuka dan pengalaman pengguna (UI/UX).

- **HTML5:** Untuk struktur dasar halaman web.
- **Tailwind CSS v4 (via CDN):** Sebagai framework CSS utama untuk membangun desain yang modern dan responsif dengan cepat.
- **Alpine.js (via CDN):** Untuk interaktivitas sederhana pada komponen seperti _dropdown_ menu dan _sidebar mobile_.
- **JavaScript (Vanilla):** Untuk menangani logika sederhana seperti proses login dan validasi form di sisi klien.

## ⚙️ Instalasi dan Cara Menjalankan

Karena proyek ini menggunakan CDN untuk semua _library_-nya, tidak ada proses _build_ atau instalasi dependensi yang rumit.

1.  **Clone Repositori**

    ```bash
    git clone [https://github.com/username/simagang.git](https://github.com/username/simagang.git)
    cd simagang
    ```

    _(Ganti `username/simagang.git` dengan URL repositori Anda)_

2.  **Buka File HTML**
    Cukup buka file `index.html` (halaman login) langsung di browser Anda.

    Untuk pengalaman pengembangan terbaik, disarankan untuk menggunakan ekstensi **Live Server** di Visual Studio Code, yang akan secara otomatis me-refresh halaman saat Anda melakukan perubahan pada kode.

## 📁 Struktur Folder

Struktur folder proyek ini diatur berdasarkan peran pengguna untuk memudahkan navigasi.

```
simagang/
├── index.html              # Halaman Login Utama
├── assets/
│   └── images/
│       └── logo-uin.png
├── mahasiswa/
│   ├── dashboard.html
│   ├── logbook.html
│   ├── tambah-logbook.html
│   ├── laporan-akhir.html
│   ├── evaluasi-diri.html
│   └── profil.html
├── dosen-pembimbing/
│   ├── dashboard.html
│   ├── bimbingan.html
│   ├── bimbingan-detail.html
│   ├── validasi-logbook.html
│   └── profil.html
└── sekretaris-jurusan/
    ├── dashboard.html
    ├── permohonan-magang.html
    ├── proses-permohonan-magang.html
    ├── penetapan-dosbing.html
    └── profil.html
```
