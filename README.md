# Landing Page PMI Lombok Barat

Selamat datang di repository landing page resmi PMI Lombok Barat - Perhimpunan Mitigasi Bencana Indonesia Lombok Barat.

## 📋 Deskripsi

Landing page modern dan responsif untuk PMI Lombok Barat yang dibangun dengan HTML5, CSS3, dan JavaScript vanilla. Website ini menampilkan informasi lengkap tentang organisasi, program-program unggulan, pencapaian, dan cara menghubungi kami.

## ✨ Fitur Utama

### 1. **Navbar Responsif**
- Menu navigasi sticky yang mengikuti scroll
- Hamburger menu untuk mobile devices
- Efek hover dan transisi yang smooth

### 2. **Hero Section**
- Gradient background yang menarik
- Call-to-action buttons
- Animasi entrance yang eye-catching

### 3. **Tentang Kami**
- Visi dan Misi PMI Lombok Barat
- Statistik pencapaian (Anggota, Program, Masyarakat Terlayani, Siap Siaga)
- Kartu-kartu interaktif dengan efek hover

### 4. **Program Kami**
- 6 program unggulan dengan ikon
- Grid layout yang responsif
- Deskripsi lengkap untuk setiap program
- Link "Pelajari Lebih Lanjut"

### 5. **Statistik & Pencapaian**
- Counter animation saat scroll
- 4 kategori pencapaian utama
- Animasi number increment yang smooth

### 6. **Kontak**
- Informasi lengkap (Alamat, Telepon, Email, Jam Operasional)
- Form kontak interaktif
- Validasi form sederhana

### 7. **Footer**
- Link-link penting
- Social media links
- Copyright information

## 🎨 Fitur Desain

- **Responsif**: Fully responsive design untuk desktop, tablet, dan mobile
- **Animasi**: Smooth transitions dan scroll animations
- **Modern**: Design modern dengan warna PMI (merah) sebagai primary color
- **Aksesibilitas**: Keyboard navigation dan screen reader friendly
- **Performance**: Optimized untuk loading cepat

## 📱 Breakpoints

- **Desktop**: > 768px
- **Tablet**: 480px - 768px
- **Mobile**: < 480px

## 🛠️ Struktur File

```
landingbaru.github.io/
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
│       └── logo.png (placeholder)
└── README.md
```

## 🚀 Cara Menggunakan

### 1. Clone Repository
```bash
git clone https://github.com/pmilombokbarat/landingbaru.github.io.git
cd landingbaru.github.io
```

### 2. Buka di Browser
Cukup buka file `index.html` dengan browser favorit Anda.

### 3. Deploy
Repository ini sudah dikonfigurasi untuk GitHub Pages. Push ke branch `main` akan otomatis di-deploy.

## 📝 Kustomisasi

### Mengubah Warna
Edit variabel CSS di `assets/css/style.css`:
```css
:root {
    --primary-color: #d32f2f;      /* Warna merah PMI */
    --secondary-color: #1976d2;    /* Warna biru sekunder */
    /* ... warna lainnya */
}
```

### Menambah Program
Edit bagian Program di `index.html` dan tambahkan card baru:
```html
<div class="program-card">
    <div class="program-icon">
        <i class="fas fa-icon-name"></i>
    </div>
    <h3>Judul Program</h3>
    <p>Deskripsi program</p>
    <a href="#" class="program-link">Pelajari Lebih Lanjut →</a>
</div>
```

### Menambah Konten
Semua konten text berada di `index.html` dan mudah untuk diubah sesuai kebutuhan.

## 🎯 Fitur JavaScript

### Mobile Menu Toggle
Hamburger menu otomatis muncul di perangkat mobile.

### Smooth Scroll
Klik pada link navigasi untuk smooth scroll ke section yang dituju.

### Form Validation
Validasi form kontak sebelum submit.

### Scroll Animations
Elemen animasi saat scroll ke viewport.

### Counter Animation
Angka statistik akan berjalan saat section statistik terlihat.

### Active Nav Link
Link navigasi otomatis highlight berdasarkan section yang sedang dilihat.

## 🔗 Font & Icon

- **Font**: Google Fonts - Segoe UI, Tahoma, Geneva, Verdana
- **Icon**: Font Awesome 6.4.0 via CDN

## 📱 Kompatibilitas Browser

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile browsers

## 🌐 Environment

Untuk development local, tidak diperlukan build tools khusus. Website ini pure HTML, CSS, dan JavaScript tanpa dependencies eksternal selain Font Awesome.

## 📧 Kontak & Support

**PMI Lombok Barat**
- Alamat: Jl. Diponegoro No. 123, Mataram, Lombok Barat
- Telepon: +62 370 123 4567
- Email: info@pmi-lombar.org

## 📄 Lisensi

Copyright © 2024 PMI Lombok Barat. All rights reserved.

## 🤝 Kontribusi

Kami menerima saran dan kontribusi untuk meningkatkan landing page ini. Silakan buat pull request atau buka issue untuk saran.

## ✅ Todo

- [ ] Tambah logo official PMI
- [ ] Integrasikan contact form dengan backend
- [ ] Tambah blog section
- [ ] Tambah gallery/portfolio
- [ ] Tambah testimonial dari beneficiaries
- [ ] Multi-language support
- [ ] SEO optimization
- [ ] Analytics integration

---

**Terakhir diupdate**: 15 Juli 2024
