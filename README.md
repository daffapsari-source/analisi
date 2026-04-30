# analisis
Berikut versi **README Bahasa Indonesia** yang lebih profesional dan siap untuk GitHub 👇

---

# 🚲 Analisis Data Bike Sharing

## 📌 Gambaran Proyek

Proyek ini bertujuan untuk menganalisis data penyewaan sepeda guna menemukan pola serta insight terkait perilaku pengguna. Analisis difokuskan pada pengaruh faktor lingkungan seperti kondisi cuaca dan musim terhadap jumlah penyewaan sepeda.

Hasil dari analisis ini diharapkan dapat membantu pengambilan keputusan berbasis data dalam meningkatkan layanan bike sharing.

---

## 🎯 Pertanyaan Bisnis

* Bagaimana pengaruh kondisi cuaca terhadap jumlah penyewaan sepeda?
* Musim apa yang memiliki jumlah penyewaan sepeda tertinggi?

---

## 📊 Dataset

Dataset yang digunakan adalah **Bike Sharing Dataset**, yang terdiri dari:

* `day.csv` → Data penyewaan sepeda per hari
* `hour.csv` → Data penyewaan sepeda per jam

### Fitur Utama:

| Fitur        | Deskripsi                            |
| ------------ | ------------------------------------ |
| `season`     | Musim (Spring, Summer, Fall, Winter) |
| `weathersit` | Kondisi cuaca                        |
| `temp`       | Temperatur                           |
| `cnt`        | Total penyewaan sepeda               |

---

## 🛠️ Teknologi yang Digunakan

* **Python**
* **Pandas** → Manipulasi data
* **Matplotlib** → Visualisasi data
* **Seaborn** → Visualisasi statistik

---

## 🔄 Proses Analisis Data

### 1. Data Gathering

* Mengimpor dataset menggunakan `pandas.read_csv()`

### 2. Data Cleaning

* Mengubah data kategorikal menjadi label yang mudah dipahami
* Memastikan tidak ada missing values
* Mengecek konsistensi data

### 3. Exploratory Data Analysis (EDA)

* Menganalisis hubungan antara:

  * Cuaca dan jumlah penyewaan
  * Musim dan jumlah penyewaan

### 4. Visualisasi Data

* Menggunakan bar chart untuk membandingkan jumlah penyewaan
* Menampilkan pola dan tren data

---

## 📈 Insight Utama

* Kondisi cuaca memiliki pengaruh signifikan terhadap jumlah penyewaan sepeda
* Cuaca cerah atau kondisi baik menghasilkan jumlah penyewaan lebih tinggi
* Musim tertentu memiliki tingkat penyewaan yang lebih tinggi dibanding lainnya

---

## 🚀 Cara Menjalankan Proyek

### ▶️ Menggunakan Google Colab

1. Buka Google Colab
2. Upload file `.ipynb`
3. Upload dataset (`day.csv` dan `hour.csv`)
4. Jalankan semua cell

---

### 💻 Menjalankan Secara Lokal

1. Clone repository:

```bash id="u2m3l0"
git clone https://github.com/username/bike-sharing-analysis.git
cd bike-sharing-analysis
```

2. Install dependency:

```bash id="k91z0c"
pip install pandas matplotlib seaborn

---

## 📌 Pengembangan Selanjutnya

* Membuat dashboard interaktif menggunakan Streamlit
* Menambahkan model prediksi (machine learning)
* Deploy proyek menjadi aplikasi web

---

## 👤 Author

**Daffa Apsari Aprila Nala Muhaemin**

* Email: [daffapsari@gmail.com](mailto:daffapsari@gmail.com)
* Dicoding ID: cdcc012d6x0148

---

## 📜 Lisensi

Proyek ini dibuat untuk tujuan pembelajaran dan sebagai submission analisis data.
