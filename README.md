# Portfolio Profesional — Farhan

Website portfolio personal berbasis **HTML, CSS, dan Vanilla JavaScript** (tanpa framework atau build tool), sesuai project brief.

## Fitur

- Hero, ringkasan profesional, ringkasan rekruter
- Dashboard metrik, keahlian teknis, profisiensi
- Pengalaman kerja dengan pencapaian terukur
- Portofolio proyek & proyek unggulan
- Studi kasus profesional (3 unggulan)
- Layanan & keahlian, timeline karier
- Sertifikasi, pendidikan, testimoni
- Personal branding, pusat unduh CV
- Kontak + formulir (demo), vCard
- **Bahasa Indonesia / English** (tanpa reload)
- **Dark / light mode**
- SEO (meta, Open Graph, JSON-LD)
- Scroll progress, back-to-top, salin email

## Struktur

```text
├── index.html
├── css/style.css
├── js/app.js          ← semua konten & logika di sini
├── assets/
│   ├── profile/       ← foto profil (profile.png)
│   ├── cv/            ← cv-indonesia.pdf, cv-english.pdf
│   ├── projects/
│   ├── certificates/
│   ├── company-logos/
│   └── documents/     ← opsional: file statis (vCard manual, dll.)
└── README.md
```

## Menjalankan

Buka `index.html` di browser, atau gunakan server statis lokal:

```bash
# Python
python -m http.server 8080

# Node (npx)
npx serve .
```

Lalu buka `http://localhost:8080`.

## Kustomisasi

1. Edit objek **`PORTFOLIO_DATA`** di `js/app.js` (nama, email, pengalaman, proyek, dll.).
2. Foto profil: `assets/profile/profile.png` (path di `PORTFOLIO_DATA.profile.avatar`).
3. **vCard:** tidak perlu file `.vcf` di folder — dihasilkan otomatis dari `PORTFOLIO_DATA.profile` saat klik "Unduh vCard" di footer. Jika ingin file statis, simpan misalnya di `assets/documents/farhan.vcf` (opsional, tidak dipakai situs saat ini).
3. Tambahkan PDF CV di `assets/cv/` (lihat `assets/cv/README.md`).
4. Sesuaikan label UI di objek **`UI`** jika diperlukan.

## Persyaratan teknis

- HTML5 semantik, satu file CSS, satu file JS
- Mobile-first, responsif
- Chrome, Firefox, Edge, Safari
- Tanpa React, Vue, Bootstrap, Tailwind, jQuery, TypeScript

## Lisensi

Konten dan kode untuk penggunaan pribadi portfolio Anda.
