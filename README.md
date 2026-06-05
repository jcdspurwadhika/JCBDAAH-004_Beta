# JCBDAAH-004_Beta

# Final-Project-Telco-Customer-Churn-Analysis
Final Project yang dibuat oleh tim BETA untuk memenuhi syarat kelulusan dari kelas Job Connector Online Purwadhika
oleh Misael Trifosa dan Benhard Oktavianus.

Dengan menggunakan dataset bernama WA_Fn-UseC_-Telco-Customer-Churn.csv dari IBM

## **1. BACKGROUND**

Perusahaan telekomunikasi yang akan dibahas dalam kasus ini berlatar belakang **di tahun 2015** dan berlokasi di **California, Amerika**. (*jika merujuk pada data telco customer churn dari IBM yang telah diupdate*).

Dengan bermodalkan *subcription based income*, perusahaan telekomunikasi menawarkan metode kontrak perbulan, 1 tahunan, dan 2 tahunan. Produk yang ditawarkan dibagi menjadi 2 produk utama yaitu layanan *landline* telepon dan layanan internet yang selanjutnya memiliki produk turunan masing-masing.

Data yang diberikan akan digunakan untuk menganalisa hubungan demografi dengan tingkat *churn* pelanggan. Tingkat *churn* yang terbilang cukup tinggi pada perusahaan telco berada di *10 - 15%* (Forbes 2015 Industry Review).

Setelah mendapatkan evaluasi dari dataset ini, diharapkan dapat berguna untuk divisi **Sales & Marketing**, terlebih lagi untuk **Commercial / Marketing Director** sebagai pengambil keputusan dalam mengantisipasi pelanggan yang memiliki riwayat demografi akan *churn* sebagai pertimbangan dalam pengambilan langkah bisnis.

## **2. PROBLEM STATEMENT**

Keberadaan **pelanggan** sangat mempengaruhi **Revenue** dan **Profit** yang dapat diperoleh suatu perusahaan. **Pelanggan tetap** *(loyal)* umumnya akan **memberikan Revenue dan Profit yang lebih besar** dibandingkan pelanggan baru. Hal ini dikarenakan dalam mencari atau **menarik pelanggan baru**, perusahaan perlu mengeluarkan **modal yang besar untuk pemasarannya**. Oleh karena itu, setiap perusahaan selalu berlomba-lomba untuk mempertahankan pelanggannya dan mencegah memiliki ***churn rate*** yang tinggi.

**Masalah Utama**

`Mengetahui tingkat churn perusahaan dan mencari penyebab-penyebab churn`

**Masalah Turunan**

1. **Tingkat *Churn***: Apakah tingkat *churn* yang dimiliki perusahaan sudah sesuai dengan standar perusahaan telco atau berada dalam kategori berbahaya.
2. **Korelasi antara Tingkat *Churn* dengan Demografi**: Apakah demografi pelanggan mempengaruhi kemungkinan pelanggan untuk *churn*.
3. **Korelasi antara Tenure dengan Produk**: Apakah lamanya pelanggan dengan perusahaan mempengaruhi ketertarikan pelanggan dalam menggunakan produk perusahaan.
4. **Pengaruh Metode Pembayaran dan Kontrak layanan terhadap *Churn***: Apakah jenis kontrak atau metode pembayaran mempengaruhi keputusan pelanggan untuk *churn*.

## **3. GOALS**

Goal Bisnis yang ingin dicapai :

- **Demografi Pelanggan yang Churn**: Mengidentifikasi demografi pelanggan *churn* dan penyebab pelanggan tersebut *churn*.
- **Penurunan Tingkat Churn**: Memberikan ide yang dapat menurunkan tingkat churn sekarang menjadi lebih baik.
- **Produk Dengan Performa Buruk**: Mengidentifikasi produk yang memiliki *revenue loss* atau tingkat *churn* tinggi.
- **Metode Pembayaran dan Kontrak Layanan Buruk**: Mengidentifikasi metode pembayaran dan tipe kontrak yang sering menyebabkan *churn* pada pelanggan.

## **4. ANALYTICAL APPROACH**

Pendekatan analitik dimulai dengan proses **Exploratory Data Analysis (EDA)** sebagai fondasi utama untuk mencari korelasi dan temuan yang akan membantu stakeholder dalam menghadapi masalah dan menggapai goals yang telah ditentukan.
