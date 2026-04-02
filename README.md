# 📊 Customer Lifetime Value (CLV) Prediction

## 📌 Overview

Project ini bertujuan untuk membangun model machine learning yang dapat memprediksi Customer Lifetime Value (CLV) pada perusahaan asuransi kendaraan.

CLV merupakan metrik penting yang digunakan untuk mengukur total nilai yang dapat dihasilkan oleh seorang pelanggan selama masa hubungan dengan perusahaan. Dengan memahami CLV, perusahaan dapat mengoptimalkan strategi pemasaran, akuisisi, dan retensi pelanggan.

⸻

## 🎯 Objective
	•	Memprediksi nilai CLV pelanggan berdasarkan data historis
	•	Mengidentifikasi faktor-faktor yang memengaruhi nilai pelanggan
	•	Membantu perusahaan dalam menargetkan pelanggan bernilai tinggi

⸻

## 📂 Dataset

Dataset yang digunakan berisi informasi pelanggan asuransi, seperti:
	•	Informasi demografis (Education, Marital Status, dll)
	•	Informasi kendaraan (Vehicle Class, Coverage)
	•	Informasi finansial (Monthly Premium, Income)
	•	Informasi klaim (Total Claim Amount)
	•	Target: Customer Lifetime Value (CLV)

⸻

## 🔍 Methodology

1. Data Understanding & EDA
	•	Analisis distribusi data (numerical & categorical)
	•	Identifikasi outlier dan skewness
	•	Analisis hubungan antar fitur dengan CLV

2. Feature Engineering
	•	Claim Ratio (Total Claim Amount / Premium)
	•	Annual Premium
	•	Feature interaksi tambahan

3. Data Preprocessing
	•	Train-test split
	•	Encoding fitur kategorikal (One-Hot Encoding)
	•	Scaling (opsional, tergantung model)

4. Modeling

Beberapa model regresi yang digunakan:
	•	Linear Regression (baseline)
	•	Random Forest
	•	XGBoost