# 🛒 Supermarket Sales Analysis

![Python](https://img.shields.io/badge/python-3.10-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-data%20analysis-green)
![Matplotlib](https://img.shields.io/badge/matplotlib-visualization-red)
![Seaborn](https://img.shields.io/badge/seaborn-statistical%20plot-purple)
![Status](https://img.shields.io/badge/status-completed-success)

Analisis data penjualan supermarket menggunakan Python untuk menemukan pola penjualan, perilaku pelanggan, dan insight bisnis berbasis data. Project ini melakukan data cleaning, exploratory data analysis (EDA), visualisasi, feature engineering, dan business recommendation.

Project ini dibuat sebagai portfolio Data Analyst untuk menunjukkan kemampuan data analysis, data visualization, dan business insight extraction.

---

# 📌 Project Overview

Dataset berisi 1000 transaksi penjualan supermarket yang mencakup:

- Customer behavior
- Product sales
- Payment methods
- Revenue
- Customer rating
- Transaction details

Project ini bertujuan mengubah data mentah menjadi insight yang dapat membantu pengambilan keputusan bisnis.

---

# 🎯 Objectives

- Memahami tren penjualan berdasarkan kota dan waktu
- Menganalisis preferensi pelanggan
- Mengidentifikasi produk dengan performa terbaik
- Mengevaluasi metode pembayaran
- Menghasilkan insight bisnis dan rekomendasi
- Melakukan feature engineering untuk analisis lanjutan

---

# 📊 Business Questions

Project ini menjawab beberapa pertanyaan bisnis:

- Kota mana menghasilkan revenue tertinggi?
- Produk apa yang paling menghasilkan?
- Bagaimana perilaku customer berdasarkan tipe?
- Metode pembayaran apa yang paling sering digunakan?
- Bagaimana tren penjualan setiap bulan?
- Apakah membership mempengaruhi spending?

---

# 📂 Dataset Information

Dataset: `Supermarket Sales.csv`

## Dataset Features
- Invoice ID
- Branch
- City
- Customer type
- Gender
- Product line
- Unit price
- Quantity
- Tax
- Total
- Date
- Time
- Payment
- Rating

---

# ⚙️ Data Processing

## Data Cleaning
- Convert Date ke format datetime
- Cek missing values
- Feature extraction (Year, Month, Day)

## Feature Engineering
- Revenue Category (High / Low)
- Spend per Item
- Estimated Profit (20% dari total transaksi)

---

# 🔍 Exploratory Data Analysis (EDA)

## Analysis Performed

### Sales Analysis
- Total transaksi
- Total revenue
- Revenue per city
- Revenue per product line

### Customer Analysis
- Customer type vs spending
- Gender vs spending
- Customer rating distribution

### Payment Analysis
- Distribusi metode pembayaran

### Time Analysis
- Monthly sales trend

### Statistical Analysis
- Correlation matrix antar variabel

---

# 📈 Data Visualization

Project ini menghasilkan beberapa visualisasi:

- 📊 Total Sales by City (Bar Chart)
- 📊 Revenue by Product Line
- 🥧 Payment Method Distribution
- 📉 Monthly Sales Trend
- 📊 Customer Rating Distribution
- 📦 Customer Type vs Spending (Boxplot)
- 🔥 Correlation Heatmap

---

# 💡 Key Insights

## 🏙 Revenue Tertinggi — Naypyitaw
- Permintaan tinggi di wilayah tersebut
- Potensi ekspansi bisnis

## 🍔 Produk Terlaris — Food & Beverages
- Demand tinggi
- Perlu optimasi stok dan pemasaran

## 💳 Pembayaran Dominan — E-Wallet
- Customer prefer cashless
- Sistem pembayaran harus optimal

## 👥 Member Spend Lebih Besar
- Program membership efektif
- Loyalty program perlu ditingkatkan

## 📅 Sales Trend Fluktuatif
- Ada faktor seasonal
- Perlu strategi inventory planning
