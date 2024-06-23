Langkah-langkah untuk membuka proyek :

- Download .zip
- Extract folder
- Buka terminal pada folder yang baru diekstrak
- Ketikan .code agar proyek dapat dibuka melalui kode editor
- Pada terminal ketik "composer install"
- Pada terminal ketik "npm install"
- Buka file .env.example kemudian copy seluruh kode ke dalam file .env untuk konfigurasi database
- Pada terminal ketik "php artisan key:generate"
- Buat folder database baru pada locallhost anda, misal "karyawandb". Pastikan nama database sesuai dengan yang ada pada file .env
- Pada terminal ketik "php artisan migrate --seed"
- Pada terminal ketik "php artisan storage:link"
- Jalankan proyek dengan "php artisan serve"
- Login menggunakan akun : email/kata sandi = selly@gmail.com/password
