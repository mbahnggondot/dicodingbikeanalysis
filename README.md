# Proyek Analisis Data - Bike Sharing Dataset

Proyek ini merupakan analisis data dari dataset *Bike Sharing* untuk memahami pola penggunaan sepeda berdasarkan waktu dan pengaruh faktor cuaca terhadap jumlah penyewaan sepeda.

## Deskripsi Proyek

Dalam proyek ini, dilakukan berbagai tahapan analisis data, mulai dari pembersihan data (*data wrangling*), eksplorasi data (*exploratory data analysis*), hingga visualisasi data menggunakan Jupyter Notebook dan pembuatan dashboard interaktif menggunakan Streamlit.

### Struktur Direktori
```
submission/
├───dashboard/
│   ├───day.csv
│   ├───hour.csv
│   └───dashboard.py
├───data/
│   ├───day.csv
│   └───hour.csv
├───notebook.ipynb
├───README.md
├───requirements.txt
└───url.txt
```



### Panduan Menjalankan Proyek

1. **Analisis di Jupyter Notebook:**
   - Buka `notebook.ipynb` menggunakan Jupyter Notebook atau Google Colab.
   - Jalankan semua sel untuk melihat proses analisis dan visualisasi data.

2. **Menjalankan Dashboard dengan Streamlit:**
   - Pastikan Anda telah menginstal semua pustaka yang tercantum di `requirements.txt`.
     JIKA BELUM menginstall requirements
      ```
     pip install -r requirements.txt
      ```
   - Jalankan perintah berikut di terminal:
     ```bash
     streamlit run dashboard/goldan.py
     ```

### Persyaratan

Pastikan Anda memiliki pustaka berikut yang terpasang di lingkungan Python Anda:

```
setuptools>=74.1.2
wheel>=0.44.0
pillow==9.4.0
scikit-learn==1.3.1
Babel==2.12.1
matplotlib==3.8.0
numpy==1.25.2
pandas==2.1.4
seaborn==0.13.0
streamlit==1.30.0
```

### Kesimpulan

- **Pola Penggunaan Sepeda Berdasarkan Waktu:** Penggunaan sepeda cenderung meningkat pada jam-jam tertentu dalam sehari.
- **Pengaruh Cuaca terhadap Penyewaan Sepeda:** Kondisi cuaca yang lebih baik cenderung meningkatkan jumlah penyewaan sepeda.
