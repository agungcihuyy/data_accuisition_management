# Proyek Akuisisi dan Manajemen Data

- **Mata Kuliah** : BIFP-243 Akuisisi dan Manajemen Data
- **Nama** : I Gusti Lanang Agung Wahyu Pandu Rangga
- **NIM** : 2501010026
- **Tujuan** : Persiapan awal environment dan struktur proyek untuk data acquisition

## Struktur Folder
- data/raw       : Data mentah hasil akuisisi (READ-ONLY)
- data/interim   : Hasil antara (cleaning, transformasi)
- data/processed : Dataset final siap analisis
- notebooks      : Notebook praktikum
- src            : Script Python yang dapat digunakan ulang
- docs           : Data dictionary dan metadata
- reports        : Laporan kualitas data

## Cara Menjalankan Ulang
1. pip install -r requirements.txt
2. Jalankan notebook di folder notebooks secara berurutan
"""

(ROOT / "README.md").write_text(readme, encoding="utf-8")
print((ROOT / "README.md").read_text(encoding="utf-8"))
