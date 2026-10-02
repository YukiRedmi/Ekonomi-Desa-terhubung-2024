# Lanskap Konektivitas Wilayah Indonesia

**Konektivitas Digital, Mobilitas, dan Infrastruktur Ekonomi Kabupaten/Kota Indonesia — Podes 2024**

Repositori ini memuat dashboard visualisasi interaktif untuk mengeksplorasi pola **konektivitas digital**, **mobilitas**, dan **infrastruktur ekonomi** pada **514 kabupaten/kota** di Indonesia berdasarkan **Statistik Potensi Desa Indonesia 2024 (Podes 2024)**.

## Tujuan
Dashboard ini dirancang untuk:
- menggambarkan variasi indikator antar kabupaten/kota;
- menunjukkan persebaran geografis indikator dan kelompok wilayah;
- menampilkan struktur wilayah Indonesia → Provinsi → Kabupaten/Kota;
- membantu interpretasi pola multivariat, cluster, dan pencilan secara eksploratif.

## Cakupan data
- **Unit analisis:** 514 kabupaten/kota
- **Provinsi:** 38
- **Sumber utama:** BPS — Statistik Potensi Desa Indonesia 2024
- **Indikator utama:** 8 indikator
- **Observasi lengkap PCA/clustering:** 509
- **Pencilan multivariat (99%):** 25

## Topik visualisasi
Dashboard mencakup tiga topik utama:
1. **Multivariat** — PCA, clustering, parallel coordinates, clustered heatmap, brushing/linking.
2. **Geospasial** — choropleth, proportional symbol map, focus-context map.
3. **Hierarkis** — treemap dan sunburst untuk Indonesia → Provinsi → Kabupaten/Kota.

## Judul akademik
- **Judul dashboard:** *Lanskap Konektivitas Wilayah Indonesia*
- **Judul laporan:** *Visualisasi Konektivitas Digital, Mobilitas, dan Infrastruktur Ekonomi Kabupaten/Kota Indonesia: Analisis Podes 2024*
- **Judul makalah IEEE:** *Eksplorasi Visual Multivariat, Geospasial, dan Hierarkis Konektivitas Digital, Mobilitas, dan Infrastruktur Ekonomi Kabupaten/Kota Indonesia Berdasarkan Podes 2024*

## Struktur berkas utama
- `index.html` — berkas utama dashboard
- `dashboard.js` — logika visualisasi dan interaksi
- `styles.css` — styling dashboard
- `plotly.min.js` — pustaka visualisasi
- `PODES_2024_DASHBOARD_FINAL.html` — versi single-file
- `assets/header-hero.webp` — aset header
- `data/` — data final dashboard
- `docs/` — dokumentasi inti

## Data final
- `data/PODES_2024_DASHBOARD_DATA.csv`
- `data/PODES_2024_DASHBOARD_ANALYSIS.geojson`
- `data/PODES_2024_HIERARCHY_READY.json`
- `data/DATA_DICTIONARY.csv`
- `data/dashboard_records.json`
- `data/dashboard_geo.geojson`
- `data/dashboard_meta.json`
- `data/analysis_podes_2024.py`

## Dokumentasi inti
- `docs/ACADEMIC_TITLE_AND_SCOPE.md`
- `docs/DATA_PROVENANCE.md`
- `docs/UAS_COMPLIANCE.md`
- `docs/FINAL_QA_CHECKLIST.md`
- `docs/FILE_MANIFEST_SHA256.txt`

## Catatan interpretasi
Analisis bersifat **deskriptif dan eksploratif**. PCA, K-Means, dan deteksi pencilan digunakan untuk membantu pembacaan pola, bukan sebagai indeks atau klasifikasi resmi pembangunan.

## Sumber data
**Badan Pusat Statistik (BPS)**  
*Statistik Potensi Desa Indonesia 2024*  
Katalog 1105014 · Nomor publikasi 04300.24002 · Rilis 10 Desember 2024

## Batas wilayah digital
Sumber batas wilayah pendukung:
**Indonesia-GeoJSON / Peta Nusa / Laravel Nusa**  
Referensi administratif: **Kepmendagri No. 300.2.2-2138 Tahun 2025**
