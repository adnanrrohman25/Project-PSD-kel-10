
# Project-PSD-kel-10

Repositori ini dibuat untuk memenuhi tugas mata kuliah **Pengantar Sains Data**. Proyek ini berfokus pada analisis eksploratif (*Exploratory Data Analysis*), prapemrosesan data, serta pemodelan prediktif menggunakan dataset *Online Shoppers Purchasing Intention* dari UCI Machine Learning Repository.

## Anggota Kelompok
```text
Muhammad Nizar Aflah (K1D025007)
Auryn Nathan Fauzia (K1D025016)
Oktaviana Ramadhani (K1D025019)
Rizky Aulia Putri (K1D025029)
Adnan Nurrohman (K1D025037)
```

## Struktur Repositori

```text
├── DATASET/        
├── LAPORAN/        
├── NOTEBOOK/       
└── README.md       
```

## Petunjuk Menjalankan Notebook

### 1. Prasyarat
Pastikan perangkat sudah terinstal **Python 3.8+** beserta salah satu lingkungan berikut:
* **Jupyter Notebook / JupyterLab** atau **Visual Studio Code** (dengan ekstensi Jupyter), atau
* Akun Google untuk menjalankan secara daring melalui **Google Colab**.

### 2. Persiapan Repositori dan Pustaka
1. *Clone* repositori ini atau unduh dalam format `.zip` lalu ekstrak ke komputer lokal:
   ```bash
   git clone [https://github.com/adnanrrohman25/Project-PSD-kel-10.git](https://github.com/adnanrrohman25/Project-PSD-kel-10.git)
   cd Project-PSD-kel-10
   ```
2. Instal pustaka Python yang dibutuhkan melalui terminal:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn kagglehub
   ```

### 3. Menjalankan Kode Analisis
* **Secara Lokal (Jupyter Notebook / VS Code):**
  1. Buka folder `NOTEBOOK/` dan pilih file `.ipynb` utama.
  2. Pastikan jalur pembacaan dataset mengarah ke folder `../DATASET/` agar file data dapat terbaca dengan benar.
  3. Jalankan seluruh sel kode secara berurutan dari atas ke bawah (**Run All**).

* **Melalui Google Colab:**
  1. Unggah file `.ipynb` dari folder `NOTEBOOK/` ke Google Colab.
  2. Unggah file dataset dari folder `DATASET/` ke penyimpanan sesi Colab (atau jalankan blok kode unduhan `kagglehub` di dalam *notebook*).
  3. Pilih menu **Runtime > Run all** untuk menjalankan seluruh tahapan analisis.
