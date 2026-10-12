# GSAP Web Motion

Koleksi animasi GSAP siap pakai untuk membuat website lebih hidup. Setiap contoh berdiri sendiri dalam satu file HTML, sehingga bisa langsung dibuka di browser atau disalin ke proyek Anda.

## Demo

Setiap contoh bisa dilihat langsung di browser:

| Contoh | Demo |
|--------|------|
| Hero hutan pinus dengan latar blur | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/hero/hero-hutan-pinus.html) |
| Hero high-tech dengan latar blur | [Buka demo](https://verlunix-maker.github.io/gsap-web-motion/hero/hero-high-tech.html) |

> Tautan demo bekerja setelah GitHub Pages diaktifkan (lihat bagian "Menampilkan demo di GitHub Pages" di bawah).

## Daftar animasi

| Kategori | Contoh                                    | Status   |
|----------|-------------------------------------------|----------|
| Hero     | Hero hutan pinus dengan latar blur        | Tersedia |
| Hero     | Hero high-tech dengan latar blur          | Tersedia |
| Latar    | Latar hutan pinus animasi (canvas + GSAP) | Rencana  |
| Aksen    | Ranting dan daun pinus melayang           | Rencana  |
| Tombol   | Tombol hover, klik, dan loading           | Rencana  |
| Komponen | Kartu, navbar, accordion, modal           | Rencana  |
| Teks     | Teks muncul per huruf dan per kata        | Rencana  |
| Scroll   | Animasi saat elemen masuk layar           | Rencana  |

## Struktur folder

```
gsap-web-motion/
├── hero/
│   ├── hero-hutan-pinus.html
│   └── hero-high-tech.html
├── background/
├── accents/
├── buttons/
├── components/
├── text/
├── scroll/
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

## Cara memakai di proyek Anda

1. Salin bagian HTML, CSS, atau JavaScript yang Anda butuhkan.
2. Pastikan library GSAP sudah dimuat sebelum script animasi.
3. Sesuaikan warna, teks, dan durasi dengan desain Anda. Nilai yang bisa diubah biasanya ada di bagian atas script atau di blok `:root` pada CSS.

## Menampilkan demo di GitHub Pages

1. Buka **Settings** repo, lalu pilih **Pages** di menu kiri.
2. Di bagian **Build and deployment**, pilih **Deploy from a branch**.
3. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
4. Tunggu beberapa menit, lalu tautan demo di atas akan aktif.

## Prinsip

- **Mandiri**: setiap contoh tidak bergantung pada file lain.
- **Ringan**: animasi memakai `transform` dan `opacity` agar tetap halus.
- **Responsif**: layout menyesuaikan lebar layar dan area aman perangkat (`safe-area-inset`).
- **Ramah aksesibilitas**: teks alternatif untuk elemen dekoratif dan dukungan untuk pengguna yang mengaktifkan `prefers-reduced-motion` (direncanakan).

## Kontribusi

Kontribusi sangat diterima. Untuk menambahkan animasi baru:

1. Buat file di folder kategori yang sesuai, dengan nama huruf kecil dan tanda hubung (misalnya `hero/hero-baru.html`).
2. Tambahkan komentar singkat di bagian atas file yang menjelaskan efeknya.
3. Perbarui tabel demo dan tabel daftar animasi di README ini.
4. Buat pull request dengan deskripsi singkat.

## Lisensi

Repo ini memakai lisensi MIT. Lihat berkas [LICENSE](LICENSE).

GSAP adalah milik GreenSock. Gunakan sesuai lisensinya, dokumentasi lengkap ada di <https://gsap.com/docs/v3/>.
