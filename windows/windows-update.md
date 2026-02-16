# Windows Update Failed

## Overview
Windows Update yang gagal dapat menyebabkan sistem tidak mendapatkan patch keamanan dan update fitur. Panduan ini membantu mengatasi masalah Windows Update yang tidak berjalan dengan normal.

---

## Gejala
- Windows Update stuck di 0% atau 100%
- Muncul error code saat update
- Update gagal berulang kali
- Komputer meminta restart terus

---

## Troubleshooting Steps

### 1. Restart Komputer
Restart komputer lalu coba jalankan Windows Update kembali.

---

### 2. Jalankan Windows Update Troubleshooter
1. Buka Settings
2. Pilih System → Troubleshoot
3. Klik Other troubleshooters
4. Jalankan Windows Update

---

### 3. Restart Windows Update Service
1. Tekan `Win + R`
2. Ketik `services.msc`
3. Restart:
   - Windows Update
   - Background Intelligent Transfer Service

---

### 4. Clear SoftwareDistribution Folder
1. Buka Command Prompt sebagai Administrator
2. Jalankan (tanpa tanda ketik ""):
  - "net stop wuauserv"
  - "net stop bits"
3. Hapus isi folder:
  - C:\Windows\SoftwareDistribution
4. Jalankan kembali (tanpa tanda ketik ""):
  - "net start wuauserv"
  - "net start bits"

---

## Hubungi IT Support Jika
- Update tetap gagal setelah troubleshooting
- Error code terus muncul
- Sistem menjadi tidak stabil


