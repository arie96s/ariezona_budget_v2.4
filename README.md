# 💸 ARIEZONA Budget V.3.1 (APK Edition)

> **Aplikasi Keuangan Personal dengan Cita Rasa Retro Windows 95.**
> *Simpel, Nostalgik, dan Powerful.*

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## 🖥️ Tentang Aplikasi
**ARIEZONA Budget** adalah aplikasi manajemen keuangan berbasis web (HTML/JS) yang dirancang agar ringan dan responsif untuk dikonversi menjadi aplikasi Android (APK). Mengusung tema visual **Windows 95/98**, aplikasi ini membuat kegiatan mencatat keuangan jadi lebih menyenangkan dan estetik.

## ✨ Fitur Utama
* **🎨 Retro UI:** Antarmuka Pixel Art & Windows 95 style yang unik.
* **🧮 Auto Calculator:** Menghitung total Gaji, Hutang, Pengeluaran, dan Sisa Aset secara otomatis.
* **📊 Analisa Keuangan:** Memberikan status kesehatan finansial (Defisit, Sehat, dll).
* **📄 Export Lengkap:**
    * Save to PDF (Format Struk).
    * Export to Excel (.csv).
    * Print Receipt (Thermal Printer friendly).
* **📱 Mobile Optimized:** Anti-zoom dan layout responsif untuk layar HP.

## 📂 Cara Instalasi & Penggunaan

### 1. Untuk Web Browser (PC/Laptop)
Cukup buka file `index.html` menggunakan Chrome, Firefox, atau Edge.

### 2. Untuk Convert ke APK (Android)
Project ini sudah dioptimasi untuk *Webview*. Anda bisa menggunakan tools seperti:
* **Website 2 APK Builder** (Recomended for Windows user)
* Cordova / Capacitor
* Android Studio (Webview)

Pastikan struktur folder aset (gambar/font) sudah lokal agar bisa berjalan **Offline**.

## 🛠️ Struktur Folder
```text
/ARIEZONA-Budget/
│
├── index.html            # File Utama Aplikasi
├── README.md             # Dokumentasi ini
├── /assets/
│   ├── /fonts/           # Font Pixel (VT323, Press Start 2P)
│   ├── /js/              # Library (pdfmake, emailjs)
│   ├── /audio/           # BGM (classic_europe.mp3)
│   └── /img/             # Logo & Icon
