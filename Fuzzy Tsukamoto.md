Implementasi Logika Fuzzy Tsukamoto Dalam Menentukan 
Harga Handphone Bekas Iphone XR



1.	PENDAHULUAN
1.1	Latar Belakang
Jual beli Handphone adalah sebuah kegiatan transaksi yang sering ditemukan dalam kehidupan sehari-hari. Dengan bermacam varian harga baik barang baru maupun bekas, dalam pembelian handphone masih banyak kekeliruan yang menyebabkan kerugian pada pembeli, karna kurang memperhatikan faktor-faktor  yang mempengaruhi harga handphone.

Salah satu cara yang bisa digunakan dalam memperkirakan harga handphone bekas agar pembeli tidak mengalami kerugian adalah dengan penerapan logika fuzzy, karena terdapat beberapa data yang bisa digunakan dalam melakukan perhitungan guna mendapatkan perkiraan harga handphone bekas. Dengan menggunakan fuzzy logic prediksi yang dihasilkan bukanlah prediksi asal yang tidak berdasar, hasil inferensi dari fuzzy logic adalah berupa angka taksiran berdasarkan perhitungan matematis sehingga tingkat keakuratannyapun bisa diukur. 

1.2	Rumusan Masalah
Berdasarkan latar belakang tersebut maka dapat dirumuskan permasalahan sebagai berikut, Bagaimana penerapan metode Tsukamoto untuk menentukan harga handphone bekas Iphone XR berdasarkan warna, kondisi, Kesehatan baterai, harga beli baru dan kisaran jual harga bekas? 

2.	LANDASAN TEORI
2.1	Logika Fuzzy Tsukamoto
Pada metode Tsukamoto, implikasi setiap aturan berbentuk implikasi “Sebab-Akibat”/Implikasi “Input-Output” dimana antara anteseden dan konsekuen harus ada hubungannya. Setiap aturan direpresentasikan menggunakan himpunan-himpunan fuzzy, dengan fungsi keanggotaan yang monoton. Kemudian untuk menentukan hasil tegas (Crisp Solution) digunakan rumus penegasan (defuzifikasi) yang disebut “Metode rata-rata terpusat” atau “Metode defuzifikasi rata-rata terpusat (Center Average Deffuzzyfier) (setiadji, 2009).

3.	HASIL DAN PEMBAHASAN
3.1	Hasil Penelitian
Penerapan metode fuzzy tsukamoto pada penelitian ini dilakukan untuk mendapatkan output berupa harga jual Iphone XR bekas berdasarkan kriteria dan bobot yang sudah ditentukan. Dalam penggunaan metode fuzzy tsukamoto terdapat beberapa langkah untuk dapat menghasilkan output seperti yang diinginkan, yaitu :
 
1.	Menentukan himpunan fuzzy
a.	Variabel kondisi HP
Variabel input Kondisi HP merupakan kondisi luar yang tampak atau kelihatan dari body HP, semakin banyaknya goresan yang terlihat pada body akan semakin menurunkan harga jual, variable ini terdiri dari himpunan BAGUS yang memiliki rentan input antara 85 sampai dengan 95 dan himpunan SEDANG yang memiluki rentan antara 75 sampai dengan 84, berikut himpunan fuzzy pada variabel Kondisi HP : 
VARIABEL KONDISI HP	
NO	HIMPUNAN	ANGKA
1	BAGUS	85 - 95
2	SEDANG	75 - 84


b. Variabel Warna HP
Variabel input warna HP merupakan varian warna HP Iphone XR. variable ini terdiri dari himpunan FAVORIT dan NON FAVORIT, Berikut himpunan fuzzy pada variabel warna HP :
VARIABEL WARNA HP	
NO 	HIMPUNAN	ANGKA
1	FAVORIT	90 - 100
2	NON FAVORIT	80 - 89


c. Variabel Kesehatan Baterai
Variabel input Kesehatan Baterai HP merupakan kondisi baterai pada HP, terdiri dari himpunan BAGUS rentan inputan antara 90 – 100 dan SEDANG antara 80 – 89, Berikut himpunan fuzzy pada variable baterai :
VARIABEL KESEHATAN BATERAI	
NO	HIMPUNAN	ANGKA
1	BAGUS	90 - 100
2	SEDANG	80 - 89


d. Variabel Harga Beli Baru
Variabel Harga Beli Baru didasarkan pada harga beli baru HP tersebut. Berikut himpunan fuzzy pada variabel Harga HP : 
VARIABEL HARGA BELI BARU	
NO	HIMPUNAN	ANGKA
1	SANGAT MURAH	12.000.000 - 12.500.000
2	MURAH	12.600.000 - 13.000.000
3	MAHAL	13.100.000 - 13.800.000


e. Variabel Harga Beli Bekas
Variabel Harga Jual Bekas merupakan variabel output yang diharapkan dalam sistem ini. Harga jual bekas yang dihasilkan dari sistem ini diharapkan sesuai atau mendekati harga jual bekas yang ada dipasaran saat ini. Berikut himpunan fuzzy pada variabel Harga Jual Bekas : 
VARIABEL HARGA BELI BEKAS	
NO	HIMPUNAN	ANGKA
1	SANGAT MURAH	4.500.000 - 5.000.000
2	MURAH	5.100.000 - 5.500.000
3	MAHAL	5.600.000 - 6.000.000


