# Food Waste Intelligence
### AI-Powered Food Demand Forecasting and Waste Reduction System

## 1. Deskripsi Proyek

Food Waste Intelligence merupakan sebuah platform digital berbasis Machine Learning dan Artificial Intelligence yang dirancang untuk membantu pelaku usaha kuliner, khususnya bakery, dalam mengoptimalkan jumlah produksi makanan dan mengurangi pemborosan bahan pangan (food waste).

Permasalahan utama yang ingin diselesaikan adalah ketidaksesuaian antara jumlah produk yang diproduksi dengan permintaan konsumen. Produksi yang terlalu banyak dapat menyebabkan makanan tidak terjual dan berakhir menjadi limbah, sedangkan produksi yang terlalu sedikit dapat menyebabkan kehilangan peluang penjualan.

Untuk mengatasi permasalahan tersebut, Food Waste Intelligence memanfaatkan data historis penjualan, karakteristik produk, kondisi cuaca, hari penjualan, dan aktivitas promosi sebagai dasar analisis dan prediksi permintaan.

Sistem menggunakan Machine Learning untuk mempelajari pola penjualan dan memperkirakan jumlah produk yang berpotensi terjual pada hari berikutnya. Hasil prediksi kemudian digunakan untuk menghasilkan rekomendasi jumlah produksi yang lebih optimal.

Selain itu, Generative AI diintegrasikan untuk memberikan penjelasan hasil analisis serta rekomendasi strategi pengurangan makanan terbuang berdasarkan informasi yang dihasilkan oleh model Machine Learning.

## 2. Latar Belakang Masalah

Food waste merupakan salah satu permasalahan yang dapat menyebabkan kerugian ekonomi bagi pelaku usaha makanan sekaligus memberikan dampak negatif terhadap lingkungan.

Pada usaha bakery, produk makanan umumnya diproduksi berdasarkan perkiraan permintaan. Ketika perkiraan tersebut tidak sesuai dengan kondisi penjualan sebenarnya, produk yang tidak terjual berpotensi menjadi limbah.

Sebagian pelaku usaha masih mengandalkan pengalaman dan perkiraan manual dalam menentukan jumlah produksi. Pendekatan tersebut belum tentu mampu menangkap perubahan pola permintaan yang dipengaruhi oleh berbagai faktor.

Oleh karena itu, diperlukan solusi berbasis teknologi yang dapat membantu pelaku usaha memahami pola penjualan, memperkirakan permintaan, dan mengambil keputusan produksi berdasarkan data.

## 3. Tujuan Proyek

1. Membantu pelaku usaha bakery memperkirakan permintaan produk berdasarkan data historis penjualan.
2. Mengoptimalkan jumlah produksi berdasarkan hasil prediksi permintaan.
3. Mengidentifikasi produk yang memiliki potensi menghasilkan food waste.
4. Menyediakan informasi analisis penjualan dan pemborosan makanan.
5. Memberikan rekomendasi berbasis AI untuk membantu pengambilan keputusan bisnis.
6. Mendukung upaya pengurangan limbah makanan melalui pemanfaatan teknologi.

## 4. Fitur Utama

### A. Sales and Production Tracking
Fitur untuk mencatat aktivitas produksi dan penjualan produk bakery, termasuk jumlah produk yang diproduksi, terjual, dan tersisa.

### B. Machine Learning Demand Forecasting
Menggunakan algoritma Machine Learning untuk memprediksi jumlah permintaan produk berdasarkan pola historis penjualan dan variabel pendukung lainnya.

### C. Food Waste Analysis
Menganalisis jumlah makanan yang tidak terjual, mengidentifikasi produk dengan tingkat pemborosan tertinggi, dan menghitung estimasi kerugian ekonomi.

### D. Production Recommendation
Memberikan rekomendasi jumlah produksi berdasarkan hasil prediksi permintaan dengan mempertimbangkan kebutuhan cadangan dan kebijakan operasional usaha.

### E. AI-Powered Insights
Mengintegrasikan Generative AI untuk menjelaskan hasil prediksi, mengidentifikasi potensi masalah, dan memberikan rekomendasi strategi pengurangan food waste.

## 5. Teknologi yang Digunakan

| Teknologi | Fungsi |
|---|---|
| Laravel | Backend dan pengelolaan data |
| React | Pengembangan antarmuka pengguna |
| Inertia.js | Penghubung Laravel dan React |
| Python | Pengembangan Machine Learning |
| Pandas & NumPy | Pengolahan dan analisis data |
| Scikit-learn | Training dan evaluasi model |
| FastAPI | Menyediakan layanan prediksi ML |
| Generative AI API | Analisis dan rekomendasi berbasis AI |
| MySQL | Penyimpanan data aplikasi |

## 6. Cara Kerja Sistem

1. Pengguna memasukkan data produksi dan penjualan produk.
2. Sistem menyimpan data historis ke database.
3. Data diproses untuk menghasilkan fitur yang diperlukan model Machine Learning.
4. Model memprediksi permintaan produk pada periode berikutnya.
5. Sistem membandingkan prediksi permintaan dengan rencana produksi.
6. Hasil analisis ditampilkan dalam dashboard.
7. Generative AI memberikan penjelasan dan rekomendasi berdasarkan hasil analisis.

## 7. Target Pengguna

Target pengguna utama Food Waste Intelligence adalah pemilik dan pengelola usaha bakery skala kecil dan menengah yang ingin meningkatkan efisiensi produksi dan mengurangi kerugian akibat produk yang tidak terjual.

Dalam pengembangan selanjutnya, sistem berpotensi diperluas untuk digunakan oleh restoran, kafe, katering, dan berbagai jenis usaha kuliner lainnya.

## 8. Dampak yang Diharapkan

Food Waste Intelligence diharapkan dapat membantu pelaku usaha beralih dari pengambilan keputusan berdasarkan perkiraan manual menuju pengambilan keputusan yang lebih terukur dan berbasis data.

Melalui prediksi permintaan dan rekomendasi produksi, sistem diharapkan mampu mengurangi potensi makanan terbuang, meningkatkan efisiensi operasional, serta membantu pelaku usaha mengelola sumber daya secara lebih optimal.

## 9. Pengembangan Masa Depan

Beberapa pengembangan yang dapat dilakukan antara lain:

- Integrasi data penjualan secara otomatis dari sistem kasir.
- Prediksi permintaan berdasarkan jam operasional.
- Pengembangan model untuk berbagai kategori usaha kuliner.
- Rekomendasi strategi diskon untuk produk yang berisiko tidak terjual.
- Analisis dampak pengurangan food waste terhadap biaya operasional.
- Pengembangan model prediksi yang dapat diperbarui menggunakan data transaksi aktual.

**Food Waste Intelligence — Turning Sales Data into Smarter Production Decisions.**
