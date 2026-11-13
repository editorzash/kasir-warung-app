# Kasir Warung — Aplikasi POS Cepat, Nyata & Ringan untuk Kedai & Warung

Aplikasi kasir web modern (*Single-File Web App*) bernuansa **Teal (`#0f766e`) & Warm Stone (`#f5f5f4`)** yang dirancang khusus untuk menjawab alur operasional nyata warung makan, kedai kopi, warkop, dan gerai UMKM di Indonesia — cukup buka satu file `index.html` tanpa build tool apa pun.

---

## 🌟 Fitur Utama (Versi 2 — Realistis & Taktil)

1. **Satu File Siap Pakai (`index.html`)**:
   - Berjalan murni menggunakan HTML5, CSS3, dan Vanilla JavaScript (ES6+) dalam satu file mandiri.
   - Kompatibel dibuka langsung lewat protokol `file://` maupun di-host di GitHub Pages / web server statis.

2. **Katalog Menu Foto Nyata & Filter Kategori**:
   - Pilihan filter kategori cepat (`Semua`, `Makanan`, `Gorengan`, `Minuman`) dan pencarian instan.
   - Kartu produk dilengkapi foto hidangan dengan *fallback* ikon otomatis apabila perangkat sedang luring (*offline*), serta badge jumlah pesanan langsung pada kartu.

3. **Antrean Multi-Nota Terbuka (*Open Bills Queue*) & Timer Langsung**:
   - Kelola banyak meja/pelanggan sekaligus (`+ Nota baru` -> `#1`, `#2`, `#3`...) lengkap dengan indikator durasi waktu nota terbuka secara *real-time* dan jam WIB langsung di bilah atas.
   - Mendukung mode pesanan **Makan Sini** dan **Bungkus**.

4. **Penanda Ciri Warna Pelanggan (*Color Traits*) & Catatan**:
   - Tanpa perlu selalu menanyakan nama, kasir cukup menandai pelanggan dengan 6 ciri warna (**Merah**, **Biru**, **Hijau**, **Kuning**, **Hitam**, **Putih**) berdasarkan warna baju atau area meja, plus kolom catatan pelanggan/meja opsional.

5. **3 Metode Pembayaran Nyata (Tunai, QRIS Dinamis & Kasbon)**:
   - **Tunai**: Kalkulator kembalian otomatis dengan tombol pecahan cepat.
   - **QRIS**: Tampilan QRIS Dinamis SVG yang siap dipindai untuk pembayaran nontunai.
   - **Kasbon**: Pencatatan utang pelanggan warung (nama & nomor WhatsApp) yang tersimpan ke tab **Buku Kasbon** lengkap dengan lencana indikator di header dan tombol pelunasan di kemudian hari.

6. **Struk Thermal 58mm & Kirim Nota WhatsApp**:
   - Pratinjau struk bergaya kertas thermal **58mm** dengan dukungan cetak langsung (`@media print`).
   - Tombol kirim ringkasan struk melalui **WhatsApp** serta akses buka ulang struk dari riwayat transaksi.

7. **Efek Suara Web Audio API (*Tactile SFX*)**:
   - Umpan balik audio sintetis (tanpa file audio eksternal) saat mengetuk menu, menghapus item, atau menyelesaikan pembayaran, dengan tombol bisu/aktifkan suara di bilah atas.

8. **Rekap Harian, Top Seller, Editor Menu & Cadangan JSON**:
   - Ringkasan omzet harian, jumlah nota, rata-rata transaksi, **Menu Terlaris (Top Seller)**, tab **Buku Kasbon**, serta unduh cadangan data ke JSON.
   - Kelola menu, kategori, dan harga rupiah secara terpadu, serta atur profil nama/alamat warung dan nama kasir.
   - Dialog konfirmasi kustom di dalam aplikasi (tanpa popup `alert()`/`confirm()` bawaan browser) dan panel nota *collapsible drawer* pada tampilan layar ponsel.

9. **Penyimpanan Lokal & Migrasi Otomatis (`localStorage`)**:
   - Menggunakan kunci `kw_menu_v2` (dengan migrasi otomatis dari `kw_menu_v1`), `kw_open_notes_v1`, `kw_history_v1`, `kw_kasbon_v1`, dan `kw_meta_v1`.

---

## 🚀 Cara Menjalankan

1. Jalankan lewat halaman login di [`../form_login_kasir-warung-app/index.html`](../form_login_kasir-warung-app/index.html), atau
2. Buka langsung file [`./index.html`](./index.html) di peramban web (*Chrome, Edge, Safari, Firefox*) pada laptop, tablet, maupun ponsel.
