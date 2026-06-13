# Kimia Farma Business Performance Dashboard (Google Looker Studio)
## 📌 Project Type
Final Project Big Data Analytics Virtual Internship Program – Kimia Farma x Rakamin Academy
## 📊 Overview
Project ini merupakan dashboard interaktif berbasis Google Looker Studio yang dikembangkan untuk menganalisis performa bisnis Kimia Farma selama periode 2020–2023.

Fokus utama dari project ini adalah mengolah data transaksi, produk, dan cabang menjadi informasi yang terstruktur, konsisten, dan mudah dianalisis. Proses yang dilakukan mencakup data integration, data transformation, perhitungan metrik bisnis, serta visualisasi data untuk mendukung pengambilan keputusan berbasis data.
## 🎯 Objectives
- Menyajikan ringkasan performa bisnis melalui KPI utama
- Menganalisis tren Net Sales dan Net Profit dari waktu ke waktu
- Mengidentifikasi provinsi dengan kontribusi Net Sales, Net Profit, dan Total Transactions tertinggi
- Mengevaluasi distribusi transaksi berdasarkan jenis cabang
- Mengidentifikasi cabang dengan Branch Rating tinggi namun Transaction Rating relatif rendah
- Menyediakan dashboard interaktif yang dapat dieksplorasi berdasarkan periode dan wilayah
## ⚙️ Data Processing
- Data integration dari beberapa tabel menggunakan Google BigQuery
- Data cleaning untuk memastikan konsistensi dan kualitas data
- Pembuatan calculated fields
- Agregasi dan transformasi data menggunakan SQL
## 🧠 Business Logic
- Net Sales dihitung dari harga setelah dikurangi diskon (`actual_price × (1 - discount_percentage)`)
- Net Profit dihitung dari hasil perkalian `Net Sales × Gross Profit Percentage`
- Average Order Value (AOV) dihitung dari total Net Sales dibagi total transaksi
- Top Provinces ditentukan berdasarkan agregasi Net Sales, Net Profit, atau Total Transactions
- Analisis High Branch Rating but Low Transaction Rating digunakan untuk mengidentifikasi cabang dengan kualitas cabang yang baik namun memiliki pengalaman transaksi yang relatif lebih rendah
## 🛠️ Tools & Skills
- SQL (Google BigQuery)
- Google Looker Studio
- Data integration
- Data cleaning
- Data transformation
- Data visualization & dashboard design
- Business analysis
## 🖼️ Preview
Berikut dashboard interaktif yang dapat dieksplorasi secara langsung melalui Google Looker Studio:
https://datastudio.google.com/reporting/d9ebdcb6-f087-4888-bd14-1a0716777eed
<img width="2500" height="3020" alt="Kimia Farma Business Performance - PBI Rakamin" src="https://github.com/user-attachments/assets/bc9c8bb3-f635-46c7-a7cf-6c25c128a6cc" />

## 📊 Dashboard Highlights
- Kimia Farma menghasilkan net sales sebesar Rp321,17 miliar dan net profit sebesar Rp91,21 miliar dari 672,5 ribu transaksi selama periode 2020–2023. Nilai average order value (AOV) tercatat sebesar Rp477,61 ribu, dengan rata-rata transaction rating 4,00 dan branch rating 4,45.
- Tren net sales dan net profit menunjukkan pola yang relatif stabil sepanjang periode analisis dengan pergerakan yang cenderung searah. Fluktuasi pada net profit mengikuti perubahan net sales, mengindikasikan bahwa pertumbuhan penjualan berkontribusi langsung terhadap peningkatan profit perusahaan.
- Jawa Barat menjadi provinsi dengan kontribusi terbesar terhadap kinerja perusahaan, mencatat net sales sebesar Rp94,87 miliar, net profit sebesar Rp26,94 miliar, dan 198,72 ribu transaksi, menjadikannya wilayah dengan performa terbaik selama periode analisis.
- Distribusi transaksi berdasarkan jenis cabang relatif seimbang, dengan masing-masing kategori cabang menyumbang sekitar 33% dari total transaksi. Hal ini menunjukkan bahwa aktivitas bisnis tidak bergantung pada satu tipe cabang tertentu.
- Visualisasi geografis memperlihatkan bahwa distribusi net profit tersebar di seluruh Indonesia, namun didominasi oleh beberapa provinsi dengan aktivitas bisnis tinggi, terutama Jawa Barat, yang menjadi kontributor profit terbesar.
- Analisis terhadap cabang dengan branch rating tinggi namun transaction rating rendah menunjukkan adanya beberapa cabang yang memiliki kualitas cabang yang baik, tetapi belum diikuti oleh pengalaman transaksi pelanggan yang optimal. Temuan ini mengindikasikan adanya peluang peningkatan kualitas layanan pada proses transaksi.
