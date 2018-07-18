Setelah Clone :

1. php artisan migrate > composer install > composer update
2. ganti .env.example menjadi .env
3. setting .env dengan database
4. Setting mail dengan settingan :
   - MAIL_DRIVER=smtp
   - MAIL_HOST=smtp.gmail.com
   - MAIL_PORT=587
   - MAIL_USERNAME=(isi dengan email yang akan digunakan)
   - MAIL_PASSWORD=(isi dengan password email yang akan digunakan)
   - MAIL_ENCRYPTION=tls
5. Setting di Gmail yang akan digunakan :
   - ke Google Account > Sign-in & Security > '*scroll paling bawah*' Hidupkan Allow less secure apps  
6. Setting di mail.php :
   - 'host' => env('MAIL_HOST', 'smtp.gmail.com'),
   - 'from' => [
        - 'address' => env('MAIL_FROM_ADDRESS', 'email yang digunakan'),
        - .'name' => env('MAIL_FROM_NAME', 'No-reply - Activation Link Account'),
    ]
