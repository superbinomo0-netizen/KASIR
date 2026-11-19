# Kasir POS - BERKAH FOTOCOPY

Aplikasi kasir berbasis web (HTML, Tailwind CSS, JavaScript, `localStorage`, dan PWA) untuk **BERKAH FOTOCOPY** (`JL. Serang, pertigaan pasar gorda`).

## Struktur File di Folder Utama (Root)
- `index.html` — Aplikasi utama POS, manajemen produk/kategori/stok, profil kasir & nomor HP, struk cetak/PNG/WhatsApp, laporan & pengeluaran manual (Gaji & Lain-lain), serta ekspor/impor JSON.
- `manifest.json` — Konfigurasi PWA untuk pemasangan di layar utama HP.
- `sw.js` — Service worker untuk caching aset lokal aplikasi.

## Cara Upload & Aktifkan GitHub Pages
1. Upload ketiga file (`index.html`, `manifest.json`, dan `sw.js`) ke folder *root* repositori GitHub.
2. Buka tab **Settings** pada repositori &rarr; pilih **Pages** di menu kiri.
3. Pada bagian **Build and deployment / Branch**, pilih cabang **`main`** dan folder **`/ (root)`**, lalu klik **Save**.
4. Tunggu sekitar 1–2 menit hingga tautan `https://<username>.github.io/<nama-repo>/` aktif.
5. Buka tautan tersebut di browser HP (Chrome/Safari) lalu pilih **Tambahkan ke Layar Utama** / **Add to Home Screen**.
