# Statistik Skripsi

Web client-side untuk membantu mahasiswa prodi kependidikan melakukan analisis data statistik dasar dari CSV/Excel.

## Fitur MVP
- Upload `.csv`, `.xls`, `.xlsx`
- Preview data dan deteksi variabel numerik
- Statistik deskriptif
- Histogram
- Uji normalitas pendekatan Shapiro-Wilk
- Independent samples t-test (Welch)
- Paired samples t-test
- Korelasi Pearson
- Regresi linear sederhana
- Grafik
- Rekomendasi analisis berdasarkan tujuan
- Draf narasi hasil
- Unduh laporan TXT
- Tidak membutuhkan backend/database

## Menjalankan
Cukup buka `index.html` atau deploy folder ini ke GitHub Pages.

## GitHub Pages
1. Buat repository, misalnya `statistik-skripsi`.
2. Upload `index.html`, folder `css`, `js`, dan `README.md`.
3. Settings → Pages → Deploy from branch → pilih `main` dan `/root`.
4. Simpan; GitHub akan memberikan URL Pages.

## Catatan metodologis
Hasil aplikasi harus diverifikasi dengan desain penelitian, asumsi, pedoman kampus, dan software statistik tervalidasi sebelum digunakan sebagai hasil final skripsi. Implementasi normalitas di MVP merupakan pendekatan client-side dan sebaiknya ditingkatkan pada versi produksi.

## Dependensi CDN
- SheetJS
- jStat
- Chart.js
