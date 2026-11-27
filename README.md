# Praktikum Data Science — Evaluasi Model & Hyperparameter Tuning

Modul interaktif berbahasa Indonesia, mengikuti sembilan slide PPT praktikum yang diberikan. Dibangun menggunakan HTML, CSS, dan JavaScript vanilla. Tidak perlu instalasi, CDN, database, API, maupun proses build.

## Menjalankan / deploy

- Ekstrak ZIP. Buka `index.html` di browser untuk penggunaan offline.
- Untuk GitHub Pages, unggah `index.html`, `style.css`, dan `app.js` ke root repositori. Aktifkan Pages dari branch yang memuat ketiga file.
- Untuk Netlify atau hosting statis lain, unggah folder hasil ekstraksi sebagai direktori publik (index.html berada di root). Tidak ada build command.

Navigasi melalui daftar materi, tombol Sebelumnya/Lanjut, atau panah kiri/kanan saat fokus tidak berada pada kontrol. Mode layar penuh tersedia jika browser mendukungnya. Setiap simulasi kembali ke kondisi awal ketika membuka ulang slide.

## Dasar materi

Sumber: PPT “MODEL EVALUASI & HYPER PARAMETER TUNING”, 9 slide. Nilai 800/200, 5 fold, confusion matrix, nilai UTS, serta tabel bias–variance dipertahankan. Grafik k-NN (dua fitur yang dinormalisasi), skor threshold, ROC-AUC, dan skor pencarian hyperparameter adalah ilustrasi tambahan, bukan hasil eksperimen dataset asli. Simulasi Bayesian menggunakan Gaussian process kecil dengan kernel RBF dan UCB pada enam kombinasi ilustratif. Tidak melatih model k-NN pada dataset mahasiswa asli karena dataset tidak disertakan. Precision tidak selalu naik ketika threshold dinaikkan; penjelasan ini memperjelas penyederhanaan pada PPT.

## Desain

Identitas biru diambil dari PPT, ditransformasikan menjadi modul kelas dengan tipografi sistem, navigasi berurutan, grafik fungsional, warna risiko/aman yang dilengkapi label, kontrol keyboard, dan layout responsif. Panduan anti-slop digunakan sebagai filter desain, tanpa memasang plugin atau dependensi.
