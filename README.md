# Jelita - Jendela Literasi Tinta Emas Warga Binaan

Website platform blog dan konten untuk cerita pendek dari perempuan hebat Indonesia, dibangun dengan Bootstrap 5 dan desain responsif modern.

## 🚀 Fitur Utama

- **Desain Responsif**: Optimal di desktop, tablet, dan mobile
- **UI/UX Modern**: Menggunakan skema warna ungu dan merah muda yang menarik
- **Animasi Interaktif**: Efek hover, transisi, dan animasi CSS
- **Navigasi Smooth**: Scroll halus antar section
- **Search Functionality**: Pencarian konten dengan filter genre
- **Newsletter Subscription**: Sistem berlangganan email
- **Mobile-First**: Optimized untuk perangkat mobile

## 🎨 Desain & Warna

### Skema Warna
- **Primary**: Ungu (#6f42c1)
- **Secondary**: Merah Muda (#ec4899)
- **Light**: Ungu Muda (#e9d5ff)
- **Dark**: Biru Gelap (#1e293b)
- **Gray**: Abu-abu (#64748b)

### Font
- **Primary Font**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700

## 📁 Struktur File

```
FE_JELITA/
├── index.html          # File HTML utama
├── styles.css          # Custom CSS styling
├── script.js           # JavaScript interaktivitas
└── README.md           # Dokumentasi
```

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Struktur semantik modern
- **CSS3**: Custom styling dengan CSS variables
- **Bootstrap 5.3.0**: Framework CSS untuk layout responsif
- **Font Awesome 6.4.0**: Icon library
- **JavaScript ES6+**: Interaktivitas dan animasi
- **Google Fonts**: Typography

## 📱 Responsivitas

Website ini responsif dengan breakpoint berikut:
- **Desktop**: ≥992px
- **Tablet**: 768px - 991px
- **Mobile**: <768px

### Fitur Responsif
- Navbar collapse pada mobile
- Grid layout yang menyesuaikan
- Gambar yang scalable
- Typography yang responsive

## 🎯 Sections

### 1. Header/Navigation
- Logo "Jelita" dengan ikon petir
- Menu navigasi: Beranda, Cerpen, Tentang, Donasi
- Tombol pencarian dan login
- Responsive hamburger menu

### 2. Hero Section
- Judul utama dengan gradient background
- Animasi kristal AI yang floating
- Call-to-action button
- Pattern background dengan CSS

### 3. Search Section
- Form pencarian dengan input judul
- Dropdown filter genre
- Tombol cari yang responsif

### 4. Featured Sections
- Kartu "Baru Saja Terbit"
- Kartu "Terpopuler"
- Hover effects dan animasi

### 5. Rekomendasi Jelita
- Artikel utama dengan gambar besar
- Grid 3 kolom artikel kecil
- Meta informasi (kategori, tanggal)
- Link "Read More"

### 6. Pilihan Pembaca
- Layout serupa dengan rekomendasi
- Background light untuk kontras
- 6 artikel dalam grid

### 7. Newsletter Section
- Background gradient merah muda
- Form subscription email
- Pattern overlay

### 8. Footer
- Logo dan navigasi
- Social media icons
- Copyright information

## 🎨 Komponen UI

### Buttons
- Primary buttons dengan warna merah muda
- Hover effects dengan ripple animation
- Responsive sizing

### Cards
- Article cards dengan shadow dan border radius
- Hover transform effects
- Image overlay dengan object-fit

### Forms
- Search form dengan styling modern
- Newsletter subscription form
- Input validation

### Animations
- Crystal floating animation
- Eye blinking effect
- Fade-in animations
- Hover transitions

## 🔧 Cara Menjalankan

1. **Clone atau download** file ke local machine
2. **Buka file** `index.html` di browser
3. **Atau gunakan live server** untuk development

### Dengan Live Server (VS Code)
```bash
# Install Live Server extension
# Right click index.html -> "Open with Live Server"
```

### Dengan Python
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

### Dengan Node.js
```bash
# Install http-server globally
npm install -g http-server

# Run server
http-server
```

## 📱 Testing Responsivitas

1. **Browser DevTools**: F12 → Toggle device toolbar
2. **Resize window**: Drag browser corner
3. **Mobile devices**: Test di smartphone/tablet

## 🎯 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🔮 Fitur JavaScript

### Interaktivitas
- Smooth scrolling navigation
- Form validation
- Notification system
- Back to top button
- Mobile menu handling

### Animations
- Intersection Observer untuk scroll animations
- Ripple effects pada buttons
- Hover effects pada cards
- Loading animations

### Performance
- Lazy loading images
- Debounced scroll events
- Optimized animations

## 🎨 Customization

### Mengubah Warna
Edit CSS variables di `styles.css`:
```css
:root {
    --primary-color: #6f42c1;
    --secondary-color: #ec4899;
    /* ... */
}
```

### Mengubah Font
Ganti Google Fonts link di `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

### Menambah Konten
- Edit HTML structure di `index.html`
- Update CSS styling di `styles.css`
- Tambah JavaScript functionality di `script.js`

## 🐛 Troubleshooting

### Gambar Tidak Muncul
- Pastikan koneksi internet aktif (untuk Unsplash images)
- Ganti URL gambar dengan gambar lokal jika perlu

### Animasi Tidak Berfungsi
- Pastikan JavaScript enabled di browser
- Check console untuk error messages

### Responsivitas Bermasalah
- Pastikan viewport meta tag ada
- Check CSS media queries
- Test di berbagai device

## 📄 License

Proyek ini dibuat untuk tujuan pembelajaran dan demonstrasi. Silakan gunakan dan modifikasi sesuai kebutuhan.

## 👥 Kontribusi

1. Fork repository
2. Buat feature branch
3. Commit changes
4. Push ke branch
5. Buat Pull Request

## 📞 Support

Untuk pertanyaan atau dukungan, silakan buat issue di repository atau hubungi developer.

---

**Dibuat dengan ❤️ untuk platform literasi Indonesia** 