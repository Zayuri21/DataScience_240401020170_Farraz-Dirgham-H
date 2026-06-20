# 📊 Portofolio Data Science – Sesi 1 sampai 7

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-red?logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-2.x-darkblue?logo=pandas)
![Status](https://img.shields.io/badge/Status-Lengkap-brightgreen)

</div>

---

## 👤 Identitas Mahasiswa

| Keterangan | Detail |
|---|---|
| **Nama Lengkap** | [Farraz Dirgham H] |
| **NIM** | [240401020170] |
| **Kelas** | [IF405] |
| **Program Studi** | [Teknik Informatika] |
| **Mata Kuliah** | Data Science |
| **Dosen Pengampu** | [Syahid abdullah,S.Si,M.kom] |

---

## 📖 Tentang Repository Ini

Halo! Saya adalah mahasiswa yang sedang menempuh mata kuliah **Data Science**. Repository ini mendokumentasikan seluruh perjalanan belajar saya dari Sesi 1 hingga Sesi 7, mencakup notebook praktikum yang dikerjakan selama perkuliahan.

Saya tertarik pada Data Science karena bidang ini memiliki kemampuan luar biasa untuk mengubah data mentah menjadi wawasan  yang berguna bagi pengambilan keputusan nyata. Tujuan belajar saya adalah membangun fondasi yang kokoh — mulai dari memahami data, membersihkannya, menganalisisnya secara statistis, memvisualisasikannya, hingga membangun model Machine Learning pertama yang benar-benar dapat diandalkan.

Repository ini dirancang secara terstruktur mengikuti silabus kuliah, di mana setiap sesi saling berkaitan satu sama lain. Sesi 1–2 membangun fondasi Python, Sesi 3–4 mengolah dan menganalisis data, Sesi 5 mengomunikasikan data lewat visualisasi, Sesi 6 menyiapkan data untuk machine learning, dan Sesi 7 mengaplikasikan model pertama — Regresi Linier — secara end-to-end.

---

## 📂 Struktur Repository

```
DataScience_[240401020170]_[Farraz Dirgham H]/
│
├── README.md
│
├── Sesi_1/
│   └── Sesi1_Pengenalan_DataScience.ipynb
│
├── Sesi_2/
│   └── Sesi2_StrukturData_NumPy_Pandas.ipynb
│
├── Sesi_3/
│   └── Sesi3_Data_Cleaning.ipynb
│
├── Sesi_4/
│   └── Sesi4_Statistika_Dasar.ipynb
│
├── Sesi_5/
│   └── Sesi5_Visualisasi_Data.ipynb
│
├── Sesi_6/
│   └── Sesi6_Persiapan_Data.ipynb
│
└── Sesi_7/
    └── Sesi7_Regresi_Linier.ipynb
```

---

## 📚 Daftar Sesi & Notebook

| # | Topik | Materi Utama | Link Notebook |
|:---:|---|---|:---:|
| 1 | Pengenalan Data Science | Definisi DS, siklus hidup, peran, jenis data, ekosistem Python | [📓 Buka](./Sesi_1/Sesi1_Pengenalan_DataScience.ipynb) |
| 2 | Struktur Data Python, NumPy & Pandas | List, tuple, set, dict, array NumPy, Series & DataFrame Pandas | [📓 Buka](./Sesi_2/Sesi2_StrukturData_NumPy_Pandas.ipynb) |
| 3 | Data Cleaning: Missing, Outlier & Ekstraksi | Imputasi, IQR, capping, regex, ekstraksi tanggal | [📓 Buka](./Sesi_3/Sesi3_Data_Cleaning.ipynb) |
| 4 | Statistika Dasar & Analisis Data | Pemusatan, penyebaran, distribusi, korelasi, uji hipotesis (t-test) | [📓 Buka](./Sesi_4/Sesi4_Statistika_Dasar.ipynb) |
| 5 | Visualisasi Data | Bar, pie, donut, histogram, KDE, scatter, box, violin, line, heatmap, dashboard | [📓 Buka](./Sesi_5/Sesi5_Visualisasi_Data.ipynb) |
| 6 | Persiapan Data | Feature engineering, encoding, scaling, train-test split, ColumnTransformer, K-Fold | [📓 Buka](./Sesi_6/Sesi6_Persiapan_Data.ipynb) |
| 7 | Pengantar ML: Regresi Linier | Simple & Multiple LR, evaluasi (MAE/RMSE/R²), residual, cross-validation, prediksi | [📓 Buka](./Sesi_7/Sesi7_Regresi_Linier.ipynb) |

---

## 🛠️ Tools & Library yang Digunakan

| Library | Kegunaan | Versi |
|---|---|---|
| `Python` | Bahasa pemrograman utama | 3.10+ |
| `NumPy` | Komputasi numerik & operasi array | ≥ 1.24 |
| `Pandas` | Manipulasi & analisis data tabular | ≥ 2.0 |
| `Matplotlib` | Visualisasi data dasar | ≥ 3.7 |
| `Seaborn` | Visualisasi statistik tingkat lanjut | ≥ 0.12 |
| `Scikit-learn` | Preprocessing, model ML, evaluasi | ≥ 1.3 |
| `SciPy` | Uji statistik (t-test, Shapiro, dll.) | ≥ 1.10 |

---

## ▶️ Cara Menjalankan Notebook

### Opsi 1 – Google Colab (Tanpa Instalasi, Direkomendasikan)

1. Klik link notebook di tabel di atas → GitHub menampilkan notebook
2. Klik **"Open in Colab"** (atau buka [colab.research.google.com](https://colab.research.google.com) → `File → Upload notebook`)
3. Jalankan sel dari atas ke bawah: `Runtime → Run All` atau `Shift + Enter`

### Opsi 2 – Jupyter Lokal

```bash
# 1. Clone repository
git clone https://github.com/[username]/DataScience_[NIM]_[Nama].git
cd DataScience_[NIM]_[Nama]

# 2. Install dependensi
pip install numpy pandas matplotlib seaborn scikit-learn scipy jupyterlab

# 3. Jalankan Jupyter
jupyter lab
```

### Opsi 3 – Anaconda

```bash
conda create -n datasci python=3.10
conda activate datasci
conda install numpy pandas matplotlib seaborn scikit-learn scipy jupyterlab
jupyter lab
```

---

## 🗺️ Alur Belajar Antar Sesi

```
Sesi 1 ──► Sesi 2 ──► Sesi 3 ──► Sesi 4
Pengenalan  Struktur   Cleaning   Statistik
Data Sci    Data &     Data       & Analisis
            NumPy,                Data
            Pandas
                                    │
                                    ▼
                    Sesi 7 ◄── Sesi 6 ◄── Sesi 5
                    Regresi    Persiapan  Visualisasi
                    Linier     Data ML    Data
                    (ML)       (Encoding,
                               Scaling,
                               Split)
```

---

## 🎯 Kesimpulan Umum Perjalanan Belajar Data Science

Tujuh sesi ini membentuk sebuah alur belajar yang logis dan saling menopang. Perjalanan dimulai dari pengenalan konsep Data Science secara menyeluruh di Sesi 1, dilanjutkan dengan membangun kemampuan teknis dasar menggunakan Python, NumPy, dan Pandas di Sesi 2. Dua sesi ini adalah pondasi yang tidak bisa dilewati.

Sesi 3 dan 4 memasuki inti analisis data: membersihkan data dari noise dan inkonsistensi, lalu menganalisisnya secara statistik untuk memahami distribusi, pola, dan hubungan antar variabel. Prinsip penting yang saya pelajari di sini adalah bahwa *kualitas data jauh lebih menentukan daripada kecanggihan algoritma*. Sesi 5 mengajarkan bahwa data yang baik perlu dikomunikasikan dengan visualisasi yang tepat — sebab angka saja tidak selalu cukup untuk meyakinkan pemangku kepentingan.

Sesi 6 adalah jembatan kritis menuju machine learning: memastikan data disiapkan dengan benar menggunakan encoding, scaling, dan train-test split tanpa *data leakage*. Puncaknya di Sesi 7 — membangun model regresi linier pertama dari awal hingga evaluasi dan prediksi. Di sinilah semua pembelajaran sebelumnya bersatu.

Secara keseluruhan, saya memahami bahwa Data Science adalah proses **berulang dan interdisipliner** — bukan hanya tentang menjalankan kode, tetapi tentang berpikir kritis terhadap data, memilih pendekatan yang tepat, dan menginterpretasikan hasil secara bermakna.

---

## 📬 Kontak

- **Email:** [farraz82@gmail.com]
- **GitHub:** [github.com/Zayuri21]

---

<div align="center">
  <sub>Dibuat dengan ❤️ sebagai bagian dari perkuliahan Data Science</sub>
</div>
