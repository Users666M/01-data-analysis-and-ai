# Make Sense of Data with Analysis and AI
Studi kasus sesi **Make Sense of Data with Analysis and AI** (Andria Arisal) - *Informatics Practitioner Lecture Series, Informatika Unib*.

**Tema:** deteksi dan atribusi penyebab deforestasi di Provinsi Bengkulu. Data **sintetis** (untuk pembelajaran).

**Tujuan:** Menjelaskan karakteristik alert deforestasi Bengkulu lewat eksplorasi data (EDA) sebelum memodelkannya dengan AI.

## Hasil singkat
- 6.000 alert, 6 penyebab; pertanian rakyat 35%, kebun sawit 24%
- Infrastruktur dekat jalan (rata-rata 0,6 km), kebakaran punya penurunan NBR tinggi (0,44), pembalakan di lereng curam
- Output: 4 grafik di `reports/figures/` dan `reports/eda_summary_by_driver.csv`

## Struktur
```
src/generate_data.py   # data sintetis
src/eda.py             # analisis data
src/features.py, config.py
data/  reports/  docs/
```

## Menjalankan
```bash
pip install -r requirements.txt
python -m src.generate_data
python -m src.eda
```

## Repo lain dalam rangkaian studi kasus ini
- `02-hpc-parallel-processing`
- `03-gis-spatial-analysis`
- `04-machine-learning-intro`
- `05-hci-data-visualization`
- `06-deforestation-drivers-satellite-ai`
