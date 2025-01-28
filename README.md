# MarketSpare - Point of Sale (POS) Management System

**Deskripsi Singkat:**  
MarketSpare adalah aplikasi desktop berbasis Java yang dirancang
untuk mengelola penjualan dan inventaris sparepart mobil. 
Aplikasi ini dibangun menggunakan NetBeans sebagai IDE, MySQL sebagai database,
dan XAMPP untuk mengelola server database lokal. Aplikasi ini memudahkan pengguna 
dalam mengelola data penjualan, stok sparepart, dan laporan transaksi.

---

## Fitur Utama

- **Login:**
  - Sistem otentikasi untuk melindungi data.
- **Manajemen Sparepart:**
  - Tambah, edit, dan hapus data sparepart.
  - Melihat stok sparepart yang tersedia.
- **Manajemen Penjualan:**
  - Mencatat transaksi penjualan.
  - Menghitung total pembayaran secara otomatis.
- **Manajemen Suplier:**
  - Mengelola data suplier.
- **Manajemen User:**
  - Mengelola Karyawan.
  - Hak Akses untuk tiap karyawan.
- **Laporan:**
  - Menghasilkan laporan penjualan harian/bulanan.
  - Melihat riwayat transaksi.
- **Database Terintegrasi:**
  - Menggunakan MySQL untuk menyimpan data.
  - File SQL disediakan untuk impor database.

---

## Teknologi yang Digunakan

- **Bahasa Pemrograman:** Java
- **IDE:** NetBeans
- **Database:** MySQL
- **Server Database:** XAMPP (phpMyAdmin)
- **Lainnya:** JDBC (Java Database Connectivity) untuk koneksi database.


---

## Prasyarat

Sebelum menjalankan proyek ini, pastikan Anda telah menginstal dan menyiapkan:

1. **Java Development Kit (JDK):** Pastikan JDK terinstal di sistem Anda.
2. **NetBeans IDE:** Unduh dan instal NetBeans dari [situs resmi](https://netbeans.apache.org/).
3. **XAMPP:** Instal XAMPP untuk menjalankan server MySQL lokal. Unduh dari [situs resmi](https://www.apachefriends.org/).
4. **MySQL Connector/J:** Pastikan Anda memiliki file JAR MySQL Connector untuk koneksi database. Dapat diunduh dari [situs resmi MySQL](https://dev.mysql.com/downloads/connector/j/).

---

## Cara Menjalankan Proyek

### 1. Menyiapkan Database
1. Jalankan XAMPP dan aktifkan Apache serta MySQL.
2. Buka phpMyAdmin di browser (`http://localhost/phpmyadmin`).
3. Buat database baru dengan nama `marketspare`.
4. Impor file SQL (`marketspare.sql`) yang ada di folder `sql/` ke database `marketspare`.

### 2. Menyiapkan Proyek di NetBeans
1. Clone repositori ini:
   ```bash
   git clone https://github.com/ferynnd/MarketSpare.git
   
2. Buka NetBeans dan pilih File > Open Project,
   lalu pilih folder proyek MarketSpare.

3. Tambahkan MySQL Connector/J ke proyek:
    - Klik kanan pada proyek di NetBeans, pilih Properties > Libraries > Add JAR/Folder.
    - Pilih file JAR MySQL Connector yang telah diunduh.
      
4. Periksa koneksi database di file konfigurasi (jika ada)
   dan sesuaikan dengan pengaturan lokal Anda (username, password, dll.).

## 3. Cara Menjalankan Aplikasi

1.  Pastikan Anda telah menginstal Java Development Kit (JDK) dan NetBeans IDE.
2.  Buka proyek di NetBeans.
3.  Instal semua dependensi yang diperlukan.
4.  Tekan tombol Run untuk menjalankan aplikasi.

## Cara Menggunakan Aplikasi

1.  **Login:** Masukkan *username* dan *password* yang valid untuk masuk ke aplikasi.
2.  **Manajemen Sparepart:**
    *   Pilih menu "Tambah Sparepart" untuk menambahkan sparepart baru.
    *   Pilih menu "Edit Sparepart" untuk mengedit atau menghapus sparepart yang ada.
    *   Kelola data barang dari suplier.
3.  **Transaksi Penjualan:**
    *   Pilih menu "Penjualan".
    *   Pilih sparepart yang akan dijual.
    *   Masukkan jumlah.
    *   Selesaikan transaksi.
4.  **Managemen User:**
    *   Pilih menu "User".
    *   Kelola data user/karyawan.
    *   Atur hak akses user .
5.  **Managemen Suplier:**
    *   Pilih menu "Suplier".
    *   Tambah Data Suplier.
    *   Kelola Data Suplier .
6.  **Laporan:**
    *   Pilih menu "Laporan" untuk melihat laporan penjualan.
  
## File SQL

File SQL (`marketspare.sql`) berisi skema database dan data awal. 
Impor file ini ke database MySQL Anda sebelum menjalankan aplikasi.

Ferry Fernando

*   Email: ferryfernando164@gmail.com
*   LinkedIn: [Linkedin](https://www.linkedin.com/in/ferryfernandoo/)]
*   GitHub: [GitHub](https://github.com/ferynnd/)]

## Catatan Tambahan

Proyek ini adalah bagian dari portofolio saya dan akan terus dikembangkan. Jika Anda menemukan bug atau memiliki ide untuk perbaikan, jangan ragu untuk membuka issue atau mengirimkan pull request.

Terima kasih telah mengunjungi proyek ini!


