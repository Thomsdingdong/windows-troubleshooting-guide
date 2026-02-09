# Blue Screen (BSOD) Troubleshooting Guide

## Overview
Blue Screen of Death (BSOD) adalah kondisi ketika Windows mengalami error kritis dan harus melakukan restart. Masalah ini biasanya berkaitan dengan driver, hardware, atau sistem operasi.

---

## Gejala
Beberapa indikasi BSOD:

- Layar biru muncul secara tiba-tiba
- Komputer restart otomatis
- Muncul error code pada layar biru
- Sistem menjadi tidak stabil
- BSOD terjadi berulang

---

## Kemungkinan Penyebab
- Driver tidak kompatibel atau rusak
- Update Windows gagal
- RAM bermasalah
- Kerusakan hardware
- Overheating
- File sistem corrupt

---

## Troubleshooting Steps

### 1. Catat Error Code
Saat BSOD muncul, catat error code yang ditampilkan.
Contoh:
CRITICAL_PROCESS_DIED
MEMORY_MANAGEMENT
IRQL_NOT_LESS_OR_EQUAL

---

### 2. Restart Komputer
Restart komputer dan periksa apakah BSOD muncul kembali.

---

### 3. Uninstall Driver Terbaru
Jika BSOD muncul setelah install driver:

1. Buka **Device Manager**
2. Pilih driver yang baru diinstall
3. Klik **Uninstall device**
4. Restart komputer

---

### 4. Jalankan Windows Memory Diagnostic
1. Tekan `Win + R`
2. Ketik:
     mdsched.exe
3. Pilih **Restart now and check for problems**

---

### 5. Jalankan System Restore
Jika BSOD muncul setelah update atau instalasi software:

1. Buka **Control Panel**
2. Pilih **Recovery**
3. Klik **Open System Restore**

---

## Hubungi IT Support Jika
- BSOD terjadi berulang
- Komputer tidak bisa masuk Windows
- Windows Memory Diagnostic menunjukkan error
- Terdapat indikasi kerusakan hardware

