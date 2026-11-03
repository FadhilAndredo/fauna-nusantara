FAUNA NUSANTARA — WEBSITE REFRESH VERSI 4

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

SUMBER MUSIK
“Epic at the Jungle” — Indieteur, OpenGameArt.org, lisensi CC0 1.0 (atribusi tidak wajib; dicantumkan sebagai apresiasi). Audio memerlukan koneksi internet dan bergantung pada ketersediaan host sumber.
