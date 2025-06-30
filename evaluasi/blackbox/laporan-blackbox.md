# Blackbox Testing Volunteer Kampus

## Base URL
https://fuzzy-spork-5g9gww7qpg9734gx-5000.app.github.dev

## ✨ Deskripsi Singkat
Aplikasi manajemen relawan kampus berbasis web, dibangun menggunakan Python Flask. Mahasiswa dapat mendaftar sebagai relawan, dosen dapat meninjau dan menyetujui.

## 🚀 Cara Menjalankan Aplikasi

1. Aktifkan virtual environment (bila perlu):
   ```bash
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate    # Windows
   ```

2. Jalankan Flask:
   ```bash
   python app.py
   ```

3. Akses aplikasi melalui URL publik di Codespaces (biasanya muncul otomatis di PORTS).

---

## 🔍 Laporan Black-box Testing

**Nama Penguji:** Kartika ariyani
**Tanggal:** 29 Juni 2025  
**Metode:** Pengujian dilakukan menggunakan Selenium IDE (Firefox)

### 🎯 Tujuan Pengujian

Memastikan fitur-fitur utama (login, tambah data) pada aplikasi Volunteer-Kampus dapat digunakan sesuai ekspektasi pengguna tanpa melihat kode program (black-box).

### 🧪 Skenario Pengujian

| No | Skenario              | Langkah                                                                  | Hasil Diharapkan                  | Hasil Aktual |
|----|-----------------------|--------------------------------------------------------------------------|----------------------------------|--------------|
| 1  | Login Mahasiswa       | Klik tombol “Student” → isi email & password → klik Login               | Masuk ke dashboard mahasiswa     | ✅ Sesuai    |
| 2  | Tambah Data Volunteer | Klik tombol Add → isi form tambah → klik Submit                         | Data muncul di daftar volunteer  | ✅ Sesuai    |
| 3  | Navigasi              | Cek apakah halaman tetap berjalan normal tanpa tombol logout            | Sistem tetap stabil              | ✅ Sesuai    |

### 📎 File Pengujian

- File Selenium IDE: [`blackbox-volunteer.side`](evaluasi/blackbox/blackbox-volunteer.side)

###  Kesimpulan

Semua fitur yang diuji telah berjalan dengan baik. Fitur logout belum tersedia, namun tidak mengganggu stabilitas aplikasi. Aplikasi layak digunakan oleh mahasiswa dan dosen.