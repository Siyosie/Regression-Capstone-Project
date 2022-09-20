# About the dataset
Dataset yang digunakan merupakan dataset dari Kaggle yaitu Superstore.csv yang berisi data penjualan sejak tahun 2014-2017 dengan total 9994 baris data dengan s1 kolom.
 #   Column         Dtype  
 0   Row ID         int64  
 1   Order ID       object 
 2   Order Date     object 
 3   Ship Date      object 
 4   Ship Mode      object 
 5   Customer ID    object 
 6   Customer Name  object 
 7   Segment        object 
 8   Country        object 
 9   City           object 
 10  State          object 
 11  Postal Code    int64  
 12  Region         object 
 13  Product ID     object 
 14  Category       object 
 15  Sub-Category   object 
 16  Product Name   object 
 17  Sales          float64
 18  Quantity       int64  
 19  Discount       float64
 20  Profit         float64

# The steps taken in this project are:
-Import Packages:
    - Pandas
    - Numpy
    - Seaborn
    - Matplotlib
    - Scikit-learn
-Load datasets
- EDA
    - Descriptive statistic
    - Info dataframe
- Data Preprocessing
    - Missing Value
    - Duplicates Data
    - Outliers  Data
- Feature Enginering
    - Standardization 
    - Label Encoding
- Modeling and Model Evaluation
    -Train Test Split (70% Train and 30% Test)
    # Algorithms
    - Linear Regression
    - Statsmodel Package
    - SVM
- Business Insight
1. Secara umum, penjualan Superstore baik sales maupun profit menunjukkan kenaikkan setiap tahunnya. Kenaikan profit tertinggi terjadi dari tahun 2015 ke tahun 2016 yakni sebesar 38,74%. Namun jika dilihat dari total sales yang dihasilkan kenaikan profit dari tahun 2014 - 2015 menjadi yang paling menguntungkan mengingat kenaikan sales tahun 2014 - 2015 hanya sebesar 2,90%.
2. Prduk kategori technology memiliki angka penjualan dan profit yang cukup tinggi. Sementara prduk pada kategori furniture meski penjualannnya tinggi namun profit yang dihasilkan terbilang rendah. Seperti diketahui berdasarkan grafik sales dan profit per sub category diketahui bahwa produk pada sub category tebles memiliki angka penjualan yang tinggi namun menghaslkan negative profit(rugi).
3. Segmen pelanggan Consumer merupakan segmen pelanggan paling banyak belanja dengan total menyumbang keuntungan 47% dari total profit yang didapatkan Superstore.
4. Cunsumer segment memegang kendali atas penjualan dari ketiga kategori produk Superstore. Namun untuk meskipun penjualan produk pada kategori  furniture tinggi, namun profit yang dihasilkan sangatlah kecil. Banyak negative profit yang dihasilkan dari penjualan kategori produk ini.
5. Customer yang berada di wilayah West dan East menyumbang penjualan dan profit lebih dari 60% dari total sales dan profit yang dihasilkan Superstore.

- Saran
1. Perusahaan harus mempertahankan segmen pelanggan Consumer karena pelanggan pada segment ini menghasilkan profit yang sangat besar bagi perusahaan. Memberikan reward dan pelayanan terbaik dapat menjaga consumen tetap berbelanja di Superstore. 
2. Penjualan produk pada sub kategori tables and bookcases menghasilkan negative profit yang cukup tinggi, melakukan penjualan dengan teknik bundling dengan beberapa produk to selling dapat meminimalisir kerugian. contoh paket bundling meja dan kursi, atau bookcases and storage. 
3. Untuk alternatif lain Superstore dapat mencari another supplier yang dapat memproduksi produk tables, bookcases, and supplies yang lebih murah dengan kualitas yang mirip dari supplier sebelumnya.
4. Memberikan pelayanan terbaik dan memberikan promosi terhadap pelanggan dari wilayah West dan East mengingat penjualan dari wilayah ini merupakan yang tertinggi. Di samping itu, menambahkan iklan dan penawaran terbaik terhadap produk Superstore di wilayah Central dan South agar pelanggan lebih mengenal Superstore dan beralih belanja di Superstore.




