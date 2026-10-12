# GSAP Web Motion

Koleksi animasi GSAP siap pakai untuk membuat website lebih hidup. Setiap contoh berdiri sendiri dalam satu file HTML, sehingga bisa langsung dibuka di browser atau disalin ke proyek Anda.

## Demo

Setiap contoh bisa dilihat langsung di browser:

| Kategori | Contoh | Demo |
|----------|--------|------|
| Hero | Hero hutan pinus dengan latar blur | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/hero/hero-hutan-pinus.html) |
| Hero | Hero high-tech dengan latar blur | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/hero/hero-high-tech.html) |
| Hero | Hero power supply dengan jaringan tiang listrik | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/hero/hero-power-supply.html) |
| Hero | Hero electricity dengan kilat yang berkedip | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/hero/hero-electricity.html) |
| Hero | Hero farm dengan ladang gandum dan burung | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/hero/hero-farm.html) |
| Hero | Hero ocean dengan gelombang berlapis | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/hero/hero-ocean.html) |
| Hero | Hero city night dengan skyline dan hujan | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/hero/hero-city-night.html) |
| Latar | Latar hutan pinus animasi (canvas + GSAP) | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/background/background-hutan-pinus.html) |
| Aksen | Ranting dan daun pinus melayang | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/accents/aksen-ranting-pinus.html) |
| Tombol | Efek magnet, ripple, dan tombol loading | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/buttons/tombol-gsap.html) |
| Komponen | Navbar, kartu, akordion, dan modal | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/components/komponen-navbar-kartu.html) |
| Teks | Teks per huruf, kata berganti, dan teks per kata | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/text/teks-per-huruf.html) |
| Scroll | Muncul saat terlihat, paralaks, dan bagian yang tertahan | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/scroll/scroll-reveal.html) |

> Tautan demo bekerja setelah GitHub Pages diaktifkan (lihat bagian "Menampilkan demo di GitHub Pages" di bawah).

## Daftar animasi

| Kategori | Contoh | Status |
|----------|--------|--------|
| Hero | Hero hutan pinus dengan latar blur | Tersedia |
| Hero | Hero high-tech dengan latar blur | Tersedia |
| Hero | Hero power supply | Tersedia |
| Hero | Hero electricity | Tersedia |
| Hero | Hero farm | Tersedia |
| Hero | Hero ocean | Tersedia |
| Hero | Hero city night | Tersedia |
| Latar | Latar hutan pinus animasi (canvas + GSAP) | Tersedia |
| Aksen | Ranting dan daun pinus melayang | Tersedia |
| Tombol | Efek magnet, ripple, dan tombol loading | Tersedia |
| Komponen | Navbar, kartu, akordion, dan modal | Tersedia |
| Teks | Teks per huruf, kata berganti, dan teks per kata | Tersedia |
| Scroll | Muncul saat terlihat, paralaks, dan bagian yang tertahan | Tersedia |

## Struktur folder

```
gsap-web-motion/
├── hero/
│   ├── hero-hutan-pinus.html
│   ├── hero-high-tech.html
│   ├── hero-power-supply.html
│   ├── hero-electricity.html
│   ├── hero-farm.html
│   ├── hero-ocean.html
│   └── hero-city-night.html
├── background/
│   └── background-hutan-pinus.html
├── accents/
│   └── aksen-ranting-pinus.html
├── buttons/
│   └── tombol-gsap.html
├── components/
│   └── komponen-navbar-kartu.html
├── text/
│   └── teks-per-huruf.html
├── scroll/
│   └── scroll-reveal.html
├── LICENSE
└── README.md
```

## Cara menjalankan

1. Clone repo ini:

   ```bash
   git clone https://github.com/verlunix-maker/gsap-web-motion.git
   ```

2. Buka file HTML di browser, misalnya `hero/hero-hutan-pinus.html`.

Tidak ada instalasi tambahan. GSAP dimuat dari CDN:

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
```

Contoh scroll juga memuat plugin ScrollTrigger:

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js"></script>
```

## Cara memakai di proyek Anda

1. Salin bagian HTML, CSS, atau JavaScript yang Anda butuhkan.
2. Pastikan library GSAP sudah dimuat sebelum script animasi.
3. Sesuaikan warna, teks, dan durasi dengan desain Anda. Nilai yang bisa diubah biasanya ada di bagian atas script atau di blok CSS.

## Menampilkan demo di GitHub Pages

1. Buka **Settings** repo, lalu pilih **Pages** di menu kiri.
2. Di bagian **Build and deployment**, pilih **Deploy from a branch**.
3. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
4. Tunggu beberapa menit, lalu tautan demo di atas akan aktif.

## Prinsip

- **Mandiri**: setiap contoh tidak bergantung pada file lain.
- **Ringan**: animasi memakai `transform` dan `opacity` agar tetap halus.
- **Responsif**: layout menyesuaikan lebar layar dan area aman perangkat (`safe-area-inset`).
- **Ramah aksesibilitas**: semua contoh menghormati `prefers-reduced-motion`. Pengguna yang mengaktifkan pengaturan ini akan melihat animasi berhenti atau langsung ke keadaan akhir.

## Kontribusi

Kontribusi sangat diterima. Untuk menambahkan animasi baru:

1. Buat file di folder kategori yang sesuai, dengan nama huruf kecil dan tanda hubung (misalnya `hero/hero-baru.html`).
2. Tambahkan komentar singkat di bagian atas file yang menjelaskan efeknya.
3. Perbarui tabel demo dan tabel daftar animasi di README ini.
4. Buat pull request dengan deskripsi singkat.

## Lisensi

Repo ini memakai lisensi MIT. Lihat berkas [LICENSE](LICENSE).

GSAP adalah milik GreenSock. Gunakan sesuai lisensinya, dokumentasi lengkap ada di <https://gsap.com/docs/v3/>.
