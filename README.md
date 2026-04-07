# KaysanBook - Toko Buku Online

Selamat datang di KaysanBook, platform toko buku online yang interaktif dengan fitur login, registrasi, dan berbagai metode pembayaran digital.

## 📁 File-File Project

- **index.html** - Halaman utama (Homepage)
- **styles.css** - File styling dan CSS untuk tampilan menarik
- **script.js** - JavaScript untuk fungsionalitas interaktif

## ✨ Fitur Utama

### 1. **Homepage/Beranda**
   - Tampilan menarik dengan gradasi warna coklat KaysanBook
   - Logo KaysanBook yang profesional
   - Koleksi buku pilihan dengan 6 judul buku
   - Section fitur unggulan
   - Informasi kontak
   - **About Us Section** - Profil lengkap KaysanBook

### 1.1 **About Us / Tentang Kami** ⭐ NEW!
   - Deskripsi lengkap tentang KaysanBook
   - Visi dan Misi perusahaan
   - Pencapaian dan statistik (5000+ buku, 50000+ pelanggan, 100000+ pesanan, 99% rating)
   - Display kartu statistik yang menarik
   - Design responsif untuk semua device

### 2. **Sistem Autentikasi**
   - **Login Modal** - Untuk pengguna existing
   - **Register Modal** - Untuk membuat akun baru
   - Opsi login sebagai Admin
   - Validasi form yang lengkap
   - Data tersimpan di localStorage

### 3. **Katalog Buku** ⭐ UPDATED!
   - **16 buku pilihan** dengan berbagai genre
   - Dari penulis lokal dan internasional
   - Judul dan author yang jelas
   - Harga yang terjangkau (mulai dari Rp 63.000 - Rp 145.000)
   - Tombol "Tambah Keranjang" yang interaktif
   - Grid responsive design
   - Genre: Fiksi, Misteri, Adventure, Self-Help, Sejarah, Fantasy, dll

### 4. **Keranjang Belanja**
   - Tambah buku ke keranjang (qty dapat bertambah)
   - Lihat ringkasan pesanan
   - Hitung total harga otomatis

### 5. **Metode Pembayaran** ✅
   - **Dana** 💰
   - **ShopeePay** 📱
   - **GoPay** 📱
   - **Transfer Bank** 🏦
   - **Kartu Kredit** 💳

### 6. **Sistem Notifikasi Pembayaran** ⭐ NEW!
   - **Real-time Notifications** - Notifikasi popup yang muncul di pojok kanan atas
   - **Berbagai Tipe Notifikasi:**
     - ✅ Success (Hijau) - Untuk transaksi berhasil
     - ⚠️ Warning (Kuning) - Untuk peringatan
     - ❌ Error (Merah) - Untuk kesalahan
     - ⏳ Pending (Orange) - Untuk proses pending
     - ℹ️ Info (Biru) - Untuk informasi umum
   - **Auto-dismiss** - Notifikasi otomatis hilang setelah beberapa detik
   - **Dapat ditutup manual** - Klik tombol × untuk menutup notifikasi
   - **Animasi Smooth** - Slide-in dan slide-out animations
   - **Responsive Design** - Bekerja sempurna di semua ukuran layar

### 8. **Sistem Diskon & Kode Promo** ⭐ NEW!
   - **Diskon Buku** - Semua buku mendapatkan diskon dengan badge merah
   - **Kode Promo** - Sistem kode promo yang dapat diterapkan saat checkout
   - **Kode Promo Tersedia:**
     - `DISKON10` - Diskon 10% untuk semua pembelian
     - `HEMAT20` - Diskon 20% maksimal Rp 50.000
     - `BUKU50K` - Diskon Rp 50.000 (min. pembelian Rp 200.000)
     - `WELCOME` - Diskon Rp 25.000 untuk pelanggan baru
     - `KAYSANBOOK2026` - Diskon 15% untuk ulang tahun KaysanBook 2026
     - `STUDENT` - Diskon 25% maksimal Rp 75.000 untuk mahasiswa
     - `FLASH50` - Diskon 50% maksimal Rp 100.000 (flash sale)
   - **Section Kode Promo** - Halaman khusus menampilkan semua kode promo tersedia
   - **Validasi Real-time** - Kode promo divalidasi saat checkout
   - **Hitung Total Otomatis** - Subtotal, diskon, dan total dihitung real-time

### 9. **Status Pesanan** ⭐ NEW!
   - **Modal Status Pesanan** - Lihat semua pesanan Anda
   - **Tracking Real-time** - Pantau status pesanan dari pending ke selesai
   - **Detail Lengkap** - Lihat item, jumlah, harga, dan total per pesanan
   - **History Order** - Riwayat lengkap semua transaksi

## 🔑 Akun Demo

Untuk testing, gunakan akun berikut:

**Akun Admin:**
- Email: `admin@kaysanbook.com`
- Password: `admin123`
- Akses: Admin

**Akun User:**
- Email: `user@example.com`
- Password: `user123`
- Akses: User Biasa

## 📚 Daftar Buku Tersedia

**Total: 16 Buku** (semua buku mendapat diskon)

| No. | Judul | Penulis | Harga Asli | Harga Diskon | Diskon | Genre |
|-----|-------|---------|------------|--------------|--------|-------|
| 1 | Laskar Pelangi | Andrea Hirata | Rp 89.000 | Rp 71.200 | 20% | Fiksi |
| 2 | Rantau 1 Muara | Fujifilm Liput | Rp 95.000 | Rp 80.750 | 15% | Fiksi |
| 3 | Ayat-Ayat Cinta | Habiburrahman El Shirazy | Rp 86.000 | - | - | Romantis |
| 4 | Conan Doyle | Arthur Conan Doyle | Rp 75.000 | - | - | Misteri |
| 5 | Harry Potter | J.K. Rowling | Rp 120.000 | Rp 90.000 | 25% | Fantasy |
| 6 | Remaja Nusantara | Anggriawan Sukarno | Rp 63.000 | Rp 56.700 | 10% | Fiksi |
| 7 | Filosofi Teras | Henry Manampiring | Rp 98.000 | Rp 83.300 | 15% | Self-Help |
| 8 | Sapiens | Yuval Noah Harari | Rp 145.000 | Rp 116.000 | 20% | Sejarah/Sains |
| 9 | Atomic Habits | James Clear | Rp 130.000 | Rp 97.500 | 25% | Self-Help |
| 10 | The Midnight Library | Matt Haig | Rp 110.000 | - | - | Fiksi |
| 11 | Wings of Fire | Tui T. Sutherland | Rp 105.000 | - | - | Adventure |
| 12 | Tentang Kamu | Tere Liye | Rp 92.000 | - | - | Romantis |
| 13 | Perahu Kertas | Dee Lestari | Rp 88.000 | - | - | Romantis |
| 14 | Dune | Frank Herbert | Rp 135.000 | - | - | Sci-Fi |
| 15 | Becoming | Michelle Obama | Rp 125.000 | - | - | Biografi |

## 🎫 Kode Promo Tersedia

**Total: 7 Kode Promo**

| Kode Promo | Deskripsi | Tipe | Nilai | Syarat |
|------------|-----------|------|-------|--------|
| `DISKON10` | Diskon 10% untuk semua pembelian | Persentase | 10% | - |
| `HEMAT20` | Diskon 20% maksimal Rp 50.000 | Persentase | 20% | Max Rp 50.000 |
| `BUKU50K` | Diskon Rp 50.000 | Tetap | Rp 50.000 | Min. pembelian Rp 200.000 |
| `WELCOME` | Diskon Rp 25.000 untuk pelanggan baru | Tetap | Rp 25.000 | - |
| `KAYSANBOOK2026` | Diskon 15% untuk ulang tahun KaysanBook 2026 | Persentase | 15% | - |
| `STUDENT` | Diskon 25% maksimal Rp 75.000 untuk mahasiswa | Persentase | 25% | Max Rp 75.000 |
| `FLASH50` | Diskon 50% maksimal Rp 100.000 (flash sale) | Persentase | 50% | Max Rp 100.000 |

### Cara Menggunakan Kode Promo:
1. Tambahkan buku ke keranjang
2. Klik "Keranjang" untuk checkout
3. Masukkan kode promo di field "Kode Promo"
4. Klik "Terapkan"
5. Lihat diskon otomatis diterapkan ke total

## 🚀 Cara Menggunakan

### Navigasi Website

Gunakan menu navigasi di header untuk mengakses berbagai section:
- **Beranda** - Halaman utama dengan hero section
- **Koleksi** - Daftar buku yang tersedia
- **Tentang Kami** - Profil dan informasi KaysanBook ⭐ NEW!
- **Kontak** - Informasi kontak dan hubungi kami

### Langkah-Langkah Berbelanja

1. **Buka File HTML**
   - Buka `index.html` di browser Anda

2. **Jelajahi Tentang KaysanBook (Opsional)**
   - Klik "Tentang Kami" di menu navigasi
   - Baca tentang visi, misi, dan pencapaian kami
   - Lihat statistik dan achievement cards

3. **Registrasi Akun (Opsional)**
   - Klik tombol "Daftar"
   - Isi formulir lengkap
   - Pilih apakah ingin sebagai Admin atau User biasa
   - Klik tombol Daftar
   - Lihat notifikasi sukses yang muncul!

3. **Login**
   - Klik tombol "Login"
   - Masukkan email dan password
   - Cek kotak "Login sebagai Admin" jika admin
   - Klik Login
   - Notifikasi akan menampilkan pesan sukses atau error

4. **Belanja**
   - Klik "Jelajahi Koleksi" atau scroll ke bawah
   - Pilih buku yang ingin dibeli
   - Klik "Tambah Keranjang"
   - Lihat notifikasi buku ditambahkan!
   - Lihat keranjang di header setelah login

5. **Checkout & Pembayaran**
   - Klik tombol "Keranjang" di header
   - **Opsional: Masukkan Kode Promo** - Gunakan kode promo untuk diskon tambahan
   - Pilih metode pembayaran
   - Klik "Proses Pembayaran"
   - Dua notifikasi akan ditampilkan:
     1. Notifikasi "Pembayaran Diproses" (orange - pending)
     2. Notifikasi "Pembayaran Berhasil!" (hijau - success)
   - Transaksi selesai! Anda akan menerima notifikasi nomor order

6. **Lihat Status Pesanan**
   - Klik tombol "Menunggu Pesanan" di header
   - Lihat semua pesanan Anda dengan detail lengkap
   - Pantau status dari pending ke selesai

## 📊 Sistem Notifikasi

### Tipe-Tipe Notifikasi:

| Tipe | Warna | Icon | Kegunaan |
|------|-------|------|----------|
| Success | Hijau | ✓ | Aksi berhasil (login, reg, pembayaran) |
| Error | Merah | ✗ | Ada kesalahan (gagal login, email duplikat) |
| Warning | Kuning | ⚠ | Peringatan (validasi form, input kosong) |
| Pending | Orange | ⏳ | Proses sedang berjalan (pembayaran) |
| Info | Biru | ℹ | Informasi umum (keranjang kosong, logout) |

### Fitur Notifikasi:

- **Posisi Fixed** - Tetap terlihat saat scroll
- **Auto-dismiss** - Hilang otomatis (bisa dikustomisasi)
- **Non-blocking** - Tidak mengganggu interaksi halaman
- **Stackable** - Bisa menampilkan beberapa notifikasi sekaligus
- **Close Button** - Tombol × untuk menutup manual
- **Smooth Animation** - Efek slide-in dan slide-out

## 📊 Data Storage

Website ini menggunakan **localStorage** browser untuk menyimpan:
- Daftar pengguna dan password
- Keranjang belanja
- User yang sedang login
- Riwayat order/transaksi

Data tersimpan lokal di browser Anda dan tidak dikirim ke server.

## 🎨 Design Features

- **Warna Tema**: Coklat (KaysanBook) dengan aksen emas
- **Typography**: Modern dan clean
- **Responsif**: Bekerja dengan baik di desktop, tablet, dan mobile
- **Icons**: Menggunakan Font Awesome
- **Animasi**: Smooth transitions dan hover effects

## 🔐 Catatan Keamanan

**PERHATIAN**: Ini adalah project demo/pembelajaran. Untuk production:
1. Jangan simpan password dalam plain text
2. Gunakan backend server untuk autentikasi
3. Implementasikan HTTPS
4. Gunakan enkripsi data sensitive
5. Implement proper backend validation

## 📱 Responsive Design

- ✅ Desktop (1200px+)
- ✅ Tablet (768px - 1199px)
- ✅ Mobile (< 768px)

## 🎯 Fitur Bonus

- Admin detection saat login
- Order history tracking
- Cart persistence
- User session management
- Demo data pre-loaded
- **Real-time Toast Notifications** ⭐
- **Payment Status Display**
- **Error Handling dengan Notifikasi**
- **Multi-device Support dengan responsive notifications**

## 📝 Pengembangan Lebih Lanjut

Anda dapat menambahkan:
- Backend server (Node.js, Python, PHP, etc)
- Database (MySQL, MongoDB, etc)
- Payment Gateway Integration (Midtrans, Stripe, etc)
- Email notification system
- Admin dashboard
- Product reviews & ratings
- Search & filter functionality
- User profile management
- Wishlist feature
- **Sound notifications** untuk pembayaran
- **Notification history/log**
- **User preference untuk notification settings**
- **Desktop push notifications**
- **Email notifications**

## 🤝 Support

Untuk pertanyaan atau saran, hubungi:
- Email: nawfalzainkaysan@gmail.com
- Telepon: +62 889 7699 8414
- Lokasi: Jl. Nanas No. 9, Jakarta, Indonesia

---

**KaysanBook © 2024** - Toko Buku Online Terpercaya
