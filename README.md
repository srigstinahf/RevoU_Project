# E-Commerce User Behavior Analysis

## Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis perilaku pengguna pada platform e-commerce berdasarkan data aktivitas pengguna (*event data*). Analisis dilakukan untuk memahami pola aktivitas pengguna, tren penggunaan platform, preferensi perangkat, serta proses konversi dari pencarian produk ke aktivitas penambahan produk ke keranjang belanja.

Proyek ini menggunakan Python untuk proses data cleaning dan exploratory data analysis (EDA), serta Google Sheets/Excel untuk pengolahan data, analisis tambahan, dan pembuatan dashboard. Link sheets: https://docs.google.com/spreadsheets/d/1SEwRPfnftOkhTOhkWIox6JhOO8YSb-HRYrRBA4JaJOQ/edit?usp=sharing

## Tools yang Digunakan

- Python
- Pandas
- Matplotlib / Seaborn
- Google Colab
- Google Sheets / Microsoft Excel

## Dataset

Dataset terdiri dari 10.000 baris data dengan 9 kolom yang mencakup informasi:
- Event ID
- User ID
- Session ID
- Event Type
- Event Timestamp
- Product ID
- Country
- Device
- Channel

## Tahapan Analisis

1. **Data Understanding**  
   Memahami struktur dataset, jumlah data, tipe data, dan karakteristik setiap kolom.

2. **Data Cleaning**  
   Memeriksa missing values, memvalidasi tipe data, serta menangani nilai yang tidak tersedia sesuai karakteristik datanya.

3. **Exploratory Data Analysis (EDA)**  
   Menganalisis distribusi aktivitas pengguna, pengguna aktif berdasarkan negara, tren aktivitas bulanan, dan penggunaan perangkat.

4. **User Behavior Analysis**  
   Menganalisis aktivitas pencarian produk (*search*) dan penambahan produk ke keranjang (*add to cart*).

5. **Data Visualization & Dashboard**  
   Menyajikan hasil analisis melalui grafik, tabel, dan dashboard agar informasi lebih mudah dipahami.

## Hasil Analisis

Beberapa analisis yang dilakukan dalam proyek ini meliputi:

- Distribusi jenis aktivitas pengguna (*event distribution*).
- Pengguna aktif berdasarkan negara.
- Tren aktivitas pengguna berdasarkan bulan.
- Aktivitas pengguna berdasarkan channel.
- Penggunaan perangkat Android, iOS, dan desktop.
- Analisis aktivitas Search to Add to Cart.

## Key Insights

- Dataset mencakup 10.000 aktivitas pengguna.
- Aktivitas terbanyak adalah `page_view`, diikuti `product_view`.
- Android merupakan perangkat dengan jumlah aktivitas tertinggi.
- Indonesia menjadi negara dengan jumlah pengguna aktif tertinggi pada periode Q2.
- Analisis Search to Add to Cart digunakan untuk mengidentifikasi pengguna yang melakukan aktivitas penambahan produk ke keranjang setelah pencarian pada hari yang sama.

## Output Proyek

- Notebook analisis Python.
- File spreadsheet hasil pengolahan dan analisis.
- Dashboard visualisasi.
- Ringkasan insight berdasarkan hasil analisis.

## Kesimpulan

Proyek ini memberikan gambaran mengenai pola aktivitas pengguna pada platform e-commerce. Hasil analisis dapat digunakan sebagai bahan evaluasi awal untuk memahami aktivitas pengguna, penggunaan perangkat, efektivitas channel, dan perilaku pengguna dalam proses pencarian hingga penambahan produk ke keranjang belanja.

