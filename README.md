# Analyzing-eCommerce-Business-Performance-with-SQL
## ✏️ **Rumusan Masalah**
Mengukur performa bisnis merupakan suatu hal yang sangat penting bagi sebuah perusahaan. Ini akan membantu dalam memantau, dan menilai keberhasilan atau kegagalan dari berbagai proses bisnis. Pengukuran performa bisnis dapat dilakukan dengan memperhitungkan beberapa metrik bisnis. Dalam poyek ini akan dilakukan analisis performa bisnis suatu perusahaan eCommerce dengan dengan metrik bisnis yaitu pertumbuhan pelanggan, kualitas produk, dan tipe pembayaran berdasarkan historical data selama tiga tahun.

## ✏️ **Objektif**
Mengumpulkan insight dari analisis dan dengan visualisasi berupa :
1. [**Annual Customer Activity Growth**](https://github.com/faizns/Analyzing-eCommerce-Business-Performance-with-SQL/blob/main/README.md#1-annual-customer-activity-growth)
2. [**Annual Product Category Quality**](https://github.com/faizns/Analyzing-eCommerce-Business-Performance-with-SQL/blob/main/README.md#2-annual-product-category-quality
)
3. [**Annual Payment Type Usage**](https://github.com/faizns/Analyzing-eCommerce-Business-Performance-with-SQL/blob/main/README.md#3-annual-payment-type-usage)

## ✏️ **Preparasi Data**
Dataset yang digunakan adalah dataset sebuah perusahaan eCommerce Brasil yang memiliki informasi pesanan dengan jumlah 99441 dari tahun 2016 hingga 2018. Terdapat fitur-titur yang membuat informasi seperti status pemesanan, lokasi, rincian item, jenis pembayaran, serta ulasan.

**Tabel yang digunakan:**
- customers_dataset
- sellers_dataset
- product_dataset
- geolocation_dataset
- orders_dataset
- order_items_dataset
- order_payments_dataset
- order_reviews_dataset

**Langkah-langkah yang dilakukan meliputi:**
1. Membuat workspace database di dalam pgAdmin dan membuat tabel menggunakan `CREATE TABLE` statement
2. Melakukan import data csv kedalam database
3. Menentukan Primary Key atau Foreign Key enggunakan statement `ALTER TABLE`
4. Membuat dan mengeksport ERD (Entity Relationship Diagram) <br>


# Data Preparation 

# Annual Customer Activity Growth Analysis
![acg 1](https://user-images.githubusercontent.com/118154539/215446005-d446920e-fd7b-4a42-8e9a-9e5296488ce1.png)
![acg2](https://user-images.githubusercontent.com/118154539/215446034-b3bed590-7ea2-4a6b-88f2-f40fbe4928af.jpg)

### Dari data dapat dilihat terjadi lonjakan customer baik customer baru atau costumer aktif di 2016 ke 2017, namun Dari 2017 ke 2018 peningkatannya tidak terlalu signifikan. Dari grafik dapat di lihat bahwaperbandingan customer baru dengan customer aktif cukup signifikan, berarti customer bari ini belum melakukan reapeat order, Maka perlu di adakan evaluasi untuk meningkatkam ke aktifan dari customer bari ini, mungkin bisa dengan menggunakam promo khusus Dan melakukan tactic marketing agar para new customer bisa menjadi customer active


# Annual Product Category Quality Analysis
![pca](https://user-images.githubusercontent.com/118154539/215446422-dcdc7e33-df84-425a-b2e3-b69a5f60f542.png)
 
 ### Health and beauty menjadi best seller item dan most canceled item Health and beauty mendominasi seluruh transaksi di ecommer

# Annual Payment Usage Analysis
