# Big-Data

# Kode 1:
sc: singkatan dari Spark Context, objek utama yang digunakan untuk berinteraksi dengan Spark.

accumulator: variabel yang dapat diakses oleh semua tugas pada node yang sama, digunakan untuk melakukan agregasi.

parallelize: method untuk membuat RDD (Resilient Distributed Dataset) dari koleksi data pada driver program.

lambda: fungsi anonim yang dapat digunakan untuk melakukan operasi pada RDD.

value: method untuk mengakses nilai yang disimpan pada variabel yang terhubung ke RDD.

# Kode 2:
broadcast: mendistribusikan variabel yang dapat diakses oleh semua tugas pada node yang sama.

list: tipe data yang menyimpan kumpulan nilai.

range:  membuat urutan bilangan bulat.

# Kode 3:
textFile: method untuk membaca file teks dan membuat RDD berisi baris-baris teks.

filter: method untuk memfilter data berdasarkan suatu kondisi dan mengembalikan RDD yang terdiri dari data yang lolos filter.

cache: method untuk menyimpan RDD dalam memori agar dapat diakses lebih cepat.

count: method untuk menghitung jumlah elemen dalam RDD.

# Kode 4:
map: method untuk melakukan transformasi pada setiap elemen RDD.

collect: method untuk mengambil seluruh elemen RDD dan mengembalikannya ke driver program.

len: method untuk menghitung panjang sebuah objek, seperti RDD.

keys: method untuk mengambil kunci dari sebuah RDD yang berisi pasangan kunci-nilai.

values: method untuk mengambil nilai dari sebuah RDD yang berisi pasangan kunci-nilai.

# Kode 5:
defaultParallelism: jumlah partisi default yang digunakan oleh RDD.

getNumPartitions: method untuk mengambil jumlah partisi dari sebuah RDD.

mapPartitionsWithIndex: method untuk melakukan transformasi pada setiap partisi RDD dengan mengakses indeks partisi.

repartition: method untuk mengubah jumlah partisi RDD menjadi jumlah partisi yang baru.

coalesce: method untuk menggabungkan beberapa partisi RDD menjadi satu partisi.

toDebugString: method untuk mengambil informasi rinci tentang RDD.
# Kode 6:
flatMap: untuk melakukan transformasi pada setiap elemen RDD dan mengembalikan kumpulan nilai.

reduceByKey: untuk menghitung hasil agregasi pada pasangan kunci-nilai yang sama.

split: untuk membagi sebuah string menjadi beberapa bagian berdasarkan pemisah yang ditentukan.
