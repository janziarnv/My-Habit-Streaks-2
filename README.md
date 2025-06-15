# My-Habit-Streaks-2

## 1. Deskripsi Aplikasi
"My Habit Streaks" adalah aplikasi mobile yang dirancang untuk membantu pengguna membangun dan mempertahankan kebiasaan positif. Aplikasi ini memungkinkan pengguna untuk:
- Menambahkan kebiasaan baru yang ingin mereka kembangkan
- Melacak kemajuan harian dari setiap kebiasaan
- Melihat statistik streak (rentang waktu berkelanjutan) untuk setiap kebiasaan
- Memvisualisasikan kemajuan melalui kalender interaktif

## 2. Fitur Utama

### 2.1 Manajemen Kebiasaan
- *Penambahan Kebiasaan Baru*
  - Nama kebiasaan
  - Deskripsi (opsional)
  - Pemilihan warna kustom
  - Timestamp pembuatan

- *Tampilan Daftar Kebiasaan*
  - Kartu kebiasaan dengan informasi utama
  - Indikator streak saat ini
  - Navigasi cepat ke detail kebiasaan

### 2.2 Pelacakan Kemajuan
- *Kalender Interaktif*
  - Tampilan bulanan
  - Penanda hari yang berhasil
  - Toggle status penyelesaian per hari

- *Statistik Streak*
  - Streak saat ini (rentang waktu berkelanjutan)
  - Streak terpanjang (pencapaian tertinggi)
  - Visualisasi kemajuan

### 2.3 Penyimpanan Data
- *Database Lokal*
  - Menggunakan SQLite untuk penyimpanan
  - Mendukung platform web dan mobile
  - Data persisten antar sesi

## 3. Teknologi yang Digunakan

### 3.1 Frontend
- *Flutter Framework*
  - UI yang responsif
  - Material Design
  - Widget kustom

### 3.2 Backend
- *State Management*
  - Provider pattern
  - Manajemen state terpusat

- *Database*
  - SQLite (sqflite)
  - SQLite FFI untuk dukungan web
  - Operasi CRUD lengkap

### 3.3 Komponen UI
- *Table Calendar*
  - Kalender interaktif
  - Penanda hari
  - Navigasi bulan

- *Custom Widgets*
  - Kartu statistik
  - Form input
  - Dialog konfirmasi

## 4. Arsitektur Aplikasi

### 4.1 Struktur Folder

lib/
├── models/
│   ├── habit.dart
│   └── habit_progress.dart
├── providers/
│   └── habit_provider.dart
├── screens/
│   ├── home_screen.dart
│   ├── add_habit_screen.dart
│   └── habit_detail_screen.dart
├── services/
│   └── database_service.dart
└── main.dart


### 4.2 Alur Data
1. *Input Pengguna*
   - Form penambahan kebiasaan
   - Toggle status harian
   - Interaksi kalender

2. *Pemrosesan*
   - Validasi input
   - Konversi data
   - Operasi database

3. *Penyimpanan*
   - Tabel habits
   - Tabel habit_progress
   - Relasi one-to-many

## 5. Keunggulan Aplikasi

### 5.1 User Experience
- Interface yang intuitif
- Navigasi yang mudah
- Feedback visual yang jelas

### 5.2 Performa
- Penyimpanan lokal yang cepat
- State management yang efisien
- Optimasi database

### 5.3 Fleksibilitas
- Dukungan multi-platform
- Skalabilitas data
- Kemudahan maintenance

## 6. Pengembangan Selanjutnya

### 6.1 Fitur yang Direncanakan
- Notifikasi pengingat
- Statistik lebih detail
- Ekspor data
- Tema gelap/terang

### 6.2 Peningkatan
- Optimasi performa
- Penambahan animasi
- Peningkatan UI/UX

## 7. Kesimpulan
"My Habit Streaks" adalah aplikasi yang dirancang dengan fokus pada kemudahan penggunaan dan efektivitas dalam membantu pengguna membangun kebiasaan positif. Dengan kombinasi fitur yang intuitif dan teknologi yang handal, aplikasi ini siap membantu pengguna mencapai tujuan mereka dalam membangun kebiasaan yang lebih baik.
