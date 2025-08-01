# data-mining-anime

## Deskripsi
Project ini berisi analisis dan prediksi anime populer menggunakan data dari `popular_anime.csv` dan notebook Jupyter `data2.ipynb`.

## Cara Pakai

1. **Clone repository ini**
   ```bash
   git clone https://github.com/zakkunaw/data-mining-anime.git
   cd data-mining-anime
   ```

2. **(Opsional) Buat virtual environment**
   ```bash
   python -m venv venv
   venv\Scripts\activate  # Windows
   # source venv/bin/activate  # Linux/Mac
   ```

3. **Install dependensi**
   ```bash
   pip install -r requirements.txt
   # atau install manual:
   pip install pandas scikit-learn matplotlib seaborn imbalanced-learn notebook
   ```

4. **Jalankan Jupyter Notebook**
   ```bash
   jupyter notebook
   # atau
   jupyter-lab
   ```

5. **Buka file `data2.ipynb`**
   - Jalankan cell satu per satu dari atas ke bawah.
   - Analisis dan model prediksi akan berjalan otomatis sesuai urutan cell.

## Struktur File
- `data2.ipynb` : Notebook utama analisis & prediksi
- `popular_anime.csv` : Dataset anime populer
- `README.md` : Dokumentasi project

## Catatan
- Pastikan Python 3 sudah terinstall.
- Jika ada error package, install manual sesuai kebutuhan.
- Untuk update data atau analisis, edit dan commit ulang notebook.

---
Created by zakkunaw
