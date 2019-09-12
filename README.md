# Build a React application with Laravel Backend

Project ini adalah demo dasar untuk menjalankan Laravel dan React secara bersama. Anda dapat membaca tutorialnya di [Blog Mata Panda Crew](https://matapanda-crew.blogspot.com/2019/09/membangun-aplikasi-react-dengan-laravel.html)

## Setting up the Demo


Anda harus memiliki semua dependensi laravel dan npm / yarn untuk menggunakan demo ini. Klon pertama repo atau unduh sebagai zip.
Selanjutnya, pastikan Anda berada di branch yang benar. Jika Anda di sini hanya untuk API Laravel, Anda harus melihat `laravelapi`. Jika Anda berada di sini untuk Laravel + React code, Anda hanya perlu `branch` master.

### Laravel Back end
Atur DB, file .env Anda, urus migrasi dan seeding. Jika Anda ragu, membaca tutorial akan membuat Anda berada di jalur yang benar. Setelah selesai, jalankan `php artisan serve`. Api dapat diakses di `http://localhost:8000/api/products`

### React front-end

Untuk membuat React berfungsi, jalankan `npm install && npm run dev`. Atau Anda juga dapat menggunakan yarn di atas npm. Sekarang, pergilah ke`http://localhost:8000/`
