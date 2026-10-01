# Vilza VVIP Rental Transport

Dashboard rental transport dan akuntansi persediaan berbasis HTML/CSS/JavaScript + Supabase REST API.

## GitHub Pages

Struktur root sudah disiapkan untuk GitHub Pages. Pastikan repository menggunakan:

- Branch: `main`
- Folder: `/ (root)`

Lalu buka **Settings → Pages**.

## Supabase

Konfigurasi koneksi berada di `backend/app.js`. Gunakan hanya publishable key (`sb_publishable_...`) di frontend. Jangan masukkan secret/service-role key ke repository.

> Catatan: `backend/app.js` adalah helper REST yang berjalan di browser, bukan server Node.js.
