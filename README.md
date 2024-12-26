# Belajar-data-analisis

1. Buka file Belajar Analisis Data dengan Python.ipynb dan eksekusi semual sel secara sekuensial dari atas ke bawah. Flow proses dari keseluruhan proses dapat dilihat pada runtutan seperti di bawah ini.


A. Melakukan data wrangling.
Untuk melakukan data wrangling terdapat beberapa hal yang harus dilakukan seperti gathering data, assessing data, dan juga cleaning data.
1. Gathering data
   * Lakukan impor library terlebih dahulu seperti pandas, matplotlib, dan juga seaborn
   * Tampilkan 5 teratas dari dataset
   * Tampilkan juga ringkasan statistik dari masing-masing dataset dengan menggunakan       .describe
2. Assessing data: Asessing data ini berfungsi untuk melihat apakah terdapat data yang kotor seperti missing value, invalid value, duplicate data, inaccurate value, incosistent value, dan juga outlier, 
   * Perhitungan missing value dilakukan dengan menggunakan library pandas yang            dipadukan sum() dan didapatkan angka 0 untuk missing value yang artinya tidak         ada data yang hilang
   * Perhitungan duplikasi data dapat dilakukan dengan metode duplicated dan               didapatkan nilai 0 sehingga ditemukan tidak ada duplikasi sama sekali.
   * Dari asessing data ditemukan bahwa tipe sudah sesuai untuk analisis proses            selanjutnya kecuali terdapat kolom dteday yang perlu dikonversi menjadi tipe          datetime (format tunggal)
3. Cleaning data: Cleaning data merupakan tindak lanjut dari asessing data yaitu tahap penyelesaian masalah untuk masalah yang ditemukan assessing data.
   * Masalah yang ditemukan adalah adanya kolom dteday yang harus dikonversi menjadi       tipe datetime. Masalah tersebut dengan menggunakan library pandas yaitu               pd.to_datetime


B. Exploratory Data Analysis: Proses analisis data yang bertujuan untuk mengeksplorasi dan mengenal sebuah data. Pada prosesnya sering kali mulai dengan mendefenisikan berbagai pertanyaan atau hanya menggali data guna menemukan beberapa insigh menarik dari sebuah data.
   * Dalam hal ini exploratory data analisis digunakan untuk menemukan korelasi antara     kondisi cuaca dengan jumlah penyewaan. Dengan menggunakan korealis pearson            ditemukan bahwa kondisi cuaca yang didefisikan dengan berbagai parameter yaitu        suhu, kelembaban, dan kecepatan angin berpengaruh terhadap jumlah penyewaan           sepeda.


C. Visualization and Explanatory Analysis: Visualisasi data merupakan cara dalam menyajikan data dalam bentuk visual. Explanatory analysis merupakan proses analisis data yang bertujuan untuk membagikan beberapa insight yang menarik dari sebauh data. Insight yang diperoleh dari proses explanatory akan digunakan untuk menjawab permasalahan bisnis yang dihadapi.
   * Terdapat 4 pertanyaan yang diajukan
   * Buat visualisasi data untuk menjawab pertanyaan tersebut dengan sumbu x merupakan     independent variabel dan sumbu y merupakan dependent variabel. 
 
