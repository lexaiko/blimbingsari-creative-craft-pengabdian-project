# 🎨 Blimbingsari Creative Craft • Pengabdian Masyarakat

Repositori ini adalah proyek sistem informasi katalog produk **kerajinan tangan Blimbingsari** yang dikembangkan dalam rangka **Program Pengabdian Masyarakat**. Fokus utama adalah menghadirkan platform digital untuk membantu pelaku UMKM mempromosikan produk-produk lokal khas Nusantara melalui media online.

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-11-red?style=flat&logo=laravel">
  <img src="https://img.shields.io/badge/TailwindCSS-3.x-38bdf8?style=flat&logo=tailwindcss">
  <img src="https://img.shields.io/badge/MySQL-8-blue?style=flat&logo=mysql">
  <img src="https://img.shields.io/github/last-commit/lexaiko/blimbingsari-creative-craft-pengabdian-project">
</p>

---

## 🌿 Latar Belakang

Blimbingsari, Banyuwangi dikenal dengan komunitas pengrajin kreatif yang memproduksi **gelang, kalung, tas rajut, dan kerajinan berbasis anyaman tradisional**.  
Proyek ini dibuat untuk:

- 💼 Mendukung digitalisasi produk lokal
- 🛒 Menyediakan katalog produk handmade yang dapat diakses publik
- 🌐 Membantu pelaku UMKM mempromosikan produknya secara online
- 👨‍👩‍👧‍👦 Memberikan pelatihan digital branding melalui website

---

## ✨ Fitur Aplikasi

- 🛍️ **Katalog Produk Handmade**: Lengkap dengan foto, deskripsi, dan ukuran
- 📂 **Kategori Dinamis**: Menampilkan produk berdasarkan kategori (Gelang, Tas, Kalung, dll.)
- 📝 **Manajemen Artikel**: Edukasi budaya & informasi kegiatan pengrajin
- 📸 **Upload Gambar Produk**: Mendukung banyak gambar per produk
- 🌐 **Multi Bahasa (ID / EN)**: Dengan deteksi otomatis atau manual switch
- 🔐 **CRUD Admin**: Admin dashboard untuk kelola data produk, artikel, user
- 📱 **Desain Responsif**: Mobile-friendly dengan Tailwind CSS & Flowbite

---

## 🧰 Teknologi yang Digunakan

| Layer       | Teknologi                    |
|-------------|------------------------------|
| Backend     | Laravel 11                   |
| Frontend    | Tailwind CSS + Flowbite      |
| Database    | MySQL                        |
| Deploy Tool | Laravel Vite, Artisan CLI    |
| Ekstensi    | Google Translate PHP (Stichoza) |

---

## 🚀 Instalasi Lokal

```bash
# 1. Clone repo
git clone https://github.com/lexaiko/blimbingsari-creative-craft-pengabdian-project.git
cd blimbingsari-creative-craft-pengabdian-project

# 2. Install dependencies
composer install
npm install && npm run dev

# 3. Setup environment
cp .env.example .env
php artisan key:generate

# 4. Atur koneksi database, lalu:
php artisan migrate --seed

# 5. Jalankan server lokal
php artisan serve
