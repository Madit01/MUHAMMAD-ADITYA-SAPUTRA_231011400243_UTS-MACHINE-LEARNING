# Prediksi Kelulusan - Project

Proyek ini membuat model klasifikasi untuk memprediksi **status kelulusan mahasiswa**
dengan menggunakan **Iris dataset** (dimodifikasi labelnya).

## Struktur folder
```
prediksi_kelulusan_project/
├─ data/
│  └─ dataset_iris_kelulusan.csv
├─ src/
│  └─ prediksi_kelulusan.py
├─ report/
│  └─ laporan_prediksi_kelulusan.docx
└─ requirements.txt
```

## Cara menjalankan
1. Pasang dependensi:
   ```
   pip install -r requirements.txt
   ```
2. Jalankan script:
   ```
   python src/prediksi_kelulusan.py
   ```
Hasil ringkasan evaluasi akan disimpan di `report/results_summary.txt` dan plot ROC di `report/plots/` (jika tersedia).
