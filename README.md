# 🌱 Irfnrdh Digital Garden

**Tempat Belajar Terbuka — Catatan, Eksperimen, dan Portfolio.**  

Ini adalah *digital garden* pribadi: kumpulan semua yang saya pelajari (coding, desain, produktivitas, parenting, dll).  
Repo ini siap **di-clone** dan **di-fork** untuk kamu kembangkan jadi kebun digital versimu sendiri.

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://irfnrdh.github.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](#-lisensi)
[![GitHub stars](https://img.shields.io/github/stars/irfnrdh/irfnrdh.github.io?style=social)](https://github.com/irfnrdh/irfnrdh.github.io/stargazers)



## 📖 Konsep

Berbeda dari blog linear, *digital garden* berisi:
- **Catatan hidup** yang terus disunting & berkembang
- **Eksperimen & prototipe** kecil untuk eksplorasi ide
- **Dokumentasi pembelajaran** harian yang terstruktur
- **Portfolio proyek** yang diorganisir per tahun
- **Knowledge graph** yang saling terhubung



## 🚀 Fitur Utama

### 🏗️ **Struktur Website**
- **Halaman Inti**: Home, About, Works, Portfolio, Product, CV
- **Portfolio Tahunan** (2020–2025) untuk timeline proyek yang jelas
- **Digital Products**: Tools seperti Domainfinder
- **Learning Notes**: Teknologi, desain, self-hacking, parenting

### 🎨 **Teknologi**
- **Static Site**: Mudah dipelihara, cepat loading, SEO-friendly
- **GitHub Pages**: Hosting gratis dengan custom domain support
- **Responsive Design**: Optimal di semua perangkat
- **Progressive Enhancement**: Fungsional tanpa JavaScript



## 📂 Struktur Proyek

```
.
├── index.html              # Landing page utama
├── about.html              # Profil & filosofi
├── creative.html           # Showcase karya kreatif
├── portfolio.html          # Portfolio lengkap per tahun
├── product.html            # Digital products
├── cv.html                 # Resume/CV online
├── content.json            # Database konten & metadata
├── assets/                 # Static resources
│   ├── css/               # Stylesheets
│   ├── js/                # Scripts & interactivity
│   └── images/            # Media assets
├── notes/                  # Digital garden notes (opsional)
└── README.md              # Dokumentasi ini
```

> **Catatan**: Struktur dapat berkembang seiring pertumbuhan garden



## ⚡️ Quick Start

### 🔄 **Clone Repository**
```bash
git clone https://github.com/irfnrdh/irfnrdh.github.io.git
cd irfnrdh.github.io
```

### 🍴 **Fork untuk Versi Pribadi** *(Recommended)*
1. Klik tombol **Fork** di kanan atas repository
2. Pilih akun GitHub Anda
3. Clone hasil fork:
```bash
git clone https://github.com/<username>/irfnrdh.github.io.git
cd irfnrdh.github.io
```

### 🌐 **Jalankan Lokal**
Website ini bersifat **static**, jadi mudah di-deploy:

```bash
# Opsi 1: Buka langsung index.html di browser

# Opsi 2: Local server (Python)
python3 -m http.server 8080
# Akses: http://localhost:8080

# Opsi 3: Local server (Node.js)
npx http-server -p 8080

# Opsi 4: Live Server (VS Code Extension)
# Install "Live Server" extension, klik kanan index.html → "Open with Live Server"
```



## 🧩 Kustomisasi & Pengembangan

### ✏️ **Mengedit Konten**
- **Profil & Narasi**: Edit `about.html` dan sesuaikan dengan story Anda
- **Portfolio Projects**: Update `portfolio.html` dan/atau `content.json`
- **Styling**: Modifikasi files di folder `assets/css/`
- **Functionality**: Tambahkan interaktivitas di `assets/js/`

### 📝 **Menambah Konten Baru**
1. Buat file HTML baru (misal: `blog.html`, `thoughts.html`)
2. Tambahkan link di navigasi utama (`index.html`)
3. Update `content.json` jika menggunakan dynamic content loading
4. Commit dan push perubahan

### 🎨 **Best Practices**
- **Work in Progress OK**: Tidak harus perfect, tunjukkan proses belajar
- **Link Everything**: Buat koneksi antar halaman dan ide
- **Version Your Thoughts**: Gunakan git untuk tracking evolusi ide
- **Tag & Categorize**: Gunakan metadata untuk organizasi yang lebih baik



## 🤝 Kontribusi

Kontribusi dalam bentuk ide, perbaikan, atau fitur baru sangat diterima!

### 🔧 **Cara Kontribusi**
1. **Fork** repository ini
2. Buat feature branch:
```bash
git checkout -b feat/awesome-feature
```
3. Commit perubahan:
```bash
git commit -m "feat: add awesome new feature"
```
4. Push ke branch:
```bash
git push origin feat/awesome-feature
```
5. Buka **Pull Request** dengan deskripsi yang jelas

### 💡 **Ide Kontribusi yang Menarik**
- [ ] **Search functionality** berbasis client-side JavaScript
- [ ] **Content tagging system** untuk better organization
- [ ] **Related notes component** berdasarkan keywords/tags
- [ ] **Content map visualization** otomatis dari `content.json`
- [ ] **Dark/light mode toggle**
- [ ] **Reading progress indicator**
- [ ] **Comment system** menggunakan GitHub Issues/Discussions



## 🗺️ Roadmap

### 🎯 **Short Term** (Q1-Q2 2025)
- [ ] **Content Map Page** untuk menelusuri seluruh notes
- [ ] **Note Templates** dengan metadata (date, status, tags)
- [ ] **Improved Navigation** dengan breadcrumbs
- [ ] **Mobile Optimization** enhancements

### 🚀 **Medium Term** (Q3-Q4 2025)
- [ ] **Search & Filter System** ringan berbasis JavaScript
- [ ] **Related Content Suggestions** otomatis
- [ ] **RSS/Atom Feed** untuk subscribers
- [ ] **Analytics Integration** untuk insights

### 🌟 **Long Term** (2026+)
- [ ] **Multi-language Support** (EN/ID)
- [ ] **Interactive Learning Paths**
- [ ] **Collaboration Features** untuk guest contributors
- [ ] **API Integration** dengan external tools



## 🧪 Pedoman Digital Gardening

### 📋 **Note Writing Guidelines**
- **Atomic Notes**: Satu ide per note, mudah di-link
- **Progressive Disclosure**: Mulai sederhana, kembangkan bertahap  
- **Link Liberally**: Hubungkan ide-ide yang saling berkaitan
- **Status Tracking**: Gunakan label status untuk setiap note

### 🏷️ **Status Labels**
- 🌱 **Seed**: Ide awal, belum dikembangkan
- 🌿 **Growing**: Sedang dikembangkan, work in progress  
- 🌳 **Evergreen**: Mature content, well-developed
- 🔄 **Refactoring**: Sedang di-reorganisasi atau di-update

### 📊 **Content Organization**
- **Chronological**: Portfolio & project timeline
- **Categorical**: Learning notes by subject/domain
- **Relational**: Cross-references and idea connections
- **Contextual**: Situational and use-case specific content



## 📈 Analytics & Insights

Website ini menggunakan pendekatan **privacy-first analytics**:
- **No cookies tracking** personal information
- **Aggregate data only** untuk improvement insights
- **Open source analytics** tools preferred
- **User control** atas data sharing preferences



## 📜 Lisensi

Dirilis di bawah [**MIT License**](LICENSE). 

**Artinya**: Silakan gunakan, modifikasi, distribusi, dan kembangkan untuk kebutuhan personal maupun komersial. Tidak ada warranty, tapi credit ke original author akan sangat dihargai! 😊



## ✨ Inspirasi & Kredit

### 🙏 **Terima Kasih Kepada**
- **Digital Garden Community** untuk konsep knowledge sharing terbuka
- **Learn in Public Movement** yang mendorong transparansi pembelajaran  
- **Open Source Contributors** yang membuat tools dan framework yang digunakan
- **GitHub Pages** untuk platform hosting yang reliable dan gratis

### 📚 **Referensi Digital Garden**
- [Maggie Appleton's Digital Garden](https://maggieappleton.com/garden-history)
- [Andy Matuschak's Working Notes](https://notes.andymatuschak.org/)
- [Tom Critchlow's Wiki](https://tomcritchlow.com/wiki/)



## 📞 Connect & Support

- **Website**: [irfnrdh.github.io](https://irfnrdh.github.io)
- **GitHub**: [@irfnrdh](https://github.com/irfnrdh)
- **Issues**: [Report bugs or suggest features](https://github.com/irfnrdh/irfnrdh.github.io/issues)
- **Discussions**: [Join community conversations](https://github.com/irfnrdh/irfnrdh.github.io/discussions)



*"The best time to plant a tree was 20 years ago. The second best time is now."*  
**— Start your digital garden today! 🌱**
