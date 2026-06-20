<h1 align="center">Sistem Inventaris Barang</h1>

**Cloned by: Baron Wahyu Gumelar**  
Date: 2026-06-20

---
## 🚀 Fitur Utama

- **Data Management:**
  - ChartJS
  - Departemen/Unit
  - Supplier
  - Lokasi
  - Jenis Pengadaan
  - Kategori Barang
  - Barang
  - Pengadaan, Penempatan, Mutasi, Peminjaman, Pengembalian, Retur, Disposal
- **Akun dan Hak Akses:**
  - Multi Akun dengan Profil Kustom
  - Group Permission dan Custom Permission
- **Fitur Lanjutan:**
  - Upload Gambar
  - Rich Text Editor
  - Konfigurasi Dinamis
  - Pencarian & Filter Data
  - Aksi Cepat (Bulk)
  - Ekspor Excel & PDF

## 🛠️ Teknologi yang Didukung

![PHP](https://img.shields.io/badge/PHP-8.0%20to%208.2-darkblue)
![CodeIgniter](https://img.shields.io/badge/CodeIgniter-3.1.13-red)
![Bootstrap](https://img.shields.io/badge/Bootstrap-4.6.2-purple)
![jQuery](https://img.shields.io/badge/jQuery-3.6.0-blue)

- **Server:**
  - ![XAMPP](https://img.shields.io/badge/XAMPP-8.0.3--8.2.12-orange)
  - ![Apache2](https://img.shields.io/badge/Apache2-%3E%3D2.4.54-red)
  - ![NGINX](https://img.shields.io/badge/NGINX-%3E%3D1.23.3-brightgreen)
- **Database:**
  - ![MySQL](https://img.shields.io/badge/MySQL-%3E%3D5.7-lightblue)
  - ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%3E%3D6.5-blue)

---

## 📝 ChangeLog
### Versi 3.1 (Terbaru)

- **Bug Fixes:**
  - Fixed pagination issue caused by incorrect URL segment configuration.
  - Resolved incompatibility with SQL ONLY_FULL_GROUP_BY mode by changing the data retrieval method for ChartJS on the dashboard from direct SQL queries to CodeIgniter Query Builder.
  - Cleaned up backend functionality for alternate text handling of images, specifically for index pages and PDF exports.

#### Versi 3.0

- **Additions:**
  - ChartJS Integration on Dashboard
  - Organisation Name and Logo in Website Settings
  - PostgreSQL Database Support
  - Support for PHP 8.2 up to the latest version
  
- **Improvements:**
  - Validate the minimum password length in the add user form and fix missing password input field
  - [Bulk] data delete feature changed to [Aksi Cepat]
  - Improvement on user profile regarding lost roles after saving
  - Table export (PDF/Excel) now supports images
  - Group information in user profiles no longer always shows the currently logged in user
  - Page redirection after login
  - Language fixed and improved
  
- **Increases:**
  - Excel export library change from PHPExcel to PHPOffice
  - PDF export library change from HTML2PDF to TCPDF
  - Landing page redesign

#### Versi 2.4
- Bug Fixes on Security Issues
- Minor Bug Fix in Menu Akun
- Deleting Role Selector on User Account Profile Menu
- Changes Sub-Menu from [Role] to [Group]
- Minor Changes to the Database

#### Versi 2.3
- Added Feature **Disposal (Penghapusan Asset)**
- Reconfigure MySQL Database 
- Bug Fixed on MySQL Database Trigger Function

#### Versi 2.2
- Added Responsive Icons and Links
- Improve UI Appearance

#### Versi 2.1
- Added Informasi
- Minor Bug Fixed
- Fixed Typo

#### Versi 2.0
- Upgrade Framework
- Major Bug Fixed
- Add PostgreSQL Support

#### Versi 1.0
- First Release
