# Spesifikasi Kebutuhan Perangkat Lunak (SKPL)

# Econiverse
### Platform Analisis Perilaku Ekonomi Berbasis AI

---

# 1. Pendahuluan

## 1.1 Tujuan

Dokumen ini menjelaskan kebutuhan perangkat lunak yang diperlukan dalam pengembangan aplikasi Econiverse.

Dokumen ini digunakan sebagai pedoman bagi tim pengembang dalam proses analisis, perancangan, implementasi, pengujian, dan pemeliharaan sistem.

---

## 1.2 Ruang Lingkup

Econiverse merupakan platform berbasis web yang membantu pengguna memahami perilaku ekonomi mereka melalui survei, analisis data, AI Financial Coach, serta sistem gamifikasi yang bertujuan meningkatkan kebiasaan finansial yang positif.

Sistem menyediakan fitur:

- Economic Personality Test
- AI Financial Coach
- Daily Mission
- Streak System
- Achievement System
- Personality Evolution
- Dashboard Analisis

---

## 1.3 Definisi Istilah

| Istilah | Definisi |
|----------|----------|
| User | Pengguna aplikasi |
| Personality Test | Survei untuk menentukan tipe perilaku ekonomi pengguna |
| AI Financial Coach | Agen AI yang memberikan analisis dan rekomendasi |
| Streak | Catatan konsistensi aktivitas pengguna |
| Achievement | Penghargaan yang diperoleh pengguna |
| Dashboard | Halaman utama yang menampilkan ringkasan aktivitas pengguna |

---

# 2. Deskripsi Umum

## 2.1 Perspektif Produk

Econiverse merupakan aplikasi web yang dapat diakses melalui browser dan menggunakan PostgreSQL sebagai database utama.

Sistem dirancang untuk membantu pengguna mengenali kebiasaan ekonomi serta meningkatkan kualitas pengambilan keputusan ekonomi melalui pendekatan behavioral economics.

---

## 2.2 Karakteristik Pengguna

### Mahasiswa

- Memiliki pendapatan terbatas.
- Sedang belajar mengelola keuangan.

### Freelancer

- Pendapatan tidak tetap.
- Membutuhkan pengelolaan keuangan yang lebih baik.

### Karyawan

- Ingin meningkatkan kualitas kebiasaan finansial.

---

## 2.3 Batasan Sistem

- Sistem hanya dapat diakses melalui internet.
- Pengguna wajib memiliki akun.
- Analisis AI berdasarkan data yang dimasukkan pengguna.
- Sistem tidak digunakan untuk transaksi keuangan nyata.

---

# 3. Kebutuhan Fungsional

## FR-01 Registrasi Pengguna

### Deskripsi

Pengguna dapat membuat akun baru.

### Input

- Nama
- Email
- Password

### Output

- Akun berhasil dibuat.

---

## FR-02 Login

### Deskripsi

Pengguna dapat masuk ke sistem.

### Input

- Email
- Password

### Output

- Dashboard pengguna.

---

## FR-03 Logout

### Deskripsi

Pengguna dapat keluar dari sistem.

### Output

- Kembali ke halaman login.

---

## FR-04 Economic Personality Test

### Deskripsi

Pengguna dapat mengisi survei untuk menentukan tipe perilaku ekonomi.

### Input

- Jawaban survei

### Output

- Hasil personality ekonomi

### Personality Type

- The Saver
- The Investor
- The Rational Planner
- The Impulsive Buyer
- The Experience Seeker
- The Risk Taker

---

## FR-05 Menampilkan Hasil Personality

### Deskripsi

Sistem menampilkan tipe personality pengguna.

### Output

- Nama personality
- Karakteristik
- Kelebihan
- Kekurangan

---

## FR-06 AI Financial Coach

### Deskripsi

Sistem menganalisis data pengguna dan memberikan rekomendasi.

### Output

- Analisis perilaku
- Kelebihan pengguna
- Kekurangan pengguna
- Saran pengembangan kebiasaan

---

## FR-07 Dashboard

### Deskripsi

Menampilkan informasi utama pengguna.

### Output

- Personality Type
- AI Insight
- Progress Streak
- Achievement
- Daily Mission

---

## FR-08 Daily Mission

### Deskripsi

Sistem memberikan tugas harian kepada pengguna.

### Contoh

- Menabung hari ini
- Tidak melakukan pembelian impulsif
- Menyelesaikan refleksi harian

### Output

- Progress misi

---

## FR-09 Streak System

### Deskripsi

Mencatat konsistensi aktivitas pengguna.

### Output

- Jumlah streak
- Riwayat streak

---

## FR-10 Achievement System

### Deskripsi

Sistem memberikan penghargaan atas pencapaian pengguna.

### Output

- Badge
- Achievement

### Contoh Badge

- First Saving
- Smart Saver
- Financial Explorer
- Financial Master

---

## FR-11 Personality Evolution

### Deskripsi

Menampilkan perubahan personality pengguna dari waktu ke waktu.

### Output

- Riwayat personality
- Grafik perkembangan personality

---

## FR-12 Profil Pengguna

### Deskripsi

Pengguna dapat melihat dan mengubah informasi akun.

### Output

- Data profil
- Pengaturan akun

---

# 4. Kebutuhan Non-Fungsional

## NFR-01 Performance

- Waktu respon maksimal 3 detik.
- Sistem mampu menangani minimal 100 pengguna aktif secara bersamaan.

---

## NFR-02 Security

- Password disimpan menggunakan hashing.
- Data pengguna hanya dapat diakses oleh pemilik akun.
- Sistem menggunakan autentikasi yang aman.

---

## NFR-03 Reliability

- Sistem tersedia minimal 95% dari waktu operasional.
- Data pengguna tersimpan secara konsisten.

---

## NFR-04 Usability

- Antarmuka mudah digunakan.
- Navigasi sederhana.
- Responsif pada desktop dan mobile.

---

## NFR-05 Maintainability

- Struktur kode modular.
- Mudah dikembangkan pada versi berikutnya.

---

# 5. Use Case

## Pengguna

### Authentication

- Register
- Login
- Logout

### Personality System

- Mengisi Personality Test
- Melihat Hasil Personality

### AI System

- Melihat AI Insight
- Menerima Rekomendasi

### Gamification

- Menyelesaikan Daily Mission
- Mengumpulkan Achievement
- Menjaga Streak

### Monitoring

- Melihat Dashboard
- Melihat Personality Evolution

---

# 6. Kebutuhan Perangkat Lunak

## Frontend

- Next.js
- TypeScript
- Tailwind CSS

## Backend

- Next.js API Routes

## Database

- PostgreSQL

## Authentication

- NextAuth

## AI Service

- OpenAI API

## Version Control

- Git
- GitHub

---

# 7. Kriteria Keberhasilan

Sistem dianggap berhasil apabila:

- Pengguna dapat menyelesaikan personality test.
- Personality berhasil ditentukan oleh sistem.
- AI Insight dapat ditampilkan.
- Daily Mission berjalan dengan baik.
- Streak tercatat dengan benar.
- Achievement dapat diperoleh pengguna.
- Dashboard menampilkan seluruh data secara akurat.

---

# 8. Pengembangan Selanjutnya

## Future Features

- AI Chat Coach
- Community Challenge
- Economic Leaderboard
- Habit Prediction
- Social Sharing
- Personal Financial Roadmap

---

# Status Dokumen

Versi : 1.0

Status : Draft

Tahun : 2026
