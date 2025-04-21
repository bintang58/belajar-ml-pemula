# 📦 Submission - Belajar Machine Learning untuk Pemula

Repositori ini berisi dua proyek akhir dari modul **Belajar Machine Learning untuk Pemula** dalam pelatihan **Laskar AI**, yaitu:

1. 🧠 **Clustering** - Mengelompokkan data berdasarkan kemiripan fitur.
2. 🤖 **Klasifikasi** - Membuat model klasifikasi berdasarkan hasil clustering.

---

## 📁 Struktur Folder

| Nama File | Deskripsi |
|-----------|-----------|
| `[Clustering]_Submission_Akhir_BMLP.ipynb` | Notebook untuk tugas clustering data |
| `[Klasifikasi]_Submission_Akhir_BMLP.ipynb` | Notebook untuk klasifikasi hasil clustering |
| `Dataset_clustering.csv` | Dataset utama yang digunakan dalam kedua proyek |
| `Dataset_inisiasi.csv` | Dataset tambahan dari Kaggle (tidak disertakan di repositori karena ukuran besar) |

---

## 📂 Akses Dataset Tambahan

Dataset `Dataset_inisiasi.csv` berasal dari Kaggle dan tidak diunggah langsung ke repositori karena ukurannya cukup besar. Kamu bisa mengunduh dataset tersebut langsung dari link berikut:

📥 **[Download Dataset - Beverage Sales (Kaggle)](https://www.kaggle.com/datasets/sebastianwillmann/beverage-sales)**

> Setelah diunduh, kamu bisa menempatkan file `Dataset_inisiasi.csv` di direktori yang sama dengan notebook saat menjalankan proyek di lokal atau Google Colab.

---

## 🛠️ Teknologi

- **Python**:
  - `numpy` – Operasi numerik dasar.
  - `pandas` – Manipulasi dan analisis data.
  - `matplotlib` & `seaborn` – Visualisasi grafik dan data.
- **Scikit-learn**:
  - `KMeans` – Algoritma clustering.
  - `RandomForestClassifier`, `GaussianNB` – Model klasifikasi.
  - `train_test_split`, `RandomizedSearchCV` – Split data & tuning hyperparameter.
  - `MinMaxScaler`, `StandardScaler`, `LabelEncoder` – Normalisasi dan encoding data.
  - `PCA` – Reduksi dimensi.
  - `confusion_matrix`, `accuracy_score`, `precision_score`, `recall_score`, `f1_score`, `classification_report`, `silhouette_score` – Evaluasi model.
- **Yellowbrick**:
  - `KElbowVisualizer` – Visualisasi Elbow Method untuk clustering.
- **Google Colab**:
  - Menggunakan `google.colab.drive` untuk membaca dan menyimpan file dari Google Drive.
- **Jupyter Notebook** – Alternatif lokal untuk eksplorasi dan pengembangan model.

---

## 🚀 Menjalankan Proyek

### 1. Jalankan di Google Colab

> Cocok untuk pengguna yang tidak ingin setup environment lokal.

1. Buka [Google Colab](https://colab.research.google.com).
2. Klik **File > Open notebook > GitHub**.
3. Masukkan URL repositori ini.
4. Pilih file notebook yang ingin dijalankan:
   - `[Clustering]_Submission_Akhir_BMLP_Bintang_Cahya_Anwar.ipynb`
   - `[Klasifikasi]_Submission_Akhir_BMLP_Bintang_Cahya_Anwar.ipynb`
5. Upload file `Dataset_clustering.csv` melalui sidebar **Files → Upload**.

### 2. Jalankan Secara Lokal

1. Clone repository ini:
   ```bash
   git clone https://github.com/bintang58/belajar-ml-pemula
   cd belajar-ml-pemula
2. Buat dan aktifkan environment (opsional, tapi disarankan):
   ```bash
   python -m venv nama_venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
3. Install dependensi:
   ```bash
   pip install -r requirements.txt
4. Jalankan notebook menggunakan Jupyter atau Jupyter Lab:
   ```bash
   jupyter notebook

---

## 📝 Catatan

- Dataset dari Kaggle perlu diunduh dan diunggah manual saat menjalankan di Colab.
- Disarankan untuk eksplorasi dan preprocessing data dilakukan terlebih dahulu untuk memahami struktur dan kualitas datanya.

---

> Proyek ini diibuat sebagai bagian dari pelatihan **Laskar AI - Belajar Machine Learning untuk Pemula**
