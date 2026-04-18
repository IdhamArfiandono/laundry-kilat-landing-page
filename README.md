# Laundry Kilat - Landing Page

Landing page profesional untuk jasa laundry antar jemput **Laundry Kilat**, dibangun dengan HTML, Tailwind CSS (CDN), dan JavaScript murni — satu file, tanpa framework, tanpa backend.

---

## Tampilan

| Section | Deskripsi |
|---|---|
| Navbar | Sticky, hamburger menu mobile, smooth scroll |
| Hero | Gradient biru, tagline, badge, CTA WhatsApp |
| Layanan | 4 kartu layanan dengan ikon SVG dan harga |
| Kalkulator | Estimasi harga otomatis berbasis JavaScript |
| Cara Order | Timeline 4 langkah pemesanan |
| Testimoni | 3 ulasan pelanggan dengan avatar |
| Kontak | Informasi kontak, jam operasional, area layanan |
| Footer | Navigasi, sosial media, copyright |

---

## Fitur Utama

- **Kalkulator Harga Otomatis** — pilih jenis layanan, input berat/jumlah, harga tampil instan; validasi minimum order 2 kg; format Rupiah `Intl.NumberFormat`
- **Tombol WhatsApp** — semua CTA terhubung ke WhatsApp dengan pesan pre-filled
- **Animasi Scroll** — elemen fade-in menggunakan `IntersectionObserver`; menghormati `prefers-reduced-motion`
- **Responsive Design** — mobile-first, breakpoint 375 / 768 / 1024 / 1440 px
- **Sticky Navbar** — shadow muncul saat scroll; hamburger menu dengan toggle animasi
- **Aksesibilitas** — semua ikon SVG inline (tidak ada emoji), `aria-label`, heading hierarchy, focus states

---

## Harga Layanan

| Layanan | Harga | Satuan | Min. Order |
|---|---|---|---|
| Cuci Kering | Rp 5.000 | /kg | 2 kg |
| Cuci Setrika | Rp 8.000 | /kg | 2 kg |
| Cuci Sepatu | Rp 25.000 | /pasang | — |
| Laundry Kilogram | Rp 6.000 | /kg | 2 kg |

---

## Teknologi

- **HTML5** — semantik, aksesibel
- **[Tailwind CSS v3](https://tailwindcss.com)** — via CDN, extended config
- **Google Fonts** — Poppins (300–800)
- **Vanilla JavaScript** — kalkulator, hamburger menu, scroll observer
- **[UI Avatars](https://ui-avatars.com)** — avatar testimoni

---

## Struktur Proyek

```
laundry-kilat-landing-page/
└── index.html   # Seluruh halaman dalam satu file
```

---

## Cara Menjalankan

Tidak perlu instalasi atau build step. Cukup buka file langsung di browser:

```bash
# Clone repository
git clone https://github.com/IdhamArfiandono/laundry-kilat-landing-page.git

# Buka di browser
cd laundry-kilat-landing-page
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

Atau buka `index.html` langsung dari file explorer.

---

## Konfigurasi WhatsApp

Nomor WhatsApp terdapat di beberapa tempat dalam `index.html`. Ganti `6281234567890` dengan nomor aktif:

```html
<!-- Contoh: ganti semua kemunculan href ini -->
href="https://wa.me/6281234567890?text=..."
```

---

## Area Layanan

Jakarta Selatan · Jakarta Pusat · Jakarta Barat

**Jam Operasional:** Setiap hari, 07.00–21.00 WIB

---

## Lisensi

MIT License — bebas digunakan dan dimodifikasi.
