# 💻 Portfolio Website - PHP & MySQL

---

[![Licensi MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub Workflow Status](https://img.shields.io/badge/Status-Complete-brightgreen)]()

## 📝 Deskripsi Proyek

Aplikasi website portofolio untuk menampilkan profil, proyek, dan *skill* sebagai *web developer*. Proyek ini dibangun dari dasar menggunakan **PHP murni (Native PHP)** dan diintegrasikan dengan **MySQL** sebagai sistem manajemen basis data (DBMS), tanpa menggunakan *framework* pihak ketiga.

---

## ✨ Fitur Utama

* **Tampilan Portofolio Responsif:** Tampilan yang menyesuaikan dengan berbagai ukuran layar (desktop, tablet, mobile).
* **Halaman Proyek Dinamis:** Daftar proyek ditarik langsung dari database.
* **CRUD Admin:** (Create, Read, Update, Delete) untuk mengelola data proyek dan *skill* melalui panel admin (jika ada).
* **Formulir Kontak:** Pengiriman pesan langsung ke database/email admin.

---

## ⚙️ Tech Stack

| Teknologi | Versi | Catatan |
| :--- | :--- | :--- |
| **Backend** | PHP | Native PHP (disarankan PHP 8.0+) |
| **Database** | MySQL | Digunakan untuk menyimpan data portofolio dan *user admin*. |
| **Frontend** | HTML5, CSS3, JavaScript | Menggunakan Bootstrap 5 |
| **Server** | XAMPP/MAMP | Lingkungan lokal untuk menjalankan PHP dan MySQL. |

---

## 🚀 Instalasi dan Setup Lokal

Ikuti langkah-langkah ini untuk menjalankan website portofolio di komputer lokal Anda:

### Prasyarat

Pastikan Anda telah menginstal salah satu paket *server* lokal berikut:
* **XAMPP** (Windows, Linux) atau **MAMP** (macOS).

### Langkah-Langkah

1.  **Clone Repositori:** Buka terminal Anda dan *clone* proyek ini.
    ```bash
    git clone [https://github.com/MANG-CODER/portfolio-php-mysql.git](https://github.com/MANG-CODER/portfolio-php-mysql.git)
    cd portfolio-php-mysql
    ```

2.  **Siapkan Database:**
    * Buka **phpMyAdmin** (biasanya melalui `localhost/phpmyadmin`).
    * Buat database baru (misalnya, beri nama **`db_portfolio`**).
    * Impor file database yang disediakan (jika Anda memiliki file `.sql`).

3.  **Konfigurasi Koneksi:**
    * Temukan file koneksi database proyek Anda (biasanya `config.php` atau `db_connect.php`).
    * Ubah kredensial database di file tersebut (misalnya, `username` menjadi **`root`** dan `password` dikosongkan).

4.  **Jalankan Server:**
    * Pastikan layanan **Apache** dan **MySQL** sudah berjalan di XAMPP/MAMP Anda.

5.  **Akses Website:**
    * Buka *browser* Anda dan kunjungi alamat proyek Anda (misalnya, `http://localhost/portfolio-php-mysql`).

---

## 🖼️ Preview Tampilan
`![Preview Tampilan Portofolio](assets/preview1.png)`

`![Preview Tampilan Portofolio](assets/preview2.png)`

---

## 📜 Lisensi

Proyek ini dilisensikan di bawah **Lisensi MIT** (MIT License). Lihat file [LICENSE](LICENSE) untuk detail lengkap.

---

## ⌥ Penulis

Proyek ini dikembangkan dan dikelola oleh:

* **Si Ocong** (`@siocongs`) - [Profil GitHub](https://github.com/siocongs)
