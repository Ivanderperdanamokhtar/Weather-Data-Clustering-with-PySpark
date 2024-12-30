# Weather-Data-Clustering-with-PySpark

## Bahasa Indonesia

### Deskripsi Proyek
Repositori ini berisi analisis dan klasterisasi data cuaca menggunakan PySpark dan algoritma pembelajaran mesin. Tujuan dari proyek ini adalah untuk mengelompokkan kondisi cuaca ke dalam klaster yang berbeda untuk memahami pola dan membuat keputusan yang lebih baik.

### Gambaran Umum
Proyek ini menganalisis dan mengelompokkan data cuaca berdasarkan fitur-fitur berikut:
- **Suhu (°C)**: Suhu udara.
- **Kelembapan (%)**: Kelembapan relatif udara.
- **Curah Hujan (mm)**: Jumlah curah hujan.
- **Kecepatan Angin (km/h)**: Kecepatan angin.

#### Sumber Data
- Data diambil dari [Kaggle - Weather Data](https://www.kaggle.com/datasets/prasad22/weather-data?resource=download).
- Dataset berisi data cuaca dari berbagai lokasi, mencakup fitur seperti suhu, kelembapan, curah hujan, dan kecepatan angin.

#### Algoritma Klasterisasi
- Algoritma **K-Means** digunakan untuk mengelompokkan data.
- Jumlah klaster optimal ditentukan menggunakan **Metode Elbow**.

#### Temuan Utama
1. **Analisis Klaster**:
   - **Klaster 0**: Suhu rendah hingga sedang, kelembapan tinggi, dan curah hujan rendah (contoh: wilayah dingin dan lembap).
   - **Klaster 1**: Suhu tinggi, kelembapan tinggi, dan curah hujan rendah (contoh: wilayah tropis yang panas).
   - **Klaster 2**: Suhu tinggi, kelembapan rendah, dan curah hujan sangat rendah (contoh: wilayah panas dan kering).
   - **Klaster 3**: Suhu rendah, kelembapan rendah, dan curah hujan rendah (contoh: wilayah dingin dan kering).

2. **Visualisasi**:
   - Metode Elbow digunakan untuk menentukan jumlah klaster optimal.
   - Plot 3D digunakan untuk menggambarkan distribusi klaster.

---

## English

### Project Description
This repository contains an analysis and clustering of weather data using PySpark and machine learning algorithms. The goal of this project is to group weather conditions into distinct clusters for better understanding and decision-making.

### Overview
The project analyzes and groups weather data based on the following features:
- **Temperature (°C)**: Air temperature.
- **Humidity (%)**: Relative humidity.
- **Precipitation (mm)**: Rainfall amount.
- **Wind Speed (km/h)**: Wind speed.

#### Data Source
- The dataset was obtained from [Kaggle - Weather Data](https://www.kaggle.com/datasets/prasad22/weather-data?resource=download).
- It contains weather data from various locations, including features like temperature, humidity, precipitation, and wind speed.

#### Clustering Algorithm
- **K-Means** algorithm is used for clustering.
- The optimal number of clusters is determined using the **Elbow Method**.

#### Key Findings
1. **Cluster Analysis**:
   - **Cluster 0**: Low to moderate temperature, high humidity, and low precipitation (e.g., cold and humid regions).
   - **Cluster 1**: High temperature, high humidity, and low precipitation (e.g., tropical climates).
   - **Cluster 2**: High temperature, low humidity, and very low precipitation (e.g., hot and dry regions).
   - **Cluster 3**: Low temperature, low humidity, and low precipitation (e.g., cold and dry regions).

2. **Visualization**:
   - The Elbow Method is used to determine the optimal number of clusters.
   - 3D plots visualize the cluster distributions.

---

## Instructions (Bahasa Indonesia & English)

### Prerequisites (Prasyarat)
- Python 3.x
- PySpark
- Matplotlib
- Seaborn

Other Contributors (Kontributor Lainnya)
- Natanael Oktavianus Partahan Sihombing
- Arsyiah Azahra
- Andini Nur Izzati
- Audrey Ribka Desmonda Manihuruk
- Barrera Putraf


