# Instalasi Laravel

Berikut adalah langkah-langkah untuk menginstal dan menjalankan proyek Laravel:

## Prasyarat

Pastikan Anda sudah memiliki:
- PHP >= 8.0
- Composer
- Web Server (Apache/Nginx)
- Database (MySQL, PostgreSQL, SQLite, atau SQL Server)

## Langkah Instalasi

1. **Clone Repository**

   Clone repository GitHub ke komputer lokal Anda:
   ```bash
   git clone https://github.com/username/repository-name.git
2. **Navigasi ke Direktori Proyek**
    cd repository-name
3. **Install Dependencies Menggunakan Composer**
    composer install
4. **Buat File Environment (.env)**
    cp .env.example .env
5. **Generate Application Key**
    php artisan key:generate
6. **Konfigurasi Database**
    DB_DATABASE=nama_database
    DB_USERNAME=user_database
    DB_PASSWORD=password_database
7. **Jalankan Migrasi Database**
    php artisan migrate
8. **Install Dependencies Frontend (Opsional)**
    npm install
9. **Jalankan Laravel Development Server**
    php artisan serve
11. Selesai

