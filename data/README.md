# Data Pencarian Literatur

Folder ini berisi data hasil pencarian literatur menggunakan Publish or Perish.

## Struktur

```
data/
├── search-results/     # Hasil pencarian mentah (CSV dari PoP)
└── processed/          # Data yang sudah diproses dan difilter
```

## Daftar Query

| Query | Nama File | Deskripsi |
|-------|-----------|-----------|
| 1 | Query 1 - Propolis Dasar.csv | Propolis sebagai biomaterial |
| 2 | Query 2 - Propolis dalam Aplikasi Medis.csv | Propolis untuk aplikasi medis |
| 3 | Query 3 - Propolis Properties.csv | Sifat-sifat propolis |
| 4 | Query 4 - GBR Overview.csv | Overview GBR |
| 5 | Query 5 - GBR dengan Coating.csv | GBR dengan coating |
| 6 | Query 6 - Collagen Membrane dalam GBR.csv | Membran kolagen untuk GBR |
| 7 | Query 7 - Modifikasi Collagen Membrane.csv | Modifikasi membran kolagen |
| 9 | Query 9 - Coating Technology.csv | Teknologi coating |
| 10 | Query 10 - Natural Products untuk Coating.csv | Natural products sebagai coating |
| 11 | Query 11 - Kombinasi Spesifik.csv | Kombinasi spesifik (critical search) |
| 13 | Query 13 - Review & Systematic Review.csv | Review articles |
| 14 | Query 14 - Metodologi Karakterisasi.csv | Metode karakterisasi |

## File Processed

| File | Deskripsi | Jumlah Artikel |
|------|-----------|----------------|
| Query 1 - Propolis Dasar - PROCESSED.csv | Filtered & ranked | 177 |

## Kolom Data

File CSV dari Publish or Perish memiliki kolom:
- Cites, Authors, Title, Year, Source, Publisher
- ArticleURL, CitesURL, DOI, ISSN
- Volume, Issue, StartPage, EndPage
- ECC, CitesPerYear, CitesPerAuthor, AuthorCount, Age
- Abstract, FullTextURL, RelatedURL

File PROCESSED memiliki kolom tambahan:
- Rank (urutan berdasarkan sitasi)
- Kesesuaian (Ya/Parsial/Tidak)

---

*Bagian dari [Proposal Tesis](../README.md)*
