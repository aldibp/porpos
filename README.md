Framework Laravel 
menggunakan berbagai Package Library

Fitur-fitur ini diantaranya =>
- Administrasi buku untuk Admin
- Administrasi user untuk Admin
- Administrasi untuk Registered User
- Peminjaman buku untuk Registered User
- Browsing buku untuk non-member
- Dashboard dengan chart untuk Admin
- Import dan Export Excel
- Export PDF

setting jika ingin mencoba =>
- composer install, 
- ubah .env.example menjadi .env (copy saja)
- lalu art key:generate
- Daftar ke https://www.google.com/recaptcha. Pada file .env ,
  isi NOCAPTCHA_SECRET dan NOCAPTCHA_SITEKEY dengan key yang didapatkan
- Daftar ke http://www.mailgun.com4. Pada file .env , 
  isi MAILGUN_DOMAIN dengan data dari https://mailgun.com/app/domains5 dan isi MAILGUN_SECRET dengan data private api key dari   https://mailgun.com/app/account/settings
- konfigurasi Database pada .env
- art migrate:refresh --seed
- jalankan localhost art serve atau menggunakna homestead
- masukkan username dan password sesuai UsersSeeder. 
