# Panduan langkah demi langkah SEO Dinda Restaurant

Domain: https://dindarestorant.bakmimuliajatiasih.my.id/
Repo: https://github.com/adindadwimulia/dindarestourant

## A. Deploy file SEO
1. Buka repo GitHub dan klik `Add file` → `Upload files`, atau ekstrak ZIP lalu unggah file ke root repo.
2. Tambahkan/replace `index.html`, `robots.txt`, `sitemap.xml`, `site.webmanifest`, dan folder `assets`.
3. Jangan menghapus `style.css` atau `script.js` yang sudah ada.
4. Klik `Commit changes`.
5. Tunggu hosting deploy, lalu cek:
   - https://dindarestorant.bakmimuliajatiasih.my.id/robots.txt
   - https://dindarestorant.bakmimuliajatiasih.my.id/sitemap.xml
   - https://dindarestorant.bakmimuliajatiasih.my.id/assets/og-image.jpg

## B. Daftarkan website di Google Search Console
1. Buka https://search.google.com/search-console/about lalu masuk dengan akun Google.
2. Klik tambah properti.
3. Pilihan **Domain** meminta verifikasi DNS TXT di pengelola DNS domain. Gunakan ini jika kamu punya akses mengatur DNS untuk `bakmimuliajatiasih.my.id`.
4. Jika kamu tidak punya akses DNS, pilih **URL prefix** dan masukkan URL persis: `https://dindarestorant.bakmimuliajatiasih.my.id/`. Pilih metode verifikasi yang ditawarkan Google, misalnya HTML tag atau file HTML. Kalau HTML tag, letakkan tag verifikasi di dalam `<head>` pada `index.html`, deploy ulang, lalu klik Verify. Jangan membagikan kode verifikasi ke orang lain.
5. Setelah properti berhasil diverifikasi, buka menu **Sitemaps**.
6. Isi `sitemap.xml`, lalu klik Submit.
7. Buka **URL Inspection**, masukkan `https://dindarestorant.bakmimuliajatiasih.my.id/`, klik Test Live URL bila tersedia, lalu Request Indexing.

Panduan resmi:
- Search Console: https://search.google.com/search-console/about
- Kirim sitemap: https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap
- Minta crawling ulang: https://developers.google.com/search/docs/crawling-indexing/ask-google-to-recrawl
- URL Inspection: https://support.google.com/webmasters/answer/9012289

## C. Periksa hasil teknis
- Buka https://search.google.com/test/rich-results dan masukkan URL untuk memeriksa data terstruktur yang didukung.
- Buka https://validator.schema.org/ untuk validasi JSON-LD.
- Setelah deploy, gunakan https://www.opengraph.xyz/ untuk melihat pratinjau Open Graph.
- Cek hasil Google dengan mencari `site:dindarestorant.bakmimuliajatiasih.my.id` beberapa hari/minggu kemudian.

## D. Isi SEO yang lebih kuat
- Tambahkan konten asli yang benar-benar menjelaskan lokasi, jenis makanan, kisaran harga, jam buka, metode reservasi, dan kontak. Jangan mengarang data bisnis.
- Pastikan nama restoran konsisten di website, profil bisnis, dan media sosial.
- Jika restoran melayani pelanggan di lokasi fisik dan memenuhi syarat, buat/kelola Google Business Profile: https://www.google.com/business/ . Gunakan alamat dan kategori bisnis yang akurat.
- Jika belum memiliki halaman menu terpisah, jangan membuat URL palsu di sitemap. Anchor seperti `#menu` tetap bagian dari satu halaman.
- Periksa performa mobile, kecepatan, dan keterbacaan: https://pagespeed.web.dev/ .

## E. Catatan penting
- Google tidak menjamin halaman akan diindeks atau muncul di posisi tertentu. Proses dapat memakan beberapa hari hingga beberapa minggu.
- Sitemap membantu Google menemukan URL, tetapi tidak memaksa Google mengindeksnya.
- `robots.txt` bukan alat untuk menyembunyikan informasi rahasia.
