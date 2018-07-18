Setelah Clone :

1. Ganti .env.example menjadi .env
2. Setting .env seperti ini :
=================
APP_NAME=Laravel
APP_ENV=local
APP_KEY=base64:UKMlN5wsx6sKeMfGzaPTCdll+OpCBNgJH2XFL6OVu+I=
APP_DEBUG=true
APP_URL=http://localhost

LOG_CHANNEL=stack

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=(isi nama database)
DB_USERNAME=(isi username database 'standart = root')
DB_PASSWORD=(isi password database 'standart = tidak diisi')

BROADCAST_DRIVER=log
CACHE_DRIVER=file
SESSION_DRIVER=file
SESSION_LIFETIME=120
QUEUE_DRIVER=sync

REDIS_HOST=127.0.0.1
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_DRIVER=smtp
MAIL_HOST=smtp.gmail.com
MAIL_PORT=587
MAIL_USERNAME=(masukan email untuk mengirim verifikasi)
MAIL_PASSWORD=(masukan password untuk mengirim verifikasi)
MAIL_ENCRYPTION=tls

PUSHER_APP_ID=
PUSHER_APP_KEY=
PUSHER_APP_SECRET=
PUSHER_APP_CLUSTER=mt1

MIX_PUSHER_APP_KEY="${PUSHER_APP_KEY}"
MIX_PUSHER_APP_CLUSTER="${PUSHER_APP_CLUSTER}"
======================================================
