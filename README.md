# Daily Dev Log

Repository ini digunakan sebagai jurnal aktivitas development harian.

Setiap hari, GitHub Actions akan menjalankan workflow otomatis untuk membuat atau memperbarui catatan aktivitas pada folder `daily/`.

## Fungsi

Repository ini dibuat untuk:

- Mencatat aktivitas development setiap hari
- Menyimpan progress project secara terstruktur
- Membuat riwayat perubahan yang mudah dilihat melalui Git
- Menjadi arsip perkembangan project dan eksperimen
- Menjalankan automation menggunakan GitHub Actions

## Struktur

```text
.
├── .github/
│   └── workflows/
│       └── daily.yml
├── daily/
│   ├── 2026-08-22.md
│   ├── 2026-08-23.md
│   └── ...
└── README.md
