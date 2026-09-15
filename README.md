# VSEPR Geometry Explorer

Paket ini siap dipublikasikan menggunakan **GitHub Pages**.

## Struktur file

- `index.html` — aplikasi utama VSEPR interaktif.
- `.nojekyll` — memastikan GitHub Pages menyajikan file statis apa adanya.
- `README.md` — petunjuk deployment.

## Cara publish ke GitHub Pages

1. Buat repository baru di GitHub, misalnya `vsepr-explorer`.
2. Upload seluruh isi folder ini ke root repository.
3. Buka **Settings** → **Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`.
6. Klik **Save**.
7. Setelah deployment selesai, situs biasanya tersedia di:
   `https://USERNAME.github.io/vsepr-explorer/`

## Catatan

Aplikasi ini tidak memerlukan server, database, npm, framework, atau CDN. Seluruh HTML, CSS, dan JavaScript berada di dalam `index.html`, sehingga cocok untuk GitHub Pages.
