# Media UDL — E-book Interaktif

**Panduan Kilat: Desain Media Pembelajaran Inklusif** — e-book interaktif 9 halaman
berbasis prinsip UDL (Universal Design for Learning), disarikan dari materi
*Inclusive EdTech Design Bootcamp for Special Educators*, Universitas Negeri Malang 2026.

## Buka e-book

https://anasysuf.github.io/media-udl/

## Isi

1. Sampul & cara pakai
2. Apa itu media pembelajaran inklusif
3. Kenapa inklusi penting
4. Tiga prinsip UDL
5. Perceivable (dapat dipersepsi)
6. Operable (dapat dioperasikan)
7. Understandable (mudah dipahami)
8. Robust (tangguh)
9. Kuis interaktif (3 pertanyaan)

## Fitur aksesibilitas

- Toolbar aksesibilitas **AksesKita** (karya sendiri, open source): profil 1-klik,
  6 tingkat ukuran teks, 7 skema kontras, alat bantu visual, screen reader & TTS —
  tombol melayang ♿ atau tekan Alt+A. Divendor lokal di `vendor/` agar tetap
  jalan saat internet lambat. Untuk mendengarkan halaman, pakai fitur
  TTS/pembaca layar di dalam panel AksesKita.
- Navigasi keyboard (panah kiri/kanan, Home, End), skip link, live regions
- Responsif untuk HP dan laptop

## Struktur

- `index.html` — seluruh e-book dalam satu file
- `vendor/akseskita.min.js` — widget aksesibilitas AksesKita (disalin lokal,
  https://github.com/anasysuf/akseskita)

## Lisensi

Bebas dibagikan untuk keperluan pembelajaran.
Materi: Muhammad Anas Yusuf.
