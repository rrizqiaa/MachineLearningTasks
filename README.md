# MachineLearningTasks

Task 
https://kalbecorp-my.sharepoint.com/:x:/p/shinta_hanafia/ETs1m-9lDftPuTkb6QkvgJYBHdbWBy0x3yssJXUAY56PWg?e=xd33gs

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24-orange)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red)
![License](https://img.shields.io/github/license/rrizqiaa/MachineLearningTasks)

liblary version
tensorflow                   2.12.0
xgboost                      2.1.3
scikit-learn                 1.5.2

Repository ini terkait pembelajaran mesin (Machine Learning) yang mencakup model regresi, klasifikasi, clustering, hingga implementasi menggunakan PyTorch. Setiap proyek disusun dengan struktur yang terorganisir, termasuk dataset, kode Python, dan laporan analisis.

Semua tugas di jalankan secara lokal menggunakan CUDA Environment Jupyter Notebooks & VSCode

Referensi Setup Cuda Environment
https://amansingh3110.medium.com/how-to-set-up-cuda-environment-for-jupyter-notebooks-vscode-a-comprehensive-guide-669f00ba07f7

---

## 📁 Struktur Proyek
- **Datasets**: Semua dataset yang digunakan dalam analisis.
- **Notebooks**: File `.ipynb` untuk setiap proyek, berisi kode, visualisasi, dan penjelasan ilmiah.
- **Reports**: Laporan hasil analisis dalam format PDF.
- **Screenshots**: Dokumentasi visual untuk proyek tertentu seperti Orange Data Mining.

---

## 🔍 Proyek Utama
### 1. **Regresi**
   - **Linear Regression**:
     - Dataset: `Salary_Data.csv`, `50_Startups.csv`, `Position_Salaries.csv`.
     - Implementasi menggunakan Scikit-learn dan basis fungsi.
     - Evaluasi: RMSE, MSE, R-squared.
   - **MLP Regression**:
     - Dataset: `AirQualityUCI.csv`, `winequality-red.csv`.
     - Dibangun dengan PyTorch tanpa Dropout, BatchNorm, atau regularisasi.
     - Perbandingan hyperparameter: hidden layers, activation functions, learning rates, batch sizes, dan epochs.

### 2. **Klasifikasi**
   - **Logistic Regression**:
     - Dataset: `Iris.csv`, `CitarumWater`.
     - Evaluasi menggunakan akurasi, precision, recall, F1 score, ROC, dan AUC.
   - **MLP Classification**:
     - Dataset: `winequality-red.csv`.
     - Dibangun dengan PyTorch dan hyperparameter yang bervariasi.
   - **Model Lain**:
     - Decision Tree, k-NN, XGBoost pada dataset seperti `dota2Train.csv`.

### 3. **Clustering**
   - Dataset: `Online Retail.xlsx`, `clusteringweek06.csv`.
   - Metode: K-Means, Hierarchical Clustering, DBSCAN.
   - Evaluasi: Knee Method, Silhouette Score, dan metrik tambahan.

### 4. **XGBoost**
   - Dataset: `melb_data.csv`, `tugasxgboost.csv`, `tugasxgboost2.csv`.
   - Analisis: Feature Importance, Tree Structure, SHAP Values, Partial Dependence Plot, dan Learning Curve.

---

## 📊 Tools dan Library yang Digunakan
- **Python**: Core language untuk semua implementasi.
- **Scikit-learn**: Model regresi, klasifikasi, dan clustering.
- **PyTorch**: Implementasi model MLP untuk regresi dan klasifikasi.
- **Orange Data Mining**: Model Logistic Regression dan analisis visual.
- **Google Colab**: Notebook interaktif untuk eksplorasi data dan pelatihan model.

---

## 🚀 Cara Menjalankan
1. Clone repository ini:
   ```bash
   git clone https://github.com/rrizqiaa/MachineLearningTasks.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Pilih proyek yang ingin dijalankan, buka file `.ipynb`, dan jalankan di Jupyter Notebook atau Google Colab.

---

## 📝 Kontribusi
Kontribusi sangat diterima! Silakan buka issue atau kirim pull request untuk penambahan atau perbaikan.

---

## 📄 Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

Semoga bermanfaat untuk pembelajaran dan eksplorasi pembelajaran mesin! 😊



