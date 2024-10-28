# Latar Belakang

## Description

Di era digital seperti saat ini, **Supermarket** harus melakukan berbagai cara untuk menarik lebih banyak pelanggan. Salah satu cara yang dilakukan adalah menggunakan berbagai saluran *(channel)* penjualan. Setiap saluran menawarkan pengalaman belanja yang berbeda dan dapat memengaruhi keputusan pembelian pelanggan. Perusahaan perlu memahami dengan baik bagaimana pelanggan berinteraksi dengan setiap saluran penjualan untuk memaksimalkan pengalaman pelanggan, meningkatkan penjualan, dan mengoptimalkan sumber daya yang digunakan pada setiap saluran.

Berdasarkan dataset yang dimiliki sebuah Supermarket di **Amerika Serikat**, terdapat informasi mengenai pembelian pelanggan melalui beberapa *channel*, yaitu penjualan melalui **website**, **katalog**, dan **toko fisik**. Selain itu, **data kunjungan situs web** juga dapat memberikan gambaran tentang intensitas penggunaan *online channel*, serta **data demografi pelanggan**, **data pembelian produk**, dan **data promosi yang sudah dilakukan** untuk menentukan strategi pemasaran yang sesuai dengan segmentasi pelanggan.

## Table of Contents

- [Pernyataan Masalah](#pernyataan-masalah)
- [Library yang Digunakan](#library-yang-digunakan)
- [Dataset yang Digunakan](#dataset-yang-digunakan)
- [Pemahaman dan Penanganan Data](#pemahaman-dan-penanganan-data)
- [Analisis Data](#analisis-data)
- [Kesimpulan](#kesimpulan)

## Pernyataan Masalah

Supermarket ini ingin memahami lebih dalam mengenai bagaimana pelanggan berinteraksi dengan berbagai saluran penjualan yang tersedia agar dapat meningkatkan pengalaman pelanggan dan memaksimalkan penjualan pada setiap saluran. Permasalahan yang ingin diselesaikan meliputi:

1. Bagaimana preferensi pelanggan terhadap berbagai saluran penjualan?
2. Bagaimana kontribusi setiap saluran penjualan terhadap penjualan keseluruhan?
3. Bagaimana hubungan antara data demografis, promosi, dan loyalitas dengan saluran penjualan yang digunakan oleh pelanggan?

## Library yang Digunakan

Project ini menggunakan beberapa library Python populer untuk analisis data, yaitu:

- **Pandas**: Digunakan untuk memanipulasi dan menganalisis data.
- **NumPy**: Digunakan untuk operasi numerik.
- **Matplotlib dan Seaborn**: Digunakan untuk visualisasi data.
- **Scikit-learn**: Digunakan untuk penerapan model machine learning sederhana.

## Dataset yang Digunakan

Dataset yang digunakan dalam project ini mencakup informasi tentang:

- **Data demografi pelanggan**: Meliputi usia, status perkawinan, pendidikan, dan pendapatan.
- **Data pembelian**: Jumlah pembelian melalui website, katalog, dan toko fisik.
- **Data kunjungan situs web**: Frekuensi kunjungan pelanggan ke website supermarket.
- **Data promosi**: Respon pelanggan terhadap kampanye promosi yang dilakukan.

Dataset ini menyediakan informasi penting yang digunakan untuk analisis segmentasi pelanggan dan preferensi terhadap saluran penjualan.

## Pemahaman dan Penanganan Data

Pada tahap ini, dilakukan beberapa langkah untuk memastikan kualitas data:

1. **Menangani Nilai yang Hilang *(Missing Value)* di Kolom `Income`**: Menggunakan teknik imputasi median untuk menangani nilai pendapatan yang hilang.
2. **Menangani Data Tanggal dalam Kolom `Dt_Customer`**: Mengubah format data tanggal untuk analisis keterbaruan interaksi pelanggan.
3. **Menangani Data *Outliers* di Kolom `Year_Birth` dan `Income`**: Menghapus data yang dianggap tidak realistis atau tidak relevan.
4. **Menangani Data di Kolom `Education` dan `Marital_Status`**: Menggabungkan beberapa kategori untuk menyederhanakan analisis.
5. **Menambahkan Kolom Baru yang Diperlukan**: Menambahkan kolom seperti `Customer_Age` untuk membantu analisis lebih lanjut.
6. **Menghapus Kolom yang Tidak Digunakan**: Menghapus kolom yang tidak relevan untuk analisis.

## Analisis Data

Pada tahap ini, dilakukan analisis untuk menjawab permasalahan yang telah diidentifikasi:

1. **Preferensi Pelanggan Terhadap Saluran Penjualan**: Menganalisis saluran mana yang paling sering digunakan oleh pelanggan.
2. **Kontribusi Setiap Saluran Penjualan Terhadap Penjualan Keseluruhan**: Mengukur seberapa besar kontribusi masing-masing saluran penjualan.
3. **Frekuensi Interaksi dengan *Online Channel* dan Korelasinya dengan Pembelian**: Mengidentifikasi korelasi antara frekuensi kunjungan situs web dan pembelian produk.
4. **Saluran Penjualan yang Kurang Efektif**: Menentukan saluran penjualan mana yang memberikan dampak paling kecil terhadap penjualan.
5. **Analisis Demografis Pelanggan dengan Saluran Penjualan**: Mengidentifikasi segmen pelanggan berdasarkan usia, pendapatan, dan preferensi saluran penjualan.
6. **Analisis Hubungan Produk dengan Saluran Penjualan**: Menentukan produk mana yang lebih sering dibeli melalui saluran tertentu.
7. **Analisis Hubungan Promosi dengan Saluran Penjualan**: Mengukur efektivitas kampanye promosi terhadap saluran penjualan tertentu.
8. **Hubungan antara Kepuasan Pelanggan dan Saluran Penjualan**: Menggunakan data kepuasan pelanggan untuk menganalisis saluran yang memberikan pengalaman terbaik.
9. **Hubungan Loyalitas Pelanggan dengan Saluran Penjualan**: Menilai tingkat loyalitas pelanggan berdasarkan preferensi saluran.
10. **Analisis Segmentasi Pelanggan Berdasarkan Saluran Penjualan**: Menggunakan clustering untuk menentukan segmentasi pelanggan.

## Kesimpulan

Dari hasil analisis yang dilakukan, dapat disimpulkan bahwa:

- Saluran **website** dan **katalog** lebih disukai oleh segmen pelanggan tertentu dibandingkan toko fisik.
- **Promosi** yang ditargetkan dengan tepat memiliki dampak positif terhadap penjualan melalui saluran online.
- Segmentasi pelanggan membantu dalam memahami bagaimana menargetkan kampanye pemasaran yang lebih efektif.

Project ini memberikan wawasan yang dapat digunakan oleh **Supermarket** untuk meningkatkan strategi pemasaran mereka, mengoptimalkan penggunaan setiap saluran penjualan, dan meningkatkan pengalaman pelanggan.

## Cara Menggunakan Repository Ini

1. Clone repository ini ke lokal Anda menggunakan perintah:
   ```bash
   git clone <repository_url>
   ```
2. Install library yang diperlukan menggunakan `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```
3. Buka file notebook `.ipynb` untuk menjalankan analisis langkah demi langkah.

## Struktur Repository

- `Capstone Project 2_Rafli Fauzan Andara.ipynb`: File notebook utama yang berisi seluruh analisis.
- `data/`: Folder yang berisi dataset yang digunakan dalam project ini.
- `images/`: Folder yang berisi visualisasi yang dihasilkan dari analisis.
- `requirements.txt`: File yang berisi daftar library yang diperlukan untuk menjalankan project ini.

## Kontribusi

Jika Anda ingin berkontribusi pada project ini, silakan buat **pull request** atau buka **issue** untuk diskusi lebih lanjut.

## Lisensi

Project ini dilisensikan di bawah **MIT License**. Silakan lihat file `LICENSE` untuk detail lebih lanjut.
