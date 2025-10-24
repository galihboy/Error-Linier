# Error Linier Assets

Folder ini menyimpan tiga varian demo untuk memahami residual pada regresi linier sederhana.

## Daftar Berkas

- `error_demo.ipynb` — Notebook perhitungan manual tiga titik terhadap garis referensi lengkap dengan penjelasan tiap langkah.
- `interactive_error_demo.ipynb` — Notebook interaktif berbasis Plotly + ipywidgets sehingga slider dapat digunakan langsung di lingkungan Jupyter.
- `index.html` — Halaman web mandiri dengan slider, grafik Plotly, tabel metrik (MAE, MSE, RMSE, MAPE), dan penjelasan residu.

## Cara Pakai Singkat

1. Untuk notebook, pastikan dependensi berikut tersedia:
   ```bash
   pip install numpy plotly ipywidgets
   jupyter nbextension enable --py widgetsnbextension
   ```
2. Buka notebook di JupyterLab atau VS Code, jalankan dari sel pertama.
- Versi daring tersedia di https://galih.eu/Error-Linier/.

Seluruh materi dapat digunakan kembali untuk keperluan pembelajaran dengan mencantumkan kredit kepada Galih Hermawan.
