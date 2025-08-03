# Aplikasi bank sampah

Nama : Djastiano Rivaldi

NIM : 312210366

Kelas : TI.22.C5

Mata Kuliah : Pemograman orientasi objek

- Project ini merupakan *Aplikasi Bank sampah* yang dikembangkan menggunakan *Apache Netbeans* dan database *MySQL*. Aplikasi ini bertujuan untuk mengelola data siswa secara sederhana, seperti menyimpan, memperbarui, dan menghapus data.

## 📂 Fitur Database
- **Manajemen Admin**: Mendukung level `Admin` dan `Master-admin` dengan informasi akun yang lengkap.
- **Manajemen Nasabah**: Menyimpan data pribadi nasabah, saldo tabungan, dan total sampah yang disetor.
- **Data Jenis Sampah**: Mencakup jenis, satuan (KG, PC, LT), harga, gambar, dan deskripsi sampah.
- **Transaksi Setor**: Mencatat detail penyetoran sampah (tanggal, berat, harga, dan total).
- **Transaksi Tarik**: Mencatat riwayat penarikan saldo oleh nasabah.

## 🧱 Struktur Tabel
- `admin`
- `nasabah`
- `sampah`
- `setor`
- `tarik`

## 🛠️ Tools & Teknologi yang Digunakan
- **PHP**: Bahasa pemrograman utama untuk backend (contoh: koneksi ke database, logika setor/tarik).
- **MySQL/MariaDB**: Sistem manajemen basis data relasional.
- **phpMyAdmin**: Antarmuka berbasis web untuk mengelola database MySQL.
- **XAMPP / Laragon / AMPPS**: Digunakan sebagai server lokal (Apache & MySQL) saat pengembangan.
- **HTML, CSS, JavaScript**: Digunakan untuk membangun tampilan antarmuka sistem.
- **VS Code / Sublime Text**: Editor kode untuk menulis skrip PHP, HTML, dan SQL.

## 📌 Tujuan Proyek
Sistem ini dirancang untuk membantu:
- Meningkatkan transparansi transaksi dalam pengelolaan bank sampah
- Memberikan kemudahan dalam monitoring saldo dan aktivitas nasabah
- Mempermudah pengelolaan jenis sampah dan penentuan harga jualnya

## 📥 Cara Import Database
1. Jalankan Apache dan MySQL melalui XAMPP/Laragon.
2. Akses `http://localhost/phpmyadmin`.
3. Buat database baru dengan nama: `bsk09`.
4. Gunakan menu **Import** untuk mengunggah file `bsk09.sql`.



