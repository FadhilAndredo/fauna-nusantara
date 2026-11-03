FAUNA NUSANTARA — https://fadhilandredo.github.io/fauna-nusantara/

ISI PAKET
- home.html, peta.html, asiatis.html, peralihan.html, australis.html
- site.css dan site.js
- assets/indonesia-fauna-hero.webp
- assets/fauna-zona-asiatis.webp, fauna-zona-peralihan.webp, fauna-zona-australis.webp
- assets/cursors/*.png (ikon kursor hewan)
- MAP-SOURCE.txt (catatan sumber dan batas penggunaan peta)

PEMASANGAN
1. Ekstrak seluruh isi ZIP.
2. Letakkan file HTML, site.css, site.js, dan folder assets dalam satu folder proyek.
3. Pertahankan folder images dari proyek lama. Foto fauna dan peta persebaran individual pada tabel masih mengambil file dari folder images tersebut.
4. Buka home.html melalui browser.

FITUR VERSI 4
- Semua fitur versi 3 tetap dipertahankan.
- Halaman peta dibangun ulang dengan garis pantai kepulauan yang diambil dari data GSHHS resolusi intermediate, bukan siluet pulau dekoratif.
- Peta memuat bentuk dan gugusan pulau utama serta banyak pulau kecil, label pulau/wilayah, koordinat, garis graticule, nama perairan, dan penunjuk arah utara.
- Pewarnaan zona diperbaiki berdasarkan gugusan geografis: Asiatis mencakup Sumatra, Jawa, Bali, dan Kalimantan; Peralihan mencakup Sulawesi, Nusa Tenggara, serta sebagian besar Maluku; Australis mencakup Papua dan Kepulauan Aru.
- Garis Wallace ditampilkan merah solid dari Selat Lombok menuju Selat Makassar. Garis Weber ditampilkan ungu putus-putus dan melewati kawasan Kepulauan Tanimbar.
- Kedua garis diberi label dan legenda tersendiri dengan kontras lebih jelas.
- Gugusan pulau pada masing-masing zona dapat di-hover, difokuskan dengan keyboard, atau diklik untuk menuju halaman zona. Pada HP peta dapat digeser mendatar dan tetap tersedia tombol pilihan zona.
- Snapshot halaman peta yang dipakai navigasi SPA pada site.js diperbarui agar tampilan yang dibuka dari Beranda sama dengan peta.html.

CATATAN AKURASI PETA
- Garis pantai bersumber dari GSHHS (Global Self-consistent, Hierarchical, High-resolution Geography Database) resolusi intermediate yang tersedia bersama Matplotlib Basemap. Detailnya lebih baik daripada skema poligon, tetapi bukan data garis pantai BIG skala 1:25.000 dan bukan peta navigasi.
- Pembagian warna zona pada pulau-pulau kecil merupakan klasifikasi edukasi berdasarkan gugusan wilayah. Batas fauna di alam bersifat biogeografis dan tidak sama dengan batas administrasi.
- Garis Wallace dan Weber merupakan garis biogeografi imajiner. Jalurnya digambarkan secara skematis untuk pembelajaran, bukan koordinat survei atau penetapan batas resmi.

SUMBER PETA DAN RUJUKAN GARIS
- NOAA/NCEI, Shoreline / Coastline Resources — GSHHG: https://www.ngdc.noaa.gov/mgg/shorelines/shorelines.html
- Modul IPS SMP, Unit 3 — Garis Wallace dari Selat Lombok ke Selat Makassar: https://www.pintar.tanotofoundation.org/wp-content/uploads/2021/09/Modul-II-IPS-SMP-MTs.pdf
- Kompas, “Garis Weber, Garis Wallace, dan Garis Lydekker” — keterangan Garis Weber melalui Kepulauan Tanimbar: https://www.kompas.com/skola/read/2020/03/28/080000469/garis-weber-garis-wallace-dan-garis-lydekker
- Bappenas/KLHK/LIPI, Indonesian Biodiversity Strategy and Action Plan 2015–2020, Gambar 3.2: https://ksdae.kehutanan.go.id/assets/publikasi/Buku_IBSAP%202015-2020.pdf

MUSIK VERSI 5
Empat komposisi instrumental orisinal dibuat secara sintetis untuk paket ini:
- Beranda/Peta versi 5: Rimba Senja (diganti lagu awal pada versi 6)
- Asiatis: Bisik Kanopi
- Peralihan: Angin Wallacea
- Australis: Fajar Papua
Melodi pentatonik lembut, pad hangat, tekstur angin dan kicau sintetis. Semua MP3 disertakan lokal; tidak memerlukan internet. Musik mencoba autoplay saat dibuka. Browser dapat menahan autoplay bersuara: klik/ketuk halaman atau tekan tombol putar untuk memulai. Tombol jeda dan volume tetap tersedia. Lagu berganti sesuai zona, dan pilihan jeda dihormati selama navigasi internal. Saat muat ulang, musik dicoba otomatis lagi.

PERUBAHAN VERSI 5
- Urutan beranda: hero, kartu konsep buka-tutup, panduan belajar, jelajah fauna.
- Enam ilustrasi hewan realistis buatan AI dipotong menjadi stiker WebP transparan. Stiker dan fakta melayang lembut pada desktop. Di ponsel, isi ditata vertikal agar mudah dibaca. Preferensi kurangi gerakan didukung.
- Huruf isi 18px desktop, tabel lebih lapang dan kontras, klasifikasi dapat dibuka. Ponsel menggunakan kartu per satwa dengan label bagian.
- Foto fauna dan peta individual dari folder images proyek lama TIDAK disertakan dalam ZIP sumber. Salin folder images tersebut ke samping home.html bila tersedia. Jika tidak, penanda teks ditampilkan sebagai pengganti gambar yang hilang.
- Isi materi dan peta warisan versi 4 dipertahankan; versi ini berfokus pada tampilan, interaksi, dan audio, bukan audit ilmiah isi ensiklopedia.
- Semua salinan halaman offline di site.js disinkronkan dengan HTML.

CARA MENJALANKAN
Ekstrak seluruh ZIP lalu buka home.html atau index.html. Jangan membuka HTML langsung dari tampilan isi ZIP. Untuk memasang di hosting statis, unggah seluruh isi folder fauna-sekolah-refresh.

PERUBAHAN VERSI 6
- Lagu awal “Epic at the Jungle” — Indieteur, CC0 1.0 — dikembalikan untuk Beranda dan Peta. File audio dari sumber ZIP awal (https://nullrights.com/download/x2zy8up903) kini disertakan lokal sebagai assets/audio/epic-at-the-jungle.mp3.
- Pengaturan suara memiliki pemilih lagu: otomatis sesuai halaman atau salah satu dari lima lagu. Pilihan manual disimpan di browser dan berlaku lintas halaman. Kembali ke otomatis untuk memakai lagu bawaan tiap zona.
- Bagian jelajah berisi 12 stiker transparan dan 12 fakta singkat dalam kelompok Asiatis, Peralihan, dan Australis. Stiker bergerak lembut dengan kartu fakta yang tertata. Gerakan mengikuti preferensi kurangi gerakan.
- Tautan langsung dari bagian jelajah ke halaman satwa dihapus. Kedua tombol jelajah mengarah ke peta.
- Fitur, ensiklopedia, kartu konsep, dan peta lainnya dipertahankan dari versi 5.
