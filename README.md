## Setup
- buka direktori project di gitBash
- ketikan command : cp .env.example .env (untuk membuat file .env)
- buat database dengan nama laravel

Lalu ketik command dibawah ini
- composer install
- php artisan optimize:clear 
- php artisan key:generate
- php artisan migrate (migrasi database)
- php artisan db:seed --class=UserSeeder (untuk mengisi data pada table users)

## Login
Untuk Login tambahkan '/login' pada penelusuran browser

Email dan Password pada halaman Login
- Email : admin@gmail.com
- Password : password

tambahan :
- Setelah memasuki dashboard admin, silakah tambahkan 'admin/about' untuk ke halaman crud about
- Setelah memasuki dashboard admin, silakah tambahkan 'admin/portfolio' untuk ke halaman crud portfolio
- Setelah memasuki dashboard admin, silakah tambahkan 'admin/skill' untuk ke halaman crud skill
