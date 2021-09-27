## E-Modul Java Backend
====
E-Modul Java Backend adalah API untuk mengintegrasikan aplikasi E-Modul Java yang berbasis Android menggunakan bahasa Java dengan Backend yang dibuat dengan Framework Laravel.

Cara Install Laravel 8 (UI Auth) dan Github
--------
- Install Composer (https://getcomposer.org/download/)
- Install NodeJS (https://nodejs.org/en/)
- Install Git (https://git-scm.com/)
- Buka command prompt / git bash pada folder yang diinginkan untuk menyimpan project
- Ketik "composer create-project laravel/laravel example-app"
- Pada command prompt / git bash, masuk ke dalam folder example-app (dengan command "cd")
- Ketik command "composer require laravel/ui" dan tunggu selesai.
- Ketik command "php artisan ui vue --auth" (Selain vue, ada bootstrap dan react)
- Ketik command "npm install && npm run dev" dan tunggu selesai. Apabila terdapat error (baca dulu error kenapa) dan coba beberapa command berikut :
-- "composer update"
-- "npm update"
-- Google sendiri error kenapa
- Bila sukses, buka kembali command prompt / git bash
- Ketik command "git init"
- Ketik command "git add ."
- Ketik command "git commit -m "Initial commit"" (Tanpa tanda " di awal dan akhir command)
- Buka https://github.com/, buat repository baru, lalu salin ssh/url pada git remote (contoh : git@github.com/suganda8/LXIV.git atau https://github.com/suganda8/LXIV.git)
- Ketik command "git remote add origin (ssh/url)"
-- Bila menggunakan SSH (git@github.com) perlu menghubungkan membuat dan menghubungkan lokal SSH dengan Github
- Ketik command "git push origin master" (Bila nama branch master sebelumnya tidak ada, akan otomatis membuat master, karena master ditulis pada git push)
