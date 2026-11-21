# Proyek Lab Pemrograman: Validasi Product-Market Fit (Uji 5 Produk)

Repositori ini memuat implementasi tahap awal proyek Lab Pemrograman: konfigurasi AI Harness lokal, katalog 5 kandidat produk digital kampus beserta masing-masing *landing page*-nya, serta instrumen pelacakan *traffic* dan klik minat (*smoke test*) sebelum tahap pemasaran dieksekusi.

## 1. Anggota Kelompok
- Lufthansa Daffa Gilbran (12010223140054)
- Ghiffari Muhammad (12010223140015)
- Farrel Eksa (12010223140014)
- Muhammad Indra (12010223140067)
- Nayla Raihanda (12010223140005)

**Program Studi S1 Bisnis Digital, Fakultas Ekonomika dan Bisnis, Universitas Diponegoro**

---

## 2. Status & Progres Pengerjaan

### A. Konfigurasi AI Harness Lokal (`AGENTS.md`)
- Menyiapkan file panduan agen lokal (`AGENTS.md`) di direktori proyek.
- Menetapkan batasan teknis: arsitektur berbasis HTML5, TailwindCSS, dan Vanilla JS tanpa dependensi berat.
- Menerapkan aturan kepatuhan data: tidak menyimpan kredensial atau API Key pada repositori publik dan menjaga data pengujian tetap anonim.

### B. Pembuatan Landing Page untuk 5 Ide Produk (Uji Minat Pasar)
Kelima kandidat ide bisnis telah berhasil dikembangkan menjadi halaman *landing page* masing-masing yang siap diuji minat pasarnya:
1. **P1 — Cathering Protein**
2. **P2 — KlinKicks**
3. **P3 — OtomasiNusa**
4. **P4 — Padelora**
5. **P5 — TemcyLens**

### C. Instrumen Pelacakan Minat & Traffic (`index.html`)
- **Deteksi Sumber Traffic:** Membaca parameter URL (`utm_source` dan `utm_campaign`) untuk memetakan efektivitas saluran distribusi promosi (WhatsApp grup, Instagram Story, TikTok).
- **Pencatatan Konversi (CTR):** Menghitung total kunjungan (*pageviews*), jumlah klik per produk, dan rasio minat (*Click-Through Rate*) secara otomatis melalui penyimpanan lokal (*local storage*).
- **Dasbor Metrik:** Tabel evaluasi langsung pada halaman untuk menentukan produk dengan performa minat tertinggi sebagai dasar validasi sebelum masuk ke tahap pengembangan aplikasi penuh.

---

## 3. Rencana Langkah Berikutnya
1. Melakukan *deployment* halaman katalog dan *landing page* ke platform hosting statis (GitHub Pages / Cloudflare Pages).
2. Menjalankan kampanye pemasaran terarah pada saluran komunitas mahasiswa menggunakan tautan berparameter UTM.
3. Menganalisis metrik konversi klik untuk memilih satu produk final yang terbukti memiliki kebutuhan pasar tertinggi.

---

## 4. Deskripsi Masing-Masing Produk Bisnis

### 1. Cathering Protein
Layanan katering harian khusus menu tinggi protein (*high-protein meal prep*) dengan takaran gizi dan kalori yang terukur. Dirancang untuk mahasiswa, anak kos, maupun pegiat kebugaran di sekitar kampus yang ingin menjaga pola makan sehat, praktis, dan terjangkau tanpa perlu repot memasak sendiri.

### 2. KlinKicks
Jasa perawatan dan cuci sepatu profesional (*shoe care & cleaning*) dengan layanan antar-jemput praktis di area kos dan kampus Tembalang. Menawarkan berbagai paket perawatan mulai dari *fast cleaning*, *deep cleaning*, hingga *unyellowing* dengan pengerjaan cepat dan transparan bagi mahasiswa dengan mobilitas tinggi.

### 3. OtomasiNusa
Platform penyedia solusi digitalisasi bisnis berupa pembuatan *landing page* profesional dan sistem otomasi administrasi untuk pelaku UMKM. Membantu pemilik usaha merapikan alur pemesanan, balas pesan pelanggan otomatis, serta meningkatkan konversi penjualan secara efisien tanpa perlu keahlian teknis.

### 4. Padelora
Platform pemesanan lapangan padel (*court booking*), penyewaan perlengkapan raket, serta penghubung komunitas olahraga padel (*open match / sparring*). Memudahkan pemain pemula maupun rutin untuk mencari jadwal lapangan kosong dan menemukan teman bermain secara instan.

### 5. TemcyLens
Layanan *Self-Photo Studio* privat berbasis *remote shutter* dan penyewaan kamera (*mirrorless* maupun kamera instan) yang berlokasi strategis di kawasan Tembalang, dekat kampus UNDIP Semarang. Menawarkan konsep studio anti-canggung dan paket sewa peralatan fotografi berkualitas dengan tarif ramah kantong mahasiswa.