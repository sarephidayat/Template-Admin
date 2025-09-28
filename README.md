# Template-Admin
# Laravel Admin Dashboard Template

Proyek ini adalah **template dashboard admin** berbasis Laravel 11 yang sudah terintegrasi dengan autentikasi sederhana dan beberapa modul seperti **Dosen**.
Template ini bisa digunakan sebagai dasar untuk membangun sistem informasi akademik, manajemen data, dan lain-lain.

---

## 🚀 Fitur

* Autentikasi login & logout sederhana
* Dashboard dengan statistik data
* CRUD untuk Dosen
* Tampilan UI berbasis Bootstrap & Stisla Template

---

## 📦 Instalasi

Ikuti langkah-langkah berikut untuk menjalankan project ini di lokal:

### 1. Clone Repository

```bash
git clone https://github.com/username/nama-project.git
cd nama-project
```

### 2. Install Dependency

```bash
composer install
```

### 3. Salin File Environment

```bash
cp .env.example .env
```

> Untuk Windows, copy manual lalu rename `.env.example` menjadi `.env`.

### 4. Generate App Key

```bash
php artisan key:generate
```

### 5. Konfigurasi Database

Edit file `.env` sesuai database lokal Anda:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nama_db
DB_USERNAME=root
DB_PASSWORD=
```

### 6. Migrasi & Seeder

```bash
php artisan migrate --seed
```

Seeder akan otomatis membuat akun default untuk login.

### 7. Jalankan Server

```bash
php artisan serve
```

Akses di browser:
👉 [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🔑 Akun Default

Gunakan akun berikut untuk login pertama kali:

* **Username:** `admin`
* **Password:** `123456`

---

