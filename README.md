<div align="center">

# Portfolio — Farhan Rachmat Syahrizal

**Software Engineer** · Backend Development & QA Automation

[![Live Demo](https://img.shields.io/badge/demo-GitHub%20Pages-2ea44f?style=for-the-badge&logo=github)](https://syahrizall.github.io/farhan-portofolio/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

[🌐 Lihat situs](https://syahrizall.github.io/farhan-portofolio/) · [💼 LinkedIn](https://linkedin.com/in/farhanrachmats) · [🐙 GitHub](https://github.com/syahrizall)

</div>

---

Website portfolio personal yang **cepat, responsif, dan mudah dikustomisasi** — dibangun dengan HTML, CSS, dan Vanilla JavaScript tanpa framework atau build tool.

## ✨ Fitur

| Kategori | Detail |
|----------|--------|
| **Konten** | Hero, ringkasan profesional, metrik, keahlian, pengalaman kerja, proyek, studi kasus, sertifikasi, pendidikan |
| **Interaksi** | Dark / light mode, bahasa **ID / EN** tanpa reload, salin email, unduh CV & vCard |
| **UX** | Mobile-first, menu bottom sheet, scroll progress, tombol kembali ke atas |
| **SEO** | Meta tags, Open Graph, JSON-LD terstruktur |

## 🖼️ Pratinjau

> Buka [demo langsung](https://syahrizall.github.io/farhan-portofolio/) untuk pengalaman penuh (animasi, tema gelap, dan toggle bahasa).

## 🛠️ Tech stack

- **Markup & style:** HTML5 semantik, CSS custom (mobile-first)
- **Logic:** satu file `js/app.js` — data-driven (`PORTFOLIO_DATA` + `UI`)
- **Deploy:** GitHub Pages (static hosting)
- **Tanpa:** React, Vue, Bootstrap, Tailwind, jQuery, TypeScript, bundler

## 📁 Struktur proyek

```text
farhan-portofolio/
├── index.html              # Halaman utama & SEO
├── css/
│   └── style.css           # Semua styling
├── js/
│   └── app.js              # Data, i18n, render, interaksi
├── assets/
│   ├── profile/            # Foto profil & logo
│   ├── cv/                   # CV PDF (ID & EN)
│   ├── projects/
│   ├── certificates/
│   └── company-logos/
└── README.md
```

## 🚀 Menjalankan secara lokal

Clone repositori, lalu jalankan server statis (disarankan — beberapa fitur browser lebih stabil dengan `http://`):

```bash
git clone https://github.com/syahrizall/farhan-portofolio.git
cd farhan-portofolio
```

**Opsi A — Python**

```bash
python -m http.server 8080
```

**Opsi B — Node (npx)**

```bash
npx serve .
```

Buka **http://localhost:8080** di browser.

> Bisa juga membuka `index.html` langsung, tetapi server lokal lebih direkomendasikan.

## ✏️ Kustomisasi

Semua konten utama ada di **`js/app.js`**:

1. **`PORTFOLIO_DATA`** — profil, pengalaman, proyek, studi kasus, sertifikasi, dll.
2. **`UI`** — label antarmuka (opsional).

**Aset yang perlu disesuaikan:**

| Aset | Lokasi | Field di `profile` |
|------|--------|-------------------|
| Foto hero | `assets/profile/profile.png` | `avatar` |
| Logo header | `assets/profile/system-administration.png` | `logo` |
| CV Indonesia | `assets/cv/cv-farhan-rachmat-syahrizal-id.pdf` | `cvId` |
| CV English | `assets/cv/cv-farhan-rachmat-syahrizal-en.pdf` | `cvEn` |

**vCard** dihasilkan otomatis dari data profil saat pengunjung mengklik *Unduh vCard* di footer — tidak perlu file `.vcf` statis.

Detail folder CV: [`assets/cv/README.md`](assets/cv/README.md).

## 📤 Deploy ke GitHub Pages

1. Push perubahan ke branch `main`
2. Di repo GitHub: **Settings → Pages**
3. Source: **Deploy from a branch** → branch `main`, folder **`/ (root)`**
4. Situs tersedia di: **https://syahrizall.github.io/farhan-portofolio/**

Setelah mengganti gambar atau PDF dengan **nama file yang sama**, lakukan hard refresh (`Ctrl+F5`) jika perubahan belum terlihat — browser dan CDN bisa meng-cache aset statis.

## 📬 Kontak

**Farhan Rachmat Syahrizal**  
📧 [farhan.rachmat09@gmail.com](mailto:farhan.rachmat09@gmail.com)  
💼 [LinkedIn](https://linkedin.com/in/farhanrachmats) · 🐙 [GitHub](https://github.com/syahrizall)

---

<div align="center">

Dibuat dengan ❤️ menggunakan HTML, CSS & JavaScript murni.

</div>
