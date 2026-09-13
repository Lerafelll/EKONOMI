# Spesifikasi Kebutuhan Perangkat Lunak (SKPL)

# Econiverse
### Sistem Pencatatan dan Simulasi Keuangan Pribadi Berbasis Financial Alternate Universe

---

## 1. Pendahuluan

### 1.1 Tujuan

Dokumen ini bertujuan untuk mendefinisikan kebutuhan perangkat lunak pada aplikasi **Econiverse**, sehingga dapat menjadi acuan bagi tim pengembang dalam proses perancangan, implementasi, pengujian, dan pemeliharaan sistem.

---

### 1.2 Ruang Lingkup

Econiverse merupakan aplikasi berbasis web yang digunakan untuk:

- Mencatat pemasukan dan pengeluaran.
- Mengelola transaksi keuangan.
- Menampilkan kondisi keuangan pengguna.
- Memberikan simulasi alternatif melalui fitur Financial Alternate Universe.
- Membantu pengguna memahami dampak keputusan finansial.

---

### 1.3 Definisi dan Singkatan

| Istilah | Definisi |
|----------|----------|
| User | Pengguna aplikasi |
| Admin | Pengelola sistem |
| Transaksi | Catatan pemasukan atau pengeluaran |
| Financial Alternate Universe | Simulasi kondisi keuangan berdasarkan skenario alternatif |
| Dashboard | Halaman ringkasan kondisi keuangan |

---

## 2. Deskripsi Umum

### 2.1 Perspektif Produk

Econiverse merupakan aplikasi web yang berjalan melalui browser dan terhubung dengan database PostgreSQL untuk menyimpan seluruh data pengguna dan transaksi.

---

### 2.2 Karakteristik Pengguna

#### Mahasiswa

- Memiliki penghasilan atau uang saku terbatas.
- Membutuhkan pengelolaan keuangan yang lebih baik.

#### Freelancer

- Pendapatan tidak tetap.
- Membutuhkan perencanaan finansial.

#### Karyawan

- Memiliki pendapatan rutin.
- Membutuhkan kontrol terhadap pengeluaran.

---

### 2.3 Batasan Sistem

- Sistem berbasis web.
- Memerlukan koneksi internet.
- Data tersimpan pada PostgreSQL.
- Pengguna harus memiliki akun untuk mengakses fitur utama.

---

## 3. Kebutuhan Fungsional

### FR-01 Registrasi Pengguna

#### Deskripsi

Pengguna dapat membuat akun baru.

#### Input

- Nama
- Email
- Password

#### Output

- Akun berhasil dibuat.

---

### FR-02 Login

#### Deskripsi

Pengguna dapat masuk ke sistem.

#### Input

- Email
- Password

#### Output

- Dashboard pengguna.

---

### FR-03 Logout

#### Deskripsi

Pengguna dapat keluar dari sistem.

#### Output

- Pengguna kembali ke halaman login.

---

### FR-04 Menambah Transaksi

#### Deskripsi

Pengguna dapat menambahkan transaksi baru.

#### Input

- Tanggal
- Kategori
- Nominal
- Jenis transaksi
- Deskripsi

#### Output

- Data transaksi tersimpan.

---

### FR-05 Mengubah Transaksi

#### Deskripsi

Pengguna dapat memperbarui data transaksi.

#### Output

- Data transaksi berhasil diperbarui.

---

### FR-06 Menghapus Transaksi

#### Deskripsi

Pengguna dapat menghapus transaksi.

#### Output

- Data transaksi berhasil dihapus.

---

### FR-07 Melihat Riwayat Transaksi

#### Deskripsi

Pengguna dapat melihat seluruh transaksi yang pernah dicatat.

#### Output

- Daftar transaksi.

---

### FR-08 Dashboard Keuangan

#### Deskripsi

Sistem menampilkan ringkasan keuangan pengguna.

#### Output

- Total pemasukan
- Total pengeluaran
- Saldo
- Grafik transaksi

---

### FR-09 Kategori Transaksi

#### Deskripsi

Sistem menyediakan kategori transaksi.

#### Kategori

- Makanan
- Transportasi
- Pendidikan
- Hiburan
- Belanja
- Kesehatan
- Lainnya

---

### FR-10 Financial Alternate Universe

#### Deskripsi

Sistem menghasilkan simulasi kondisi keuangan alternatif berdasarkan transaksi pengguna.

#### Contoh

Input:

```text
Kopi Harian Rp25.000
```

Skenario:

```text
Tidak membeli kopi selama 6 bulan
```

Output:

```text
Potensi tabungan Rp4.500.000
```

---

### FR-11 Simulasi Penghematan

#### Deskripsi

Sistem menghitung potensi penghematan dari pengurangan suatu kategori pengeluaran.

#### Input

- Kategori
- Persentase pengurangan

#### Output

- Potensi penghematan bulanan
- Potensi penghematan tahunan

---

### FR-12 Grafik Keuangan

#### Deskripsi

Sistem menampilkan visualisasi data transaksi.

#### Output

- Grafik pemasukan
- Grafik pengeluaran
- Grafik kategori transaksi

---

## 4. Kebutuhan Non Fungsional

### NFR-01 Kinerja

- Waktu respon maksimal 3 detik.
- Sistem mampu menangani minimal 100 pengguna aktif.

---

### NFR-02 Keamanan

- Password disimpan dalam bentuk hash.
- Hanya pengguna yang terautentikasi dapat mengakses data pribadi.

---

### NFR-03 Usability

- Tampilan mudah digunakan.
- Responsif pada desktop dan perangkat mobile.

---

### NFR-04 Reliability

- Data transaksi tersimpan secara konsisten.
- Sistem mampu melakukan validasi input.

---

### NFR-05 Maintainability

- Kode menggunakan struktur modular.
- Mudah dikembangkan untuk fitur baru.

---

## 5. Use Case

### User

- Register
- Login
- Logout
- Menambah transaksi
- Mengubah transaksi
- Menghapus transaksi
- Melihat dashboard
- Melihat grafik
- Menggunakan Financial Alternate Universe

---

## 6. Kebutuhan Perangkat Lunak

### Frontend

- Next.js
- TypeScript
- Tailwind CSS

### Backend

- Next.js API Routes

### Database

- PostgreSQL

### Version Control

- Git
- GitHub

---

## 7. Kriteria Keberhasilan

Sistem dianggap berhasil apabila:

- Pengguna dapat melakukan autentikasi.
- Pengguna dapat melakukan CRUD transaksi.
- Dashboard menampilkan data secara akurat.
- Financial Alternate Universe menghasilkan simulasi yang sesuai.
- Grafik transaksi dapat ditampilkan dengan benar.

---

## 8. Pengembangan Selanjutnya

Fitur yang dapat ditambahkan pada versi berikutnya:

- Financial Health Score
- AI Financial Advisor
- Target Tabungan
- Export PDF
- Notifikasi Pengingat Keuangan
- Mobile Application

---

## Status Dokumen

Versi: 1.0

Status: Draft

Tanggal: 2026
