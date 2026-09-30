# ROADMAP BELAJAR BACKEND WEB DEV (PHP → MySQL → Laravel)

**Pemilik:** Fatih (D3 TI, Politeknik Negeri Cilacap, sekarang semester 3)
**Target:** ±1 tahun ke depan (sebelum magang semester 5) jadi junior backend developer yang siap ambil proyek freelance kecil.
**Waktu belajar:** 3-4 jam/hari, Senin-Sabtu. Minggu istirahat.
**Stack utama:** PHP, MySQL, Laravel. HTML+CSS secukupnya.
**Kondisi awal:** fundamental masih berantakan (lupa syntax, OOP belum paham, belum bisa menyambungkan semua bagian). Jadi mulai dari dasar, tanpa malu.

---

## 0. Aturan Main (wajib)

1. **Ketik sendiri, jangan copy-paste.** Syntax nempel lewat jari dan otak, bukan lewat mata.
2. **AI hanya untuk menjelaskan, bukan menulis kode.** Kalau error, minta AI jelasin *kenapa* error-nya. Coba sendiri minimal 15 menit sebelum bertanya.
3. **Jam belajar tetap tiap hari.** HP jauh dari meja atau mode pesawat. Game dan scrolling setelah jam belajar selesai, sebagai hadiah.
4. **Kalau males, janji 25 menit saja.** Biasanya setelah mulai, lanjut sendiri.
5. **Commit ke GitHub tiap hari belajar**, walau kecil.
6. **Jangan loncat fase** sebelum checkpoint fase itu terpenuhi. Lebih baik lambat tapi nempel.

## 1. Pola Belajar Tiap Topik (sekitar 3 jam)

| Durasi | Kegiatan |
|---|---|
| 30 menit | Baca atau nonton materi |
| 30 menit | Ketik ulang contoh persis |
| 1 jam | Ubah-ubah contoh, lalu bikin latihan dari nol tanpa lihat contoh |
| 30 menit | Soal tantangan |
| 10 menit | Catat apa yang dipelajari, lalu commit |

Kalau punya 4 jam, tambahkan waktunya di sesi latihan.

**Sumber belajar:**
- YouTube: Web Programming UNPAS (playlist PHP dasar)
- Situs: Petani Kode (bahasa Indonesia)
- Referensi resmi: php.net/manual, dokumentasi Laravel (laravel.com/docs), W3Schools PHP

## 2. Gambaran Besar

| Fase | Durasi | Fokus | Hasil akhir |
|---|---|---|---|
| Phase 1 | Minggu 1-12 | PHP dasar | Mini Project #1 |
| Phase 2 | Minggu 13-24 | OOP + MySQL + CRUD | Mini Project #2 |
| Phase 3 | Minggu 25-36 | Laravel | Mini Project #3 |
| Phase 4 | Minggu 37-44 | Portofolio + persiapan freelance | Profil siap, proyek pertama |
| Buffer | Sisa 1-2 bulan | Mengejar ketertinggalan / pendalaman | Siap masuk magang |

---

## PHASE 1: PHP DASAR (Minggu 1-12)

**Tujuan:** bisa menulis program PHP sendiri tanpa lihat contoh dan tanpa AI.

### Setup awal (Hari 1)
- [x] Laragon jalan, folder `belajar-php` di dalam `www`, `index.php` bisa dibuka lewat `localhost`
- [x] VS Code terpasang
- [x] Akun GitHub + repo `belajar-php`
- [x] Hafal 5 perintah Git: `git init`, `git add .`, `git commit -m "pesan"`, `git remote add origin`, `git push`

### Week 1: Dasar PHP
- [ ] **Hari 1:** Setup + Git + Hello World (`<?php echo "Hello World"; ?>`), paham tag pembuka/penutup
- [ ] **Hari 2:** Variabel (`$nama = "Fatih";`), tipe data (string, integer, float, boolean), `var_dump()`, `gettype()`. Latihan: biodata
- [ ] **Hari 3:** String dan output: `echo`, penggabungan dengan `.`, variabel di dalam kutip ganda, `strlen`, `strtoupper`, `str_replace`, `substr`
- [ ] **Hari 4:** Operator aritmatika (`+ - * / %`), perbandingan (`== === != > <`), logika (`&& || !`). Paham beda `==` dan `===`. Latihan: kalkulator, cek genap/ganjil
- [ ] **Hari 5:** Latihan gabungan tanpa lihat contoh: konversi suhu, hitung BMI, hitung diskon
- [ ] **Hari 6:** Review. Tulis ulang dari ingatan: variabel, operator, `echo`
- [ ] **Hari 7:** Istirahat

### Week 2: Percabangan dan perulangan
- [ ] **Hari 8:** `if / elseif / else`. Latihan: lulus/tidak lulus, grade A/B/C/D
- [ ] **Hari 9:** `switch` dan kondisi bertingkat. Latihan: nama hari dari angka 1-7, menu sederhana
- [ ] **Hari 10:** `for`. Latihan: angka 1-100, jumlah 1 sampai N, tabel perkalian
- [ ] **Hari 11:** `while`, `break`, `continue`. Latihan: tebak angka, hitung mundur
- [ ] **Hari 12:** Loop bertingkat. Latihan: pola bintang, faktorial, Fibonacci
- [ ] **Hari 13:** Tantangan "Cek Nilai Mahasiswa": simpan nilai, hitung rata-rata, tentukan grade, tampilkan hasil
- [ ] **Hari 14:** Uji diri: 5 soal tanpa contekan (variabel, operator, if, for, while). Lalu istirahat

### Week 3-4: Function dan scope
- [ ] Membuat function, parameter, nilai default, return value
- [ ] Scope (variabel lokal vs global), `global` dan cara menghindarinya
- [ ] Function bawaan PHP yang sering dipakai (string, angka, tanggal)
- [ ] Latihan: 15-20 function kecil (hitung luas, cek palindrom, cek bilangan prima, format rupiah, dst)
- [ ] Paham kapan sebuah kode sebaiknya dijadikan function

### Week 5-6: Array
- [ ] Array biasa (indexed) dan asosiatif (key => value)
- [ ] Array bersarang (nested)
- [ ] `foreach`, `count`, `array_push`, `array_pop`, `array_merge`, `in_array`, `sort`, `array_filter`, `array_map`
- [ ] Latihan: daftar mahasiswa dan nilainya, cari nilai tertinggi, filter yang lulus, urutkan ranking

### Week 7-8: PHP + HTML form
- [ ] Form HTML mengirim data ke PHP (`$_GET`, `$_POST`)
- [ ] Validasi dasar (kolom kosong, format angka)
- [ ] `htmlspecialchars()` supaya input aman ditampilkan
- [ ] `include` / `require` untuk memecah file (header, footer)
- [ ] Latihan: form biodata, form kalkulator, form login sederhana (data masih tulis manual di kode)

### Week 9-12: Mini Project #1 "Sistem Nilai Mahasiswa"
- [ ] Form input nama dan beberapa nilai mata kuliah
- [ ] Hitung rata-rata, tentukan grade, urutkan ranking
- [ ] Pakai function, array, loop, if, dan form
- [ ] Kode rapi, dipecah ke beberapa file
- [ ] README di GitHub: apa ini, cara menjalankan, tangkapan layar
- [ ] Week 12: buffer untuk mengulang materi yang masih lemah

**Checkpoint Phase 1 (harus terpenuhi sebelum lanjut):**
- [ ] Bisa menulis variabel, if, loop, function, dan array tanpa lihat contoh
- [ ] Mini Project #1 jalan dan ada di GitHub dengan README
- [ ] Bisa menjelaskan kode sendiri dengan kata-kata sendiri

---

## PHASE 2: OOP + DATABASE (Minggu 13-24)

**Tujuan:** paham OOP dasar dan bisa membuat aplikasi CRUD dengan PHP + MySQL.

### Week 13-16: OOP
- [ ] Class dan object, property dan method
- [ ] Constructor
- [ ] Access modifier (`public`, `private`, `protected`), getter/setter
- [ ] Static vs instance
- [ ] Inheritance dan konsep polymorphism dasar
- [ ] Latihan: class `User`, `Product`, `Mahasiswa`; ulangi Mini Project #1 versi OOP
- [ ] Tips: kaitkan dengan materi PBO (Java) di kuliah, konsepnya sama, syntax-nya beda

### Week 17-20: MySQL
- [ ] Tabel, primary key, foreign key
- [ ] `SELECT`, `INSERT`, `UPDATE`, `DELETE`
- [ ] `WHERE`, `ORDER BY`, `LIMIT`, `LIKE`
- [ ] `JOIN` (INNER dan LEFT) dan relasi antar tabel (satu-ke-banyak)
- [ ] Latihan: rancang database toko sederhana (user, produk, pesanan) dan latihan query
- [ ] Trigger dan stored procedure: ikuti dari materi kuliah, bukan prioritas roadmap ini

### Week 21-24: PHP + MySQL (CRUD)
- [ ] Koneksi ke MySQL pakai PDO
- [ ] Prepared statement (mencegah SQL injection)
- [ ] Menampilkan data dari database
- [ ] Tambah, ubah, hapus data dari form
- [ ] `password_hash()` dan `password_verify()` untuk password
- [ ] Session dasar untuk login
- [ ] **Mini Project #2 "Todo App"** atau aplikasi CRUD kecil lain: login, tambah/ubah/hapus tugas, tandai selesai
- [ ] README + push ke GitHub

**Checkpoint Phase 2:**
- [ ] Bisa membuat class sendiri dan menjelaskan fungsinya
- [ ] Bisa menulis query `JOIN` sederhana tanpa contekan
- [ ] Mini Project #2 jalan (CRUD + login) dan ada di GitHub

---

## PHASE 3: LARAVEL (Minggu 25-36)

**Tujuan:** bisa membuat aplikasi web lengkap dengan Laravel, dan paham cara semua bagiannya tersambung.

### Week 25-28: Dasar Laravel
- [ ] Instalasi dan struktur folder Laravel
- [ ] Konsep MVC (Model, View, Controller)
- [ ] Routing
- [ ] Controller
- [ ] Blade template (layout, komponen, loop, kondisi)
- [ ] Migration dan seeder
- [ ] Konfigurasi `.env` dan koneksi database

### Week 29-32: Laravel lanjutan
- [ ] Eloquent ORM: model, CRUD lewat model
- [ ] Relasi antar model (`hasMany`, `belongsTo`)
- [ ] Validasi form
- [ ] Autentikasi memakai starter kit resmi Laravel
- [ ] Middleware dasar
- [ ] Latihan: ulangi Todo App versi Laravel, bandingkan dengan versi PHP murni

### Week 33-36: Mini Project #3 "Sistem Blog"
- [ ] Model: User, Post, Comment
- [ ] CRUD post, hanya pemilik post yang bisa ubah/hapus
- [ ] Sistem komentar
- [ ] Login dan register
- [ ] Tampilan rapi (HTML+CSS seperlunya, tidak perlu mewah)
- [ ] README lengkap + tangkapan layar
- [ ] Push ke GitHub

**Checkpoint Phase 3:**
- [ ] Bisa membuat CRUD Laravel dari nol dengan membuka dokumentasi (bukan copy-paste dari AI)
- [ ] Bisa menjelaskan alur satu request: route → controller → model → view
- [ ] Mini Project #3 jalan dan ada di GitHub

---

## PHASE 4: PORTOFOLIO + PERSIAPAN FREELANCE (Minggu 37-44)

**Tujuan:** punya portofolio yang bisa ditunjukkan dan siap mengambil proyek kecil.

### Week 37-40: Rapikan portofolio
- [ ] Review 3 mini project: rapikan kode, hapus yang tidak terpakai
- [ ] README tiap project: deskripsi, fitur, teknologi, cara menjalankan, tangkapan layar
- [ ] Rapikan profil GitHub (foto, bio, pin 3 project terbaik)
- [ ] Deploy minimal 1 project ke hosting (riset hosting gratis/murah yang mendukung PHP)
- [ ] Buat CV singkat (Indonesia dan versi English sederhana)
- [ ] Polish sistem bengkel yang pernah dibuat: pahami sendiri kodenya, perbaiki bagian yang belum kamu mengerti, lalu masukkan sebagai project keempat

### Week 41-44: Persiapan freelance
- [ ] Riset platform: Fastwork, Sribulancer (lokal), Upwork/Fiverr (internasional, butuh English lebih baik)
- [ ] Buat profil di 1-2 platform saja dulu
- [ ] Siapkan 3 contoh layanan yang kamu tawarkan (misal: website company profile sederhana, sistem CRUD, perbaikan bug PHP)
- [ ] Ambil 1 proyek kecil (boleh murah, bahkan untuk teman atau UMKM) demi pengalaman dan testimoni
- [ ] Belajar cara estimasi waktu dan harga proyek

**Checkpoint Phase 4:**
- [ ] 3-4 project di GitHub dengan README bagus
- [ ] Minimal 1 project online
- [ ] Profil freelance siap
- [ ] Minimal 1 proyek kecil sudah dikerjakan atau sedang berjalan

### Buffer (sisa 1-2 bulan sebelum magang)
- Ulangi materi yang masih lemah
- Perdalam satu topik (API/REST, Git branching, atau dasar keamanan web)
- Siapkan diri untuk magang (dokumentasikan apa yang dikerjakan)

---

## JALUR PARALEL

### Bahasa Inggris (15-30 menit/hari)
- Baca dokumentasi (php.net, Laravel) dalam bahasa Inggris, jangan langsung terjemahkan semuanya
- Catat 5 kosakata teknis baru tiap hari
- Nonton tutorial berbahasa Inggris dengan subtitle Inggris (melatih listening yang masih lemah)
- Tulis commit message dan README dengan English sederhana
- Manfaatkan matkul Bahasa Inggris Teknik di kuliah

### Sinkron dengan kuliah
- Tugas Pemrograman Web Dasar (HTML+CSS) dan Laravel di kampus dijadikan latihan tambahan
- Tugas kampus tetap dikerjakan sendiri dulu, baru dibandingkan dengan pemahaman dari roadmap ini

---

## RITUAL MINGGUAN (15 menit, hari Minggu)

1. Centang yang sudah selesai di roadmap ini
2. Tulis di Log Progres: apa yang beres, apa yang macet
3. Tentukan target 3 hal untuk minggu depan
4. Kalau ketinggalan, jangan panik: lihat bagian di bawah

## KALAU KETINGGALAN ATAU KONDISI BERUBAH

- **Ketinggalan 1-2 minggu:** tambah waktu di fase itu, jangan skip materi. Ada buffer di akhir.
- **Ketinggalan lebih dari 1 bulan:** pangkas fitur mini project, bukan pangkas pemahaman dasar.
- **Dapat kerja part-time:** kurangi jam belajar sesuai waktu kosong (minimal 1,5-2 jam/hari), lalu susun ulang jadwal fase.
- **Ada UTS/UAS:** turunkan jam belajar roadmap, tapi pertahankan minimal 30 menit/hari supaya ritme tidak putus.
- **Tugas TA/magang mulai:** roadmap ini berhenti jadi target utama, jadikan pendalaman ringan.

## TEMPLATE UNTUK CHAT BARU

Kalau membuka chat baru, tempel ini di awal:

> Ini roadmap belajar backend gue: [tempel isi ROADMAP.md]
> Posisi gue sekarang: Phase __, Week __.
> Yang sudah beres: __.
> Yang lagi macet: __.
> Tolong bantu gue: __.

---

## LOG PROGRES

| Tanggal | Phase / Week | Yang dikerjakan | Kendala | Catatan |
|---|---|---|---|---|
| | | | | |
| | | | | |
| | | | | |
