# prediksi-bantuan-dana-desa
Model prediksi kelayakan penerima bantuan Dana Desa di Kampung Sawah menggunakan Random Forest, SMOTE, Permutation Importance, dan SHAP.

# Prediksi Kelayakan Penerima Bantuan Dana Desa Menggunakan Random Forest & SHAP

Repositori ini berisi kode sumber dan analisis untuk penelitian berjudul **"Prediksi Kelayakan Penerima Penerima Bantuan Dana Desa Kampung Sawah Menggunakan Algoritma Random Forest"**. Studi kasus dilakukan di Desa Kampung Sawah, Kecamatan Rumpin, Kabupaten Bogor[cite: 1].

## 📌 Deskripsi Proyek
Penentuan penerima bantuan Dana Desa sering kali menghadapi kendala subjektivitas dan ketimpangan data (*class imbalance*)[cite: 1]. Proyek ini membangun pipeline *machine learning* komprehensif yang mencakup:
1. **Penanganan Class Imbalance** menggunakan **SMOTE** (Synthetic Minority Over-sampling Technique)[cite: 1].
2. **Feature Selection** berbasis **Permutation Importance** untuk mereduksi dimensi data tanpa menurunkan performa[cite: 1].
3. **Interpretabilitas Model** tingkat global dan lokal menggunakan **SHAP** (SHapley Additive exPlanations)[cite: 1].

## 📊 Hasil Performa Model
Berdasarkan pengujian pada beberapa skenario pembagian data, skenario **80:20** dengan 9 fitur terpilih menghasilkan performa terbaik:
* **Accuracy:** 95.83%[cite: 1]
* **Precision:** 95.00%[cite: 1]
* **Recall:** 86.36%[cite: 1]
* **F1-Score:** 90.48%[cite: 1]
* **ROC-AUC:** 96.93%[cite: 1]

Fitur paling berpengaruh dalam menentukan kelayakan bantuan adalah **Pendapatan**, **Umur**, **Status Kawin**, dan **Jumlah Tanggungan**[cite: 1].

## 🛠️ Teknologi yang Digunakan
* **Language:** Python[cite: 1]
* **Environment:** Google Colab[cite: 1]
* **Libraries:** Scikit-learn, Imbalanced-learn, SHAP, Pandas, NumPy, Matplotlib, Seaborn[cite: 1]

## 👤 Author
* **Tajul Alamsyah**[cite: 1]
