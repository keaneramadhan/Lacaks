<h1 align="center">📍 Lacaks – Location Information Toolkit</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.0-brightgreen?style=for-the-badge">
  <img src="https://img.shields.io/badge/Language-Python-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Linux%20%7C%20Termux%20%7C%20OSX-lightgrey?style=for-the-badge">
</p>

---

## 🧭 Deskripsi
**Lacaks** adalah toolkit untuk membuat website palsu (*fake page*) yang meminta izin lokasi dari korban.  
Jika diizinkan, Seeker akan menampilkan data lokasi dengan akurasi tinggi, bahkan hingga **±30 meter** di perangkat dengan GPS.

---

## 📌 Data yang Didapat
- 📍 **Longitude & Latitude**
- 🎯 **Accuracy**
- 🗻 **Altitude**
- 🧭 **Direction**
- 🚀 **Speed**
- 💻 **Device Info** (OS, Browser, CPU, GPU)
- 🌐 **IP Public & Local**
- 🔍 **Port Lokal**

---

## ⚡ Fitur
- **IP Recon** otomatis setelah data diterima
- **Fallback** ke IP GeoLocation jika GPS tidak tersedia
- **Template** siap pakai:
  - NearYou
  - Google Drive
  - WhatsApp
  - Telegram
  - Zoom
  - Google reCAPTCHA
- **Custom Template** support

---

## 📦 Install
```bash
git clone https://github.com/keaneramadhan/lacaks.git
cd lacaks/
chmod +x install.sh
./install.sh
