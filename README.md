# UTS Graf Sains Data — Rekomendasi Berbasis Graf (RetailRocket × Neo4j)

- **Notebook:** `UTS_GSD_RetailRocket_Neo4j.ipynb`
- **Dataset hasil filter:** `data/events_filtered.csv` (kolom `fold` = P1/P2)
- **Periode (UTC):** P1 = 2015-08-08 s/d sebelum 2015-08-22 (training), P2 = 2015-09-05 s/d sebelum 2015-09-12 (testing)
- **Neo4j:** Neo4j Desktop 2, server 2026.09, database `neo4j`
- **Screenshot graf (sebelum/sesudah similarity):** folder `img/`

## Cara menjalankan
```bash
uv venv myvenv --python 3.10 && source myvenv/bin/activate
uv pip install -r requirements.txt
jupyter notebook
```
Ganti password di sel konfigurasi (`AUTH`), lalu jalankan semua sel (Run All).

`data/events.csv` (±90 MB) tidak di-upload karena melebihi batas GitHub; notebook mengunduhnya otomatis dari Kaggle.
