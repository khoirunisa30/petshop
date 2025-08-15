# dspetshop — Static Website

Tech: HTML + CSS + JavaScript (no build step).  
Color scheme: biru & ungu (sky blue & indigo).

## Fitur
- Slider produk terlaris (maks 5)
- Tambah ke keranjang (localStorage)
- Keranjang belanja & tombol Checkout (demo alert)
- Testimoni pelanggan + form tambah testimoni (localStorage)
- Form Kritik & Saran (pratinjau data)
- Alamat klinik: Jalan Wibisana 36, Jakarta
- Responsif, UI modern

## Struktur Folder
```
dspetshop-site/
├─ index.html
├─ assets/
│  ├─ css/
│  │  └─ styles.css
│  ├─ js/
│  │  └─ app.js
│  └─ img/
│     ├─ logo.svg
│     ├─ hero-pet.svg
│     ├─ pin.svg
│     ├─ prod-dogfood.svg
│     ├─ prod-cat-toy.svg
│     ├─ prod-scissor.svg
│     ├─ prod-bed.svg
│     └─ prod-leash.svg
└─ README.md
```

## Deploy ke GitHub Pages
1. Buat repo baru, misal `dspetshop`.
2. Upload semua file/folder ini ke repo (atau upload ZIP lalu `Extract` via GitHub web).
3. Buka **Settings → Pages**.
4. Pada **Source**, pilih `Deploy from a branch`.  
   Branch: `main`, Folder: `/ (root)` → Save.
5. Tunggu proses build, situs akan tersedia di `https://<username>.github.io/dspetshop/`.

> Catatan: Fitur checkout bersifat demo (alert). Keranjang & testimoni tersimpan di browser pengunjung (localStorage).
