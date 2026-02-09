# Network Connection Troubleshooting Guide

## Overview
Panduan ini membantu pengguna mengatasi masalah komputer Windows yang tidak terhubung ke jaringan atau internet.

---

## Gejala
Beberapa indikasi masalah koneksi jaringan:

- Muncul status **No Internet**
- Ikon jaringan menunjukkan tanda peringatan
- Tidak bisa membuka website
- Tidak bisa mengakses aplikasi berbasis internet
- Windows Update gagal

---

## Kemungkinan Penyebab
- Kabel LAN tidak terhubung dengan baik
- Router atau modem mati
- Gangguan jaringan dari ISP
- Network adapter bermasalah
- Konfigurasi IP tidak valid

---

## Troubleshooting Steps

### 1. Periksa Koneksi Fisik
- Pastikan kabel LAN terhubung dengan benar
- Periksa lampu indikator LAN pada komputer atau router
- Restart modem atau router

---

### 2. Restart Network Adapter
1. Buka **Control Panel**
2. Pilih **Network and Internet**
3. Klik **Network Connections**
4. Klik kanan adapter jaringan
5. Pilih **Disable**, lalu **Enable**

---

### 3. Reset IP Configuration
1. Buka **Command Prompt** sebagai Administrator
2. Jalankan perintah berikut:
                ipconfig /release
                ipconfig /renew
                ipconfig /flushdns

---

### 4. Jalankan Network Troubleshooter
1. Buka **Settings**
2. Pilih **Network & Internet**
3. Klik **Network Troubleshooter**

---

## Hubungi IT Support Jika
- Komputer tetap tidak terhubung ke jaringan
- Network adapter tidak terdeteksi
- Lampu indikator LAN tidak menyala
- Masalah terjadi pada banyak perangkat
