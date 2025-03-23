# Quran-Finder-Web

![Quran Finder](https://blog.classy.id/upload/gambar_berita/c69ebfc5f1abb21b87bb576c22ef590d_20250323225057.png)

Aplikasi web pencarian Al-Quran dengan antarmuka modern dan responsif. Aplikasi ini memungkinkan pengguna untuk mencari ayat-ayat Al-Quran berdasarkan kata kunci, menjelajahi surah, juz, dan halaman mushaf, serta mendengarkan bacaan ayat.

## ✨ Fitur

- 🔍 Pencarian ayat Al-Quran berdasarkan kata kunci
- 📖 Jelajahi Al-Quran berdasarkan surah (114 surah)
- 📑 Jelajahi Al-Quran berdasarkan juz (30 juz)
- 📄 Jelajahi Al-Quran berdasarkan halaman mushaf (604 halaman)
- 🔊 Dengarkan audio bacaan ayat dan surah
- 🌙 Mode gelap/terang
- 📱 Responsif untuk berbagai ukuran layar
- 🕒 Riwayat pencarian terakhir

## 🚀 Demo

Aplikasi ini dapat diakses secara online melalui link berikut:
[https://s.id/quran-finder-web](https://s.id/quran-finder-web)

## 🛠️ Teknologi yang Digunakan

- HTML5
- CSS3
- JavaScript (ES6+)
- [Tailwind CSS](https://tailwindcss.com/) - Framework CSS
- [Font Awesome](https://fontawesome.com/) - Icon library
- [Google Apps Script](https://developers.google.com/apps-script) - Hosting dan backend

## 📋 Prasyarat

Untuk menjalankan aplikasi ini secara lokal atau mengembangkannya, Anda memerlukan:

- Akun Google (untuk Google Apps Script)
- Browser modern
- Koneksi internet (untuk mengakses API Al-Quran)

## 🔧 Instalasi dan Deployment

### Cara Deploy di Google Apps Script

1. Buka [Google Apps Script](https://script.google.com)
2. Klik tombol "Proyek baru"
3. Buat file baru dengan nama "index.html" dan salin kode HTML dari repository ini
4. Salin kode berikut ke file "Code.gs":

```javascript
function doGet() {
  return HtmlService.createHtmlOutputFromFile('index')
    .setTitle('Al-Quran App')
    .setXFrameOptionsMode(HtmlService.XFrameOptionsMode.ALLOWALL);
}
```

5. Klik "Deploy" > "New deployment"
6. Pilih tipe "Web app"
7. Setel akses ke "Anyone" dan klik "Deploy"
8. Salin URL yang diberikan untuk mengakses aplikasi

## 🤝 Kontribusi

Kontribusi selalu diterima! Jika Anda ingin berkontribusi:

1. Fork repository
2. Buat branch fitur baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan Anda (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buka Pull Request

## 📝 Lisensi

Didistribusikan di bawah Lisensi MIT. Lihat `LICENSE` untuk informasi lebih lanjut.

## 📬 Kontak

Andri Wiratmono - kontak@classy.id

Link Proyek: [https://github.com/classyid/quran-finder-web](https://github.com/classyid/quran-finder-web)
