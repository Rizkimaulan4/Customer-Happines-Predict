# 📊 Customer Happiness Prediction App

Aplikasi berbasis **Machine Learning** untuk memprediksi apakah seorang customer merasa **happy atau tidak** berdasarkan data logistik dan transaksi.

Project ini mengubah model Machine Learning menjadi **aplikasi web interaktif** menggunakan **Streamlit**.

---

## 🌐 Live Demo

Coba langsung tanpa install:

👉 https://customer-happines-predict.streamlit.app/

---

## 📌 Overview

Project ini bertujuan untuk:

* Mengolah data customer
* Membangun model prediksi kepuasan pelanggan
* Mengimplementasikan model ke dalam aplikasi web interaktif

Aplikasi ini dirancang agar **user non-teknis** dapat langsung menggunakan model tanpa perlu coding.

---

## 🚀 Features

* Input data customer secara manual
* Prediksi Happy / Not Happy secara real-time
* Probabilitas kepuasan pelanggan
* Insight & rekomendasi bisnis
* Multi-page app:

  * Home
  * Prediction
  * Final Thoughts

---

## 🛠 Tech Stack

* Python
* Streamlit
* Scikit-learn
* Pandas
* NumPy
* Joblib

---

## 🧑‍💻 Cara Menggunakan (User / Pengunjung)

### 🔹 Versi Online (Paling Mudah)

1. Klik link berikut:
   👉 https://customer-happines-predict.streamlit.app/
2. Masuk ke halaman **Prediction**
3. Isi data customer
4. Klik tombol **Predict**
5. Lihat hasil prediksi

---

## 🧑‍💻 Cara Menjalankan Project Secara Lokal (Full Setup)

Ikuti langkah berikut untuk menjalankan aplikasi di komputer lokal:

```bash
# ================================
# 🚀 STEP 1 — CLONE REPOSITORY
# ================================
git clone https://github.com/Rizkimaulan4/Customer-Happines-Predict.git

# ================================
# 📂 STEP 2 — MASUK KE PROJECT
# ================================
cd Customer-Happines-Predict

# ================================
# 🧪 STEP 3 — BUAT VIRTUAL ENV
# ================================
python -m venv venv

# ================================
# ⚡ STEP 4 — AKTIFKAN ENV
# ================================

# Windows
venv\Scripts\activate

# Mac / Linux
source venv/bin/activate

# ================================
# 📦 STEP 5 — INSTALL DEPENDENCIES
# ================================
pip install --upgrade pip
pip install -r requirements.txt

# ================================
# ▶️ STEP 6 — JALANKAN APP
# ================================
streamlit run 01_Home.py

# ================================
# 🌐 STEP 7 — AKSES DI BROWSER
# ================================
# http://localhost:8501
```

---

## ⚠️ Troubleshooting (Kalau Error)

### ❌ Streamlit tidak dikenali

```bash
pip install streamlit
```

### ❌ Module tidak ditemukan

```bash
pip install -r requirements.txt
```

### ❌ Port sudah digunakan

```bash
streamlit run 01_Home.py --server.port 8502
```

### ❌ Model tidak terbaca

Pastikan file berikut ada di folder utama:

* model.pkl
* scaler.pkl

---

## 📁 Project Structure

```
Customer-Happines-Predict/
│
├── 01_Home.py
├── pages/
│   ├── 02_Predict.py
│   └── 03_Final Thoughts.py
├── model.pkl
├── scaler.pkl
├── requirements.txt
```

---

## 📌 Key Insight

Customer satisfaction sangat dipengaruhi oleh **kualitas layanan pengiriman**,
di mana delivery charges berperan sebagai indikator service level, bukan sekadar biaya.

---

## 👨‍💻 Author

Rizky Maulana
