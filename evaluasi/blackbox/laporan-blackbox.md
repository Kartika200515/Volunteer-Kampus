
## 🔍 Laporan Black-box Testing

**Nama Penguji:** Kartika  
**Tanggal:** 29 Juni 2025  
**Metode:** Pengujian dilakukan menggunakan Selenium IDE (Firefox)

### 🎯 Tujuan Pengujian

Memastikan fitur-fitur utama (login, tambah data, logout) pada aplikasi Volunteer-Kampus dapat digunakan sesuai ekspektasi pengguna tanpa melihat kode program (black-box).

### 🧪 Skenario Pengujian

| No | Skenario              | Langkah                                                                  | Hasil Diharapkan                  | Hasil Aktual |
|----|-----------------------|--------------------------------------------------------------------------|----------------------------------|--------------|
| 1  | Login Mahasiswa       | Klik tombol “Student” → isi email & password → klik Login               | Masuk ke dashboard mahasiswa     | ✅ Sesuai    |
| 2  | Tambah Data Volunteer | Klik tombol Add → isi form tambah → klik Submit                         | Data muncul di daftar volunteer  | ✅ Sesuai    |
| 3  | Logout                | Klik tombol Logout                                                       | Kembali ke halaman login         | ✅ Sesuai    |

### 📎 File Pengujian

- File Selenium IDE: [`blackbox-volunteer.side`](evaluasi/blackbox/blackbox-volunteer.side)

### Kesimpulan

Semua fitur yang diuji telah berjalan dengan baik. Tidak ditemukan error pada saat pengujian berlangsung. Aplikasi layak digunakan oleh mahasiswa dan dosen.

