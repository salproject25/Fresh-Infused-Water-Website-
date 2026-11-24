# Panduan Lengkap Website Fresh Infused Water 🌿
## Konsep: "Interactive Tropical Fresh Experience"

Selamat datang di repositori website resmi **Fresh Infused Water**! Website ini dirancang khusus untuk UMKM minuman infused water premium dengan konsep **Interactive Tropical Fresh & Natural Premium**.

Website ini dibangun menggunakan arsitektur statis modern berkecepatan tinggi:
- **100% Client-Side Pure HTML5, CSS3, & Vanilla JavaScript**
- **Tailwind CSS CDN + Custom Animations & Micro-Interactions**
- **Zero Build Step & Zero Database Requirement** (Langsung berfungsi di browser tanpa instalasi NodeJS)
- **Siap Hosting 1-Klik** di Netlify Drop, GitHub Pages, atau Vercel.

---

## 🎨 Palet Warna Resmi
| Nama Warna | Kode Hex | Penggunaan |
| :--- | :--- | :--- |
| **Fresh Green** | `#8FAF78` | Aksen tombol utama, progress bar, border aktif |
| **Sage Green** | `#A8B89A` | Garis pembatas, badge sekunder, elemen alam |
| **Cream** | `#FAF8F0` | Latar belakang seluruh halaman website |
| **Lemon Yellow** | `#F4D75E` | Highlight tagline, bintang ulasan, pulse dot |
| **Strawberry Red**| `#E98282` | Badge Signature, aksen buah berry |
| **Dark Green** | `#294B35` | Teks judul utama, tombol CTA primer, latar footer |

---

## 📁 Struktur 6 Halaman & File Proyek

```text
fresh-infused-water/
├── index.html                  # 1. Halaman Beranda (Hero, 3D Benefit, 6 Produk Unggulan)
├── produk.html                 # 2. Halaman Katalog 6 Produk & Staggered Reveal
├── detail.html                 # 3. Halaman Detail Produk & Switcher Varian Interaktif
├── tentang.html                # 4. Halaman Natural Storytelling & Animated Timeline
├── galeri.html                 # 5. Halaman Galeri Foto & Interactive Lightbox Modal
├── kontak.html                 # 6. Halaman Kontak, Platform Resmi & Quick Order Form
├── buka-website.bat            # Script 1-klik untuk membuka website langsung di browser
├── vercel.json                 # Konfigurasi routing static host Vercel
├── README.md                   # Dokumentasi teknis & panduan pengelolaan
├── assets/
│   ├── logo/
│   │   ├── logo.jpg            # Logo Resmi Fresh Infused Water (Bulat Premium)
│   │   ├── brand-logo.jpg      # Salinan Logo Resmi
│   │   └── favicon.svg         # Favicon daun & embun air
│   └── images/
│       ├── brand-logo.jpg      # Logo Resmi untuk Showcase Tentang Kami
│       ├── about-brand.jpg     # Gambar Brand Botol & Buah Segar (Tentang Kami)
│       ├── mix-fruit.jpg       # Foto Produk Asli 1: Mix Fruit (Rp20.000 / 500ml)
│       ├── lychee-lime-mint.jpg# Foto Produk Asli 2: Lychee Lime Mint
│       ├── pineapple-lemon.jpg # Foto Produk Asli 3: Pineapple Lemon
│       ├── apple-cinnamon.jpg  # Foto Produk Asli 4: Apple Cinnamon
│       ├── mango-lime-mint.jpg # Foto Produk Asli 5: Mango Lime Mint
│       ├── blueberry-orange-lime.jpg # Foto Produk Asli 6: Blueberry Orange Lime
│       └── *.svg               # Ilustrasi buah & dekorasi tropis
├── css/
│   └── style.css               # Loader, progress bar, keyframes buah, 3D tilt, lightbox
└── js/
    ├── products.js             # PUSAT DATA: Konfigurasi Bisnis, 6 Produk, Harga & Link Resmi
    └── main.js                 # Logika interaktif: Loader, Lightbox, Switcher Detail, WhatsApp Form
```

---

## 🍹 6 Varian Resmi Fresh Infused Water (Rp20.000 / 500ml)
1. **Mix Fruit (Signature Varian)**: Perpaduan lemon, strawberry segar, irisan mentimun, dan daun mint aromatik.
2. **Lychee Lime Mint**: Manis eksotis buah leci berpadu sentuhan jeruk nipis segar dan mint dingin.
3. **Pineapple Lemon**: Manisnya buah nanas tropis dipadu kesegaran lemon murni dan aroma mint.
4. **Apple Cinnamon**: Irisan apel merah segar berpadu aroma hangat batang kayu manis alami.
5. **Mango Lime Mint**: Harum manis mangga tropis diseimbangkan kesegaran jeruk nipis dan daun mint.
6. **Blueberry Orange Lime**: Superfruit kaya antioksidan dari blueberry segar, jeruk manis, dan lime.

---

## 🔗 Saluran Bisnis & Tautan Resmi Terverifikasi
- **Nomor WhatsApp**: `0813-8912-1407` (Link otomatis: `https://wa.me/6281389121407`)
- **Instagram Resmi**: `https://www.instagram.com/freshinfused.id?psln=ajdyMmZ2aHJpY2Yy&utm_source=qr`
- **Facebook Marketplace**: `https://www.facebook.com/share/1FWF2DbE1Z/`
- **Shopee Official Store**: `https://s.shopee.co.id/80E5rqXJPH?share_channel_code=1`

---

## 💻 Cara Menjalankan Website Secara Lokal

1. **Cara Paling Praktis (1-Klik):**
   - Klik ganda pada file `buka-website.bat`.
   - Browser default Anda akan otomatis membuka halaman utama `index.html`.
2. **Membuka File HTML Manual:**
   - Masuk ke folder `fresh-infused-water/`.
   - Klik ganda pada file `index.html`, `produk.html`, `detail.html`, `tentang.html`, `galeri.html`, atau `kontak.html`.
3. **Menggunakan Live Server (VS Code / Antigravity IDE):**
   - Klik kanan pada `index.html` -> **Open with Live Server**.

---

## 🌐 Cara Mempublikasikan Website (Online & Gratis)

### Opsi A: Netlify Drop (30 Detik Tanpa Akun / Tanpa Git)
1. Buka browser dan kunjungi: [app.netlify.com/drop](https://app.netlify.com/drop).
2. Tarik (drag & drop) seluruh folder `fresh-infused-water` ke dalam kotak upload Netlify.
3. Tunggu beberapa detik, Netlify akan langsung memberikan URL website publik yang aktif dan dapat langsung dibagikan kepada pelanggan!

### Opsi B: GitHub Pages
1. Buat repositori baru di [github.com](https://github.com) dengan nama `fresh-infused-water`.
2. Upload seluruh isi folder `fresh-infused-water` via browser (Add file -> Upload files).
3. Masuk ke **Settings** -> **Pages** -> Branch: **main** / **root** -> Klik **Save**.
4. Website akan tayang di: `https://[username].github.io/fresh-infused-water/`.

### Opsi C: Vercel
1. Import repositori GitHub Anda di [vercel.com](https://vercel.com).
2. Konfigurasi `vercel.json` sudah disediakan otomatis. Klik **Deploy**.
