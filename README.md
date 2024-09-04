# Studi Kasus E-Commerce X tahun 2016-2018
## 1. Latar Belakang
Suatu E-Commerce X memiliki 100 ribu lebih data penjualan barang dari berbagai seller beserta reviewnya. Disini kita akan melakukan beberapa analisis dan membangun model berdasarkan data yang diberikan.

## 2. Objective
- Persebaran konsumen dan seller secara spasial
- Status pengiriman berdasarkan negara bagian
- Jumlah pemesanan berdasarkan kota
- Jumlah pemesanan per jam, per hari dan per bulan
- Produk yang banyak dijual oleh seller dan dipesan oleh konsumen berdasarkan negara bagian
- Jumlah review skor yang diterima
- Segmentasi konsumen menggunakan RFM
- Model untuk memprediksi review skor

## 3. Dataset
Data yang diberikan terpisah satu sama lain dengan kolom identifier yang sama agar memudahkan saat digabungkan. Data-data tersebut antara lain:
- Data Customers
- Data Geolocation
- Data Order Items
- Data Payments
- Data Reviews
- Data Orders
- Data Products
- Data Products Translation
- Data Sellers

Link Data: https://drive.google.com/file/d/1LpA3l60tZLX8pTcZAQtc_XDiGQOr1KjR/view?usp=drive_link

## 4. Flowchart


## 5. Analisis
- Secara spasial, seller dan konsumen sebagian besar terkonsentrasi di negara bagian SP (Sao Paulo) dan RJ (Rio de Janeiro)
- Status pengiriman terbanyak adalah delivered (97.89%) dengan konsumennya berada di negara bagian SP (Sao Paulo)
- Jumlah pemesanan terbanyak berada di kota Sao Paulo, dengan total 18582 pemesanan.
- Puncak jumlah pemesanan per jam terjadi pada pukul 10-16 dengan hari Senin. Untuk per bulan, puncaknya terjadi pada bulan November 2017 - May 2018.
-  Produk yang banyak dijual oleh seller dan dipesan oleh konsumen adalah produk bed-bath_table di negara bagian SP (Sao Paulo)
-  Jumlah review score yang diterima sebagian besar adalah skor 5 dengan persentase 56.48%. Namun terdapat skor 1 dengan persentase cukup besar yaitu 12.66%.
-  Konsumen sebagian besar masuk dalam jenis 'Big Spenders' dan diikuti oleh jenis 'Lost Cheap Customers'
-  Model yang cukup baik memprediksi review score dalam dataset ini adalah Decision Tree Classifier

## 6. Future Work
- Perlu analisis lebih lanjut pada kategori 'Others' di segmentasi RFM
- Analisis menggunakan K-Means Clustering pada segmentasi konsumen
- Menerapkan model deep learning untuk prediksi review score





