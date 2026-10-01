# HR Analytics MNC

Analisis data HR menggunakan Python, mencakup eksplorasi data, pemeriksaan kualitas data, klasifikasi Random Forest, dan clustering K-Means.

## Struktur

```text
.
|-- DataAnalyticsss (1).ipynb   # Notebook analisis
|-- Dataset.txt                 # Sumber dataset
|-- LaporanDataEng Kel 11.pdf   # Laporan pendukung
|-- requirements.txt            # Dependensi Python
|-- .gitignore
```

File presentasi `.pptx` sengaja tidak disertakan di repository.

## Dataset

Dataset tidak disimpan di repository ini. Tautan sumber Kaggle dan Google Drive tersedia di [Dataset.txt](Dataset.txt). Unduh file CSV, lalu letakkan di folder yang sama dengan notebook dengan nama:

```text
HR_Data_MNC_Data Science Lovers.csv
```

Periksa ketentuan lisensi dan penggunaan dataset sebelum membagikan salinannya.

## Menjalankan notebook

Gunakan Python 3.10 atau lebih baru. Dari folder proyek, buat environment dan pasang dependensi:

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
```

Buka `DataAnalyticsss (1).ipynb` di VS Code atau jalankan dengan Jupyter setelah memilih environment tersebut sebagai kernel.