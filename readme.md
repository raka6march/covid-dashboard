# Dashboard Interaktif COVID-19 Indonesia + Model AI

Project Tugas Besar: Visualisasi Interaktif + Model AI  
Menggunakan Bokeh + Scikit-learn

---

## Tujuan

Membuat dashboard interaktif yang menampilkan data COVID-19 Indonesia per provinsi dan per tahun, serta membangun model AI untuk memprediksi zona risiko per provinsi.

---

## Struktur File

- `app.py` → Main Dashboard Bokeh (Line, Pie, Bar, Div Analisis, Div Hasil Model AI, Kesimpulan)
- `classification.ipynb` → Model AI (Decision Tree Classifier → prediksi zona risiko)
- `covid_19_indonesia_time_series_all.csv` → Dataset
- `requirements.txt` → Library yang digunakan
- `readme.md` → Dokumentasi project

---

## Teknologi yang Digunakan

- Python
- Bokeh
- Pandas
- Scikit-learn

---

## Cara Menjalankan Dashboard

1️⃣ Buka Terminal  
2️⃣ Masuk ke folder project:

```bash
cd ~/covid-dashboard
bokeh app server
