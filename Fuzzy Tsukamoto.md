KELOMPOK 1 : Juwanda Azi Mayuswa
		    : Achmad Yanis
		    : Kerryna Dwi Andaria
		    : Aina Fadila

Implementasi Logika Fuzzy Logic Tsukamoto Dalam Menentukan
Harga Handphone Bekas Iphone XR

1. PENDAHULUAN
1.1 Latar Belakang
Jual beli Handphone adalah sebuah kegiatan transaksi yang sering ditemukan dalam kehidupan sehari-hari. Dengan bermacam varian harga baik barang baru maupun bekas, dalam pembelian handphone masih banyak kekeliruan yang menyebabkan kerugian pada pembeli, karna kurang memperhatikan faktor-faktor  yang mempengaruhi harga handphone.
Salah satu cara yang bisa digunakan dalam memperkirakan harga handphone bekas agar pembeli tidak mengalami kerugian adalah dengan penerapan logika fuzzy, karena terdapat beberapa data yang bisa digunakan dalam melakukan perhitungan guna mendapatkan perkiraan harga handphone bekas. Dengan menggunakan fuzzy logic prediksi yang dihasilkan bukanlah prediksi asal yang tidak berdasar, hasil inferensi dari fuzzy logic adalah berupa angka taksiran berdasarkan perhitungan matematis sehingga tingkat keakuratannya pun bisa diukur. 

1.2	Rumusan Masalah
Berdasarkan latar belakang tersebut maka dapat dirumuskan permasalahan sebagai berikut, Bagaimana penerapan metode Tsukamoto untuk menentukan harga handphone bekas Iphone XR berdasarkan kondisi, harga beli baru dan kisaran jual harga bekas? 

2.	LANDASAN TEORI
2.1	Logika Fuzzy Tsukamoto
Pada metode Tsukamoto, implikasi setiap aturan berbentuk implikasi “Sebab-Akibat”/Implikasi “Input-Output” dimana antara anteseden dan konsekuen harus ada hubungannya. Setiap aturan direpresentasikan menggunakan himpunan-himpunan fuzzy, dengan fungsi keanggotaan yang monoton. Kemudian untuk menentukan hasil tegas (Crisp Solution) digunakan rumus penegasan (defuzifikasi) yang disebut “Metode rata-rata terpusat” atau “Metode defuzifikasi rata-rata terpusat (Center Average Deffuzzyfier) (setiadji, 2009).

3.	HASIL DAN PEMBAHASAN
3.1	Hasil Penelitian
Penerapan metode fuzzy tsukamoto pada penelitian ini dilakukan untuk mendapatkan output berupa harga jual Iphone XR bekas berdasarkan kriteria dan bobot yang sudah ditentukan. Dalam penggunaan metode fuzzy tsukamoto terdapat beberapa langkah untuk dapat menghasilkan output seperti yang diinginkan, yaitu :
	Menentukan himpunan fuzzy
a. Variabel Harga Beli Baru
Variabel Harga Beli Baru merupakan variabel output yang diharapkan dalam sistem ini. Harga beli baru yang dihasilkan dari sistem ini diharapkan sesuai atau mendekati harga beli baru yang ada dipasaran saat ini. Berikut himpunan fuzzy pada variabel Harga Beli Baru: 
VARIABEL HARGA BELI BARU	
NO	HIMPUNAN	ANGKA
1	MURAH	12.000.000 – 14.500.000
3	MAHAL	12.000.000 – 14.500.000

b. Variabel kondisi HP
Variabel input Kondisi HP merupakan kondisi luar yang tampak atau kelihatan dari body HP, semakin banyaknya goresan yang terlihat pada body akan semakin menurunkan harga jual, variable ini terdiri dari himpunan BAGUS yang memiliki rentan input antara 75 sampai dengan 95 dan himpunan TIDAK BAGUS yang memiliki rentan antara 75 sampai dengan 95, berikut himpunan fuzzy pada variabel Kondisi HP : 
VARIABEL KONDISI HP	
NO	HIMPUNAN	ANGKA
1	BAGUS	75 – 95 
2	TIDAK BAGUS	75 – 95 






c. Variabel Harga Beli Bekas
Variabel Harga Beli Bekas merupakan variabel output yang diharapkan dalam sistem ini. Harga beli bekas yang dihasilkan dari sistem ini diharapkan sesuai atau mendekati harga beli bekas yang ada dipasaran saat ini. Berikut himpunan fuzzy pada variabel Harga Beli Bekas: 
VARIABEL HARGA BELI BEKAS	
NO	HIMPUNAN	ANGKA
1	MURAH	4.500.000 - 6.000.000
3	MAHAL	4.500.000 - 6.000.000

Representasi linear NAIK
 
Ò  Representasi linear TURUN
 
 
Pada metode Tsukamoto, implikasi setiap aturan berbentuk implikasi “Sebab-Akibat”/Implikasi “Input-Output”
 Contoh
Misalkan ada 2 variabel input, Var-1 (x) dan Var-2(x), serta variabel output,Var-3(z), dimana Var-1 terbagi atas 2 himpunan yaitu A1 dan A2. Var-2 terbagi atas 2 himpunan B1 dan B2, Var-3 juga terbagi atas 2 himpunan yaitu C1 dan C2 (C1 dan C2 harus monoton). Ada 2 aturan yang digunakan, yaitu:
[R1] IF (x is A1) and (y is B2) THEN (z is C1)
[R2] IF (x is A2) and (y is B1) THEN (z is C2) 

 



Kasus 
Berapa harga yang cocok untuk membeli HP Bekas dibawah ini.


Data minimum dan Data maksimum
Harga beli baru MAHAL			: 14.000.000
Harga beli baru MURAH			: 12.000.000
Kondisi HP BAGUS				: 95
Kondisi HP TIDAK BAGUS 			: 75
Harga beli bekas MAHAL			: 6.000.000
Harga beli bekas MURAH			: 4.500.000



PENYELESAIAN 
	Memodelkan variabel fuzzy (Fuzzifikasi)
	Ada 3 variabel fuzzy yang akan dimodelkan, yaitu: Pembayaran, Pelayanan, dan Tips.
	BeliBaru; terdiri dari 2 himpunan fuzzy, yaitu MURAH dan MAHAL. Fungsi keanggotaan Permintaan direpresentasikan pada Gambar.
Fungsi Keanggotaan Himpunan Mahal, dan Murah dari variabel.
Pembayaran:
Nilai keanggotaan himpunan Rendah, dan Tinggi dari variabel
	Pembayaran bisa dicari dengan:
μPembayaranMurah[12.500.000] = (14.000.000-12.500.000)/2.000.000
                                                         = 0,75
μPembayaranMahal[12.500.000] = (12.500.000-12.000.000)/2.000.000
                                                         = 0,25


	Kondisi; terdiri dari 2 himpunan fuzzy, yaitu BAGUS dan TIDAK BAGUS. Fungsi keanggotaan kondisi dapat dicari dengan:
Nilai keanggotaan himpunan Cepat, dan Lama dari variabel.
	Pelayanan bisa dicari dengan:
μKondisiBagus [80] = (95-80)/20
  	                                 = 0,75
μKondisiTidakBagus [80] = (80-75)/20
                                                         =0,25

	BeliBekas; terdiri dari 2 himpunan fuzzy, yaitu MURAH dan MAHAL. Fungsi keanggotaan kondisi dapat dicari dengan:
Nilai keanggotaan himpunan Cepat, dan Lama dari variabel.
Pelayanan bisa dicari dengan:
μPembayaranMurah [n] = {█(1         ;                  x ≤4.500.000@(6.000.000-n)/1.500.000;4.500.000 ≤x ≤6.000.000@0         ;                  x ≥6.000.000)┤
  	                                 

μPembayaranMahal[n] =  {█(0         ;                  x ≤4.500.000@(n-4.500.000)/1.500.000;4.500.000 ≤x ≤6.000.000@1         ;                  x ≥6.000.000)┤

	INFERENSI
[R1] IF Harga Murah And KondisiTidakBagus THEN Harga Bekas Mahal;
Nilai keanggotaan anteseden untuk aturan fuzzy [R1] yang dinotasikandengan α1 diperoleh dengan rumus sebagai berikut:
α1=  μHargaMurahKondisiTidakBagus
= min(μHargaMurah [12.500.000], μKondisiTidakBagus [80])
= min (0,75, 0,25)
= 0,25

n1=nmax – α1(nmax – nmin)
n1 adalah nilai untuk aturan fuzzy [R1].
Menurut fungsi keanggotaan himpunan Harga Jual Murah dalam aturan fuzzy [R1], maka nilai n1 adalah:
n = 6.000.000-(n*(6.000.000-4.500.000) = 0,25
n1 = 5.625.000


[R2] IF Harga Murah And Kondisi Bagus THEN Harga Bekas Murah;
Nilai keanggotaan anteseden untuk aturan fuzzy [R2] yang dinotasikan dengan α2 diperoleh dengan rumus sebagai berikut:
α2 =  μHargaMurahKondisiBagus
= min(μHargaMurah [12.500.000], μKondisiBagus [80])
= min (0,75, 0,75)
= 0,75

n2 = nmax – α2(nmax – nmin)
n2 adalah nilai untuk aturan fuzzy [R2].
Menurut fungsi keanggotaan himpunan Harga Jual Murah dalam aturan fuzzy [R2], maka nilai n1 adalah:
n = 6.000.000-(n*(6.000.000-4.500.000) = 0,75
n1 = 4.875.000

[R3] IF Harga Mahal And KondisiTidakBagus THEN Harga Bekas Mahal;
Nilai keanggotaan anteseden untuk aturan fuzzy [R3] yang dinotasikandengan α3 diperoleh dengan rumus sebagai berikut:
α3=  μHargaMahalKondisiTidakBagus
= min(μHargaMurah [12.500.000], μKondisiTidakBagus [80])
= min (0,25, 0,25)
= 0,25

n3=nmax – α3(nmax – nmin)
n3 adalah nilai untuk aturan fuzzy [R3].
Menurut fungsi keanggotaan himpunan Harga Jual Murah dalam aturan fuzzy [R3], maka nilai n1 adalah:
n = 6.000.000-(n*(6.000.000-4.500.000) = 0,25
n1 = 5.625.000


[R4] IF Harga Mahal And Kondisi Bagus THEN Harga Bekas Murah;
Nilai keanggotaan anteseden untuk aturan fuzzy [R4] yang dinotasikan dengan α4 diperoleh dengan rumus sebagai berikut:
α4	=  μHargaMahalKondisiBagus
= min(μHargaMahal [12.500.000], μKondisiBagus [80])
= min (0,25, 0,75)
= 0,25

n4 = nmax – α4(nmax – nmin)
n4 adalah nilai untuk aturan fuzzy [R4].
Menurut fungsi keanggotaan himpunan Harga Jual Murah dalam aturan fuzzy [R4], maka nilai n1 adalah:
n = 6.000.000-(n*(6.000.000-4.500.000) = 0,25
n1 = 5.625.000


Menentukan Output Crisp (Deffuzzyfikasi)
Pada metode Tsukamoto, untuk menentukan output crisp digunakan defuzifikasi rata-  rata terpusat, yaitu:

n=(a1 * n1+a2*n2+a3*n3+a4*n4)/(a1+a2+a3+a4)
n=(0,25 * 5.625.000+0,75*4.875.000+0,25*5.625.000+0,25*5.625.000)/(0,25+0,75+0,25+0,25)
n=(1.406.250+3.656.250+1.406.250+1.406.250)/1.5
n=7.875.000/1.5
n=5.250.000

Kesimpulan 

Dengan mengacu kepada solusi yang diberikan oleh metode Fuzzy Tsukamoto dalam membantu membuat keputusan. Salah satunya pengambilan keputusan  dalam memberikan imbalan yang setimpal untuk pelayan yang memberikan pelayanan tepat waktu sesuai keinginan pelanggan pada sebuah restoran. Menentukan perkiraan besaran tips yang diberikan kepada pelayan restoran bisa dilakukan secara mudah dan tepat sesuai dengan pelayanan yang diberikan menggunakan Metode Fuzzy Tsukamoto.


