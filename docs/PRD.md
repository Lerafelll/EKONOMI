# Product Requirements Document (PRD)

# Money DNA
### Sistem Pencatatan dan Simulasi Keuangan Pribadi Berbasis Financial Alternate Universe

---

## 1. Informasi Produk

| Item | Detail |
|--------|--------|
| Nama Produk | Money DNA |
| Versi | 1.0 |
| Platform | Web |
| Frontend | Next.js |
| Backend | Next.js API Routes |
| Database | PostgreSQL |
| Target Pengguna | Mahasiswa, Freelancer, Karyawan |

---

# 2. Latar Belakang

Sebagian besar aplikasi pencatatan keuangan hanya berfungsi sebagai alat untuk mencatat pemasukan dan pengeluaran. Pengguna dapat melihat kondisi keuangan saat ini, namun belum dapat memahami dampak dari keputusan finansial yang mereka ambil.

Money DNA hadir sebagai solusi yang tidak hanya mencatat transaksi, tetapi juga membantu pengguna menganalisis berbagai kemungkinan kondisi keuangan melalui fitur utama **Financial Alternate Universe**.

Fitur ini memungkinkan pengguna melihat simulasi dari keputusan finansial yang berbeda sehingga dapat membantu dalam pengambilan keputusan ekonomi yang lebih baik.

---

# 3. Visi Produk

Menjadi platform pencatatan keuangan yang mampu membantu pengguna memahami dampak jangka pendek dan jangka panjang dari setiap keputusan finansial yang mereka ambil.

---

# 4. Tujuan Produk

- Membantu pengguna mengelola keuangan pribadi.
- Menyediakan pencatatan pemasukan dan pengeluaran.
- Menampilkan kondisi keuangan secara visual.
- Memberikan simulasi alternatif terhadap keputusan finansial pengguna.
- Membantu pengguna mengambil keputusan ekonomi yang lebih rasional.

---

# 5. Target Pengguna

## Mahasiswa

Karakteristik:

- Memiliki uang bulanan terbatas.
- Membutuhkan kontrol pengeluaran.
- Ingin mengetahui dampak dari kebiasaan konsumtif.

---

## Freelancer

Karakteristik:

- Pendapatan tidak tetap.
- Membutuhkan perencanaan keuangan.

---

## Karyawan

Karakteristik:

- Memiliki pemasukan rutin.
- Ingin mengelola pengeluaran dan tabungan.

---

# 6. Problem Statement

Pengguna sering mengalami kesulitan dalam:

- Mengetahui pola pengeluaran.
- Mengontrol kebiasaan konsumtif.
- Melihat dampak dari keputusan finansial.
- Membuat perencanaan keuangan jangka panjang.

---

# 7. Solusi

Money DNA menyediakan:

- Dashboard keuangan.
- Pencatatan transaksi.
- Analisis pemasukan dan pengeluaran.
- Simulasi Financial Alternate Universe.

---

# 8. Fitur Utama

## 8.1 Autentikasi

### Deskripsi

Pengguna dapat membuat akun dan masuk ke sistem.

### Fitur

- Register
- Login
- Logout

---

## 8.2 Dashboard

### Deskripsi

Menampilkan ringkasan kondisi keuangan pengguna.

### Informasi yang Ditampilkan

- Total pemasukan
- Total pengeluaran
- Saldo saat ini
- Grafik transaksi
- Ringkasan aktivitas

---

## 8.3 Manajemen Transaksi

### Deskripsi

Pengguna dapat mengelola transaksi keuangan.

### Fitur

- Tambah transaksi
- Edit transaksi
- Hapus transaksi
- Lihat riwayat transaksi

---

## 8.4 Kategori Transaksi

### Kategori Default

- Makanan
- Transportasi
- Pendidikan
- Hiburan
- Belanja
- Kesehatan
- Lainnya

---

# 9. Financial Alternate Universe

## Deskripsi

Fitur utama yang membedakan Money DNA dari aplikasi pencatatan keuangan lainnya.

Sistem akan membuat simulasi berdasarkan data transaksi pengguna dan menampilkan kemungkinan kondisi keuangan apabila pengguna mengambil keputusan yang berbeda.

---

## Contoh Skenario 1

### Data Aktual

```text
Kopi Harian
Rp25.000/hari
```

### Simulasi

```text
Jika tidak membeli kopi selama 6 bulan
```

### Hasil

```text
Potensi tabungan:
Rp4.500.000
```

---

## Contoh Skenario 2

### Data Aktual

```text
Belanja Online
Rp500.000/bulan
```

### Simulasi

```text
Jika pengeluaran dikurangi 50%
```

### Hasil

```text
Potensi penghematan:
Rp3.000.000/tahun
```

---

## Contoh Skenario 3

### Data Aktual

```text
Tabungan
Rp0
```

### Simulasi

```text
Menabung Rp10.000/hari
```

### Hasil

```text
1 Tahun:
Rp3.650.000
```

---

# 10. User Story

## US-01

Sebagai pengguna, saya ingin membuat akun agar dapat menggunakan sistem.

---

## US-02

Sebagai pengguna, saya ingin mencatat pemasukan agar kondisi keuangan saya terdokumentasi.

---

## US-03

Sebagai pengguna, saya ingin mencatat pengeluaran agar dapat mengetahui ke mana uang saya digunakan.

---

## US-04

Sebagai pengguna, saya ingin melihat dashboard agar dapat memahami kondisi keuangan saya secara cepat.

---

## US-05

Sebagai pengguna, saya ingin membuat simulasi Financial Alternate Universe agar dapat memahami dampak keputusan finansial yang berbeda.

---

# 11. MVP (Minimum Viable Product)

Fitur yang wajib selesai pada versi pertama.

- Register
- Login
- Logout
- Dashboard
- CRUD Transaksi
- Kategori Transaksi
- Grafik Keuangan
- Financial Alternate Universe

---

# 12. Kriteria Keberhasilan

Produk dianggap berhasil apabila:

- Pengguna dapat mencatat transaksi dengan mudah.
- Dashboard dapat menampilkan kondisi keuangan secara akurat.
- Simulasi Financial Alternate Universe berjalan sesuai perhitungan.
- Sistem dapat digunakan tanpa error pada browser modern.

---

# 13. Future Development

Fitur yang dapat ditambahkan pada versi berikutnya:

- AI Financial Advisor
- Target Tabungan
- Analisis Kebiasaan Pengeluaran
- Export PDF
- Multi Currency
- Notifikasi Pengingat Keuangan

---

# 14. Tim Pengembang

| Role | Tanggung Jawab |
|--------|--------|
| Product Master | Requirement, Timeline, Monitoring, Pengujian Sistem |
| Frontend Developer | UI/UX dan Implementasi Next.js |
| Backend Developer | API, Business Logic, PostgreSQL |

---

# Status Dokumen

Draft Version 1.0
