# Slow Computer Troubleshooting Guide

## Overview
Panduan ini berisi langkah-langkah troubleshooting untuk mengatasi komputer Windows yang berjalan lambat. Masalah performa biasanya berkaitan dengan penggunaan resource sistem, aplikasi startup, atau file sementara yang menumpuk.

---

## Gejala
Beberapa tanda komputer mengalami penurunan performa:

- Sistem membutuhkan waktu lama untuk booting
- Aplikasi terbuka dengan lambat
- Komputer sering freeze
- CPU atau RAM usage tinggi
- Penyimpanan hampir penuh

---

## Kemungkinan Penyebab
- Terlalu banyak aplikasi startup
- File temporary menumpuk
- Penyimpanan hampir penuh
- Penggunaan RAM tinggi
- Sistem belum di-restart dalam waktu lama

---

## Troubleshooting Steps

### 1. Restart Komputer
Restart membantu membersihkan memory sementara dan menghentikan proses yang tidak diperlukan.

Langkah:
- Klik **Start → Power → Restart**

---

### 2. Nonaktifkan Aplikasi Startup
Mengurangi aplikasi startup dapat mempercepat proses booting dan meningkatkan performa sistem.

Langkah:
1. Tekan `Ctrl + Shift + Esc` untuk membuka **Task Manager**
2. Pilih tab **Startup**
3. Klik aplikasi yang tidak diperlukan
4. Klik **Disable**

---

### 3. Hapus File Temporary
Membersihkan file sementara dapat mengosongkan ruang penyimpanan dan meningkatkan performa.

#### Menggunakan Disk Cleanup
1. Buka **Start Menu**
2. Ketik **Disk Cleanup**
3. Pilih drive sistem (biasanya `C:`)
4. Pilih file yang ingin dihapus
5. Klik **OK**

#### Menghapus Folder Temp Secara Manual
1. Tekan `Windows + R`
2. Ketik `%temp%`
3. Hapus file di dalam folder
4. Ulangi dengan mengetik:
   - `temp`
   - `prefetch`

---

### 4. Periksa Kapasitas Penyimpanan
Pastikan drive sistem memiliki ruang kosong minimal 20%.

Langkah:
1. Buka **File Explorer**
2. Klik **This PC**
3. Periksa kapasitas drive `C:`

---

## Hubungi IT Support Jika
- Komputer tetap lambat setelah troubleshooting
- Penggunaan CPU atau RAM tetap tinggi
- Terdapat indikasi kerusakan hardware

