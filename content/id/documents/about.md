---  
title: About 
date: 2025-03-31T01:19:10+07:00
image: https://placehold.co/1080x520
description: "Tentang Tema My Notes"  
tags:  
  - pages  
  - documents
  - about
categories:  
  - Pages  
---  
# Catatan Saya  

## 🌟 **Gambaran Umum**  
Tema Hugo serbaguna untuk **blog, portofolio, dokumentasi teknis, dan catatan pribadi**. Cocok untuk penulis, pengembang, pelajar, dan pengguna non-bisnis.  
**Demo**: [Tautan Demo](https://wumbojb.github.io/my-notes-demo) | **Repositori**: [GitHub](https://github.com/masputrawae/my-notes)  

---  

## 🚀 **Fitur Utama**  
- **Desain Modern**: Responsif, mode gelap otomatis, tata letak minimalis.  
- **Multi-bahasa**: Mendukung 15+ bahasa (termasuk Indonesia, Inggris, Jepang, dll.).  
- **Integrasi**:  
  - 🔍 Pencarian konten (lunr.js).  
  - 📊 Google Analytics.  
  - 💬 Komentar Giscus (GitHub Discussions).  
- **Optimasi**: Ramah SEO, lazy loading untuk gambar, aksesibilitas WCAG.  
- **Shortcodes**: Gambar responsif, embed YouTube, dan lainnya.  

---  

## 📦 **Instalasi**  
1. **Prasyarat**: Versi Hugo terbaru (edisi extended).  
2. **Tambahkan Tema**:  
   ```bash  
   git submodule add https://github.com/masputrawae/my-notes.git themes/my-notes-theme  
   ```  
3. Salin konfigurasi dari `exampleSite/` ke root proyek Anda.  

---  

## ⚙️ **Konfigurasi**  
File konfigurasi utama di `config/_default/`:  
- `hugo.toml`: Pengaturan dasar Hugo.  
- `params.toml`: Parameter tema.  
- `languages.toml`: Pengaturan bahasa.  
- `services.toml`: Pengaturan Google Analytics.  

---  

## 📝 **Konten**  
1. **Posting Blog** (`content/posts/`)  
2. **Proyek** (`content/projects/`)  
3. **Catatan** (`content/notes/`)  
4. **Dokumentasi** (`content/documents/`)  

---  

## 🛠 **Optimasi & Dukungan**  
- **Browser**: Chrome, Firefox, Safari, Edge terbaru.  
- **Laporan Bug**: Buat [issue di GitHub](https://github.com/masputrawae/my-notes/issues/new).  
- **Tips**:  
  - Gunakan gambar `.webp` untuk performa lebih baik.  
  - Batasi shortcode kompleks di halaman statis.  

---  

## 📜 **Lisensi**  
Tema ini dilisensikan di bawah [MIT License](https://github.com/masputrawae/my-notes?tab=MIT-1-ov-file). Bebas dimodifikasi dan digunakan untuk keperluan komersial.  

---  

## 🙌 **Berkontribusi**  
1. Fork repositori ini.  
2. Buat branch baru untuk fitur Anda: `git checkout -b fitur-anda`.  
3. Ajukan pull request.  

---  

> [!CATATAN] Catatan  
> Untuk kustomisasi CSS/JS tingkat lanjut, disarankan untuk memahami [Hugo Modules](https://gohugo.io/hugo-modules/) atau melakukan fork tema ini.  

---