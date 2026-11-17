# Money Journal — Neo Brutalist Edition

Website pencatatan pemasukan dan pengeluaran pribadi dengan arah visual neo-brutalist editorial yang lebih tenang: kertas krem, tinta hitam, hijau sage, dan aksen tanah.

## Fitur
- Dashboard harian dan ringkasan bulanan yang dapat dipilih (bulan sebelumnya/berikutnya).
- Total pemasukan, pengeluaran, selisih, dan jumlah catatan per bulan.
- Statistik dengan laporan bulan terpilih dan perbandingan enam bulan di sekitar bulan tersebut.
- Tambah, edit, hapus, cari, dan filter transaksi.
- Tanggal/waktu transaksi dapat diatur mundur.
- Data disimpan lokal di browser melalui IndexedDB.
- Backup dan restore JSON.
- PWA manifest dan service worker untuk pemasangan di layar utama dan cache offline.

## Jalankan di komputer
Untuk melihat halaman: buka `index.html` di browser. Untuk mencoba service worker/PWA, jalankan server lokal:

```bash
python -m http.server 8080
```

Lalu buka `http://localhost:8080`.

## Pasang di HP
Unggah semua isi folder ini ke hosting static dengan HTTPS (misalnya Netlify, Vercel, atau GitHub Pages). Jangan hanya mengunggah `index.html`; sertakan juga `manifest.json`, `sw.js`, dan folder `icons`.

- Android: buka URL di Chrome → menu ⋮ → Instal aplikasi / Tambahkan ke layar utama.
- iPhone: buka URL di Safari → Bagikan → Add to Home Screen.

## Tentang data
Data transaksi tersimpan pada browser dan perangkat tempat transaksi dicatat. Tidak ada akun, backend, atau sinkronisasi otomatis. Backup data sebelum berganti perangkat atau membersihkan data browser. Selisih pemasukan dan pengeluaran bukan saldo atau sisa uang.
