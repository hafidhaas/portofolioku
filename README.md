# Portofolio Analisis Spasial — Hafidha Aulia Setyanida

Situs portofolio satu tautan berisi karya analisis spasial, GIS, dan pengolahan
citra drone. Dibangun sebagai halaman statis (HTML + CSS), tanpa proses build,
siap ditayangkan di GitHub Pages.

## Halaman

- `index.html` — beranda + indeks karya
- `projects/unfpa-garut.html` — Risiko Kematian Ibu & Perubahan Iklim
- `projects/klhs-teluk-pandan.html` — KLHS RDTR Teluk Pandan
- `projects/drone.html` — Pemetaan Drone & Fotogrametri
- `projects/deka-insight.html` — Validasi Data Survei
- `projects/coursework-thesis.html` — Skripsi & Tugas Kuliah

## Atribusi & hak cipta

- **UNFPA Garut** — output magang di UNFPA Indonesia, bersama Kharunnisa Pertiwi.
  Tabel numerik ditampilkan sebagian karena bersifat internal.
- **KLHS Teluk Pandan** — bagian dari proyek Rekaspasial Indonesia. Hak cipta dokumen
  tetap pada Rekaspasial & klien; tabel/matriks ditampilkan sebagian (pra-validasi).
- **Drone** — laporan pemrosesan fotogrametri (Agisoft Metashape).

Struktur:

```
.
├── index.html
├── style.css
├── README.md
├── projects/
│   ├── unfpa-garut.html
│   ├── klhs-teluk-pandan.html
│   ├── drone.html
│   ├── deka-insight.html
│   └── coursework-thesis.html
└── assets/
    ├── klhs/     (7 gambar)
    ├── unfpa/    (8 gambar)
    ├── drone/    (4 gambar)
    ├── deka/     (kosong — untuk cuplikan Anda)
    └── akademik/ (kosong — untuk gambar Anda)
```

Narasi tiap halaman sudah disesuaikan dengan peran sebenarnya:
- UNFPA Garut — dikerjakan penuh (data, analisis, peta, laporan).
- KLHS Teluk Pandan — pemeriksaan data, pengisian matriks KRP, dan narasi (peta oleh tim).
- Drone — diproses sendiri (RTK/PPK/GCP).
- Deka Insight — pemeriksaan isian kuesioner survei (bukan validasi peta).
