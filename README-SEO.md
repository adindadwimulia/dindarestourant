# Dinda Restaurant — SEO files

Paket ini berisi versi `index.html` dengan metadata SEO dasar dan file pendukung untuk domain:
https://dindarestorant.bakmimuliajatiasih.my.id/

## Isi
- `index.html`: title, description, canonical, Open Graph, Twitter Card, JSON-LD Restaurant, alt text, labels aksesibilitas, dan lazy loading gambar bagian bawah.
- `robots.txt`: mengizinkan crawler dan menunjukkan sitemap.
- `sitemap.xml`: sitemap untuk landing page satu halaman.
- `assets/og-image.jpg`: gambar preview ketika URL dibagikan.
- `assets/favicon.svg`, `favicon-32.png`, `favicon-192.png`, `favicon-512.png`, `apple-touch-icon.png`: ikon situs.
- `site.webmanifest`: metadata ikon untuk perangkat.

## Cara pakai
1. Unduh ZIP, ekstrak.
2. Buat backup repo saat ini terlebih dahulu.
3. Upload/replace `index.html`, `robots.txt`, `sitemap.xml`, `site.webmanifest`, dan folder `assets/` ke root repo GitHub (sejajar dengan `style.css` dan `script.js`).
4. Pastikan `style.css` dan `script.js` dari repo yang sekarang tetap ada. Jangan hapus keduanya.
5. Commit perubahan dan tunggu proses deploy hosting selesai.
6. Uji URL ini di browser:
   - `/robots.txt`
   - `/sitemap.xml`
   - `/assets/og-image.jpg`
   - `/assets/favicon.svg`
7. Ikuti `PANDUAN-SEO.md` untuk Search Console.

## Penting
- Paket menggunakan URL domain yang diberikan. Jika domain utama diganti, perbarui canonical, sitemap, Open Graph, Twitter image, dan JSON-LD di `index.html` serta `robots.txt`.
- Schema hanya memakai data yang sudah tersedia; jangan menambahkan alamat, jam buka, rating, atau klaim lain sebelum datanya benar-benar dipastikan.
- Halaman ini tetap berupa landing page satu URL, jadi sitemap hanya memuat homepage.
- Pastikan `style.css` dan `script.js` di repo sama dengan versi saat ini karena paket ini tidak dimaksudkan menggantikan file tersebut.

Catatan kompatibilitas: referensi eksternal `silverhawk.web.id/lock/lock.css` dan `lock.js` dari repo asli tetap dipertahankan bersama atribut data-shlock pada body. Jika layanan tersebut bukan milikmu atau kamu tidak mengenali fungsinya, tinjau dulu sebelum menghapusnya; penghapusan dapat mengubah perilaku situs.
