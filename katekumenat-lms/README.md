# Katekumenat LMS — Materi Web Interaktif (EDU-PK-001 V4.0)

**Status:** Materi web diunggah dan diverifikasi pada branch `feature/katekumenat-lms`; **belum dipublikasikan melalui GitHub Pages**.

## Struktur
- `index.html` — katalog enam bulan
- `bulan-1/index.html` hingga `bulan-6/index.html` — enam modul interaktif, total 24 materi mingguan

Semua materi dapat diakses sejak awal. Kuis dan tugas bulanan dikerjakan dan dinilai terpisah melalui ASAG 2.0. Progres baca di halaman web hanya tersimpan pada browser lokal, tidak masuk ke Gradebook ASAG.

## Menghubungkan dengan ASAG
1. Publikasikan folder ini di hosting statis HTTPS.
2. Pada course Katekumenat di ASAG, tambahkan materi berbentuk tautan eksternal.
3. Tempel URL katalog atau URL tiap folder bulan.
4. Uji menggunakan akun siswa pada desktop dan ponsel.

## Catatan deployment
Repository induk `anasius-nyoba/anasius-nyoba.github.io` mempunyai file `CNAME` yang mengarah ke domain parokikedaton.me. Karena itu materi ditempatkan **di branch terpisah, bukan di main**. Jangan menggabungkan branch ini ke main tanpa meninjau konsekuensi publikasi pada domain terkait.

Untuk hosting terpisah, buat repository publik `katekumenat-lms`, salin ketujuh halaman ke root repo baru, kemudian atur GitHub Pages dari branch main/root. URL Pages umumnya `https://anasius-nyoba.github.io/katekumenat-lms/`, bergantung pada pengaturan akun dan domain.

## Paket SCORM
File ZIP SCORM 1.2 disiapkan terpisah dari versi web ini. Penggunaan URL ASAG bukan integrasi SCORM Runtime.
