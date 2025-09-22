# projek_akhir

# Sistem Point of Sale (POS)

Sistem **Point of Sale (POS)** ini dirancang untuk memudahkan pemilik usaha dalam mengelola transaksi penjualan, inventaris produk, dan laporan keuangan secara efisien. Dengan antarmuka yang user-friendly dan fitur yang lengkap, sistem ini dapat mengoptimalkan operasional bisnis Anda, baik itu bisnis kecil maupun besar.

## 🚀 Fitur Utama

- **Manajemen Produk**  
  Tambah, edit, atau hapus produk dengan mudah untuk menjaga inventaris Anda selalu terupdate.

- **Proses Transaksi Penjualan**  
  Transaksi penjualan dilakukan dengan cepat, membantu kasir melayani pelanggan lebih efisien.

- **Laporan Penjualan**  
  Akses laporan penjualan harian, bulanan, dan tahunan untuk analisis bisnis yang lebih baik.

- **Pengelolaan Pelanggan**  
  Simpan data pelanggan secara otomatis untuk mempercepat proses transaksi dan meningkatkan layanan.

- **Multi-User Support**  
  Dukung lebih dari satu pengguna dengan hak akses yang berbeda, memudahkan kolaborasi dalam manajemen toko.

## 💻 Teknologi yang Digunakan

- **Bahasa Pemrograman**: PHP, JavaScript
- **Database**: MySQL
- **Alat Pengembangan**: Git

# Steampunk Circus Emporium

A grand web-based cashier system for a medieval, steampunk-inspired circus, managing tickets, merchandise, schedules, admins, and patrons. Built with PHP, MySQL, and styled with W3.CSS and Tailwind CSS, it embodies a vintage aesthetic with brass and wood tones.

## Features
- **Admin and User Login**: Secure authentication for stewards (admins) and patrons (customers).
- **Product Management**: Catalog tickets and merchandise with categories.
- **Order Processing**: Track orders with total payments and products.
- **Schedules**: Display upcoming circus performances.
- **Steampunk Aesthetic**: Medieval and old-fashioned design with brass (#d4a373) and wood (#8b5a2b) tones.

## Setup
1. Import `project_akhir.sql` into MySQL.
2. Configure `config/config.php` with your database credentials.
3. Place the project in your web server (e.g., XAMPP's `htdocs`).
4. Access via `http://localhost/cashier-circus`.

## Folder Structure
- `add/`: Scripts for adding admins, categories, customers, and products.
- `config/`: Database configuration.
- `errors/`: Custom error pages (403, 404, 500).
- `middleware/`: Session and authentication logic.
- `font/`: Placeholder for custom fonts.
- `public/assets/`: CSS, JS, and images for the steampunk theme.
