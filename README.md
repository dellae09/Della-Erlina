# Della Erlina - Tugas PBO 
<h1 align="center">Hai! Semua 👋</h1>
<h3 align="center"> Disini saya akan menjelaskan mengenai tugas PBO saya</h3>

<img align="right" height="150" src="https://i.imgflip.com/65efzo.gif"  />

<h3 align="left"> Perkenalan</h3>
<h5 align="left"> Nama  : Della Erlina</h5>
<h5 align="left"> NPM   : G1F022019</h5>
<h5 align="left"> Prodi : Sistem Informasi</h5>
<h5 align="left"> Fakultas Teknik Universitas Bengkulu</h5>

## Pokok Bahasan
Pada halaman ini saya menjelaskan 3 soal dari tugas PBO yang telah di berikan
1.  Buatlah perulangan hingga 100 menggunakan Python dengan output sebagai berikut:
2.  Buatlah program bebas, dengan menerapkan if else pada:
  a. For Loops
  b. While Loops
3. Buatlah sebuah variabel dengan tipe data array, kemudian tampilkan semua nilai dalam variabel tersebut menggunakan perulangan for!

## Penjelasan soal no 1
Soal : 
Buatlah perulangan hingga 100 menggunakan Python!
disini saya menggunakan 3 versi
<h5 align="left"> Tabel 1.1 Kode Versi 1</h5>

| Kode Python  | Input Data | Output Data|
| :------------ |:---------------:| -----:|
| for i in range(1, 101)      |  | Mulai iterasi i dari 1 hingga 100 |
| if i % 10 != 0      |        |  Jika i bukan kelipatan 10 |
|     print(i)	 |     |   Cetak nilai i |
|   else:      |        |  Jika i adalah kelipatan 10 |
|       print("Della Erlina")	 |     |   Cetak "Della Erlina" satu kali |
|       print("Della Erlina")	 |     |   Cetak "Della Erlina" satu kali |
|       print("Della Erlina")	 |     |   Cetak "Della Erlina" satu kali |

Penjelasan : program menggunakan perulangan for untuk mengiterasi variabel i dari 1 hingga 100. Selanjutnya, program menggunakan pernyataan if-else untuk menentukan apakah nilai i adalah kelipatan 10 atau tidak. Jika i bukan kelipatan 10, program mencetak nilai i. Jika i adalah kelipatan 10, program mencetak "Della Erlina" tiga kali.

<h5 align="left"> Tabel 1.2 Kode Versi 2</h5>

| Kode Python  | Input Data | Output Data|
| :------------ |:---------------:| -----:|
| for i in range(1, 101)      |  | Mulai iterasi i dari 1 hingga 100 |
| if i % 10 != 0      |        |  Jika i bukan kelipatan 10 |
|     print(i)	 |     |   1, 2, 3, ..., 9 |
|   else :    print("Della Erlina\n"*3, end="")	 |     |   Della Erlina, Della Erlina, Della Erlina (pada setiap kelipatan 10)|


<h5 align="left"> Tabel 1.3 Kode Versi 3</h5>

| Iterasi  | Penggunaan Kode  | Output Data|
| :------------ |:---------------:| -----:|
| 1    | 	i = 1 | Cetak nilai i (1) |
| 2    | i += 1 | Cetak nilai i (2) |
| 3    |i += 1 | Cetak nilai i (3) |
| 4    |i += 1| Cetak nilai i (4) |
| 5   | i += 1 | Cetak nilai i (5) |
| 6   | i += 1 | Cetak nilai i (6) |
| 7    |i += 1 | Cetak nilai i (7) |
| 8    | 	i += 1 | Cetak nilai i (8) |
| 9    | i += 1| Cetak nilai i (9) |
| 10    | 	i += 1 | Della Erlina 3 kali|
|....   | 	... | .... |


Penjelasan : Pada setiap iterasi, program memeriksa apakah nilai i adalah kelipatan 10. Jika iya, maka program mencetak "Della Erlina\n" sebanyak 3 kali. Jika tidak, program hanya mencetak nilai i. Iterasi ini berlanjut hingga i mencapai nilai 100.


## Penjelasan soal no 2
Buatlah program bebas, dengan menerapkan if else pada:
  a. For Loops
  b. While Loops

  <h5 align="left"> Tabel 2.1 Kode For Loops</h5>

| Kode Python  | Input Data | Output Data|
| :------------ |:---------------:| -----:|
| for i in range(1, 101)      |  | Mulai iterasi i dari 1 hingga 100 |
| if i % 10 != 0      |        |  Jika i bukan kelipatan 10 |
|     print(i)	 |     |   1, 2, 3, ..., 9 |
|   else :    print("Della Erlina\n"*3, end="")	 |     |   Della Erlina, Della Erlina, Della Erlina (pada setiap kelipatan 10)|

Penjelasan : 


  <h5 align="left"> Tabel 3 Tipe data Array</h5>

| Kode Python  | Input Data | Output Data|
| :------------ |:---------------:| -----:|
|Import Module]     | Tidak ada (tidak memerlukan input) | Tidak ada input, hanya pesan selamat datang dan petunjuk awal |
| Definisi Variabel]     |kata_kunci berisi list kata        |  Variabel kata_terpilih dipilih secara acak dari kata_kunci |
|    | kesempatan diinisialisasi 5    | tebakan diinisialisasi dengan underscore (_panjang kata) |
|     While Loop	 | Tidak ada (masuk loop dengan kesempatan > 0)    |   Menampilkan informasi kata yang harus ditebak dan petunjuk|
|    	 | Input tebakan dari pengguna    |   Memeriksa tebakan, memberikan umpan balik, dan mengubah tebakan|
|    	 |    |   Menampilkan informasi tebakan dan kondisi berakhir loop|
|    	 |    |  Menampilkan pesan hasil akhir permainan|






## Penjelasan soal no 3


  <h5 align="left"> Tabel 3 Tipe data Array</h5>

| Kode Python  | Input Data | Output Data|
| :------------ |:---------------:| -----:|
| my_array = [1, "Hello", 3.14, True, [5, 6, 7], "Python"]     |  |  |
| my_array = [1, "Hello", 3.14, True, [5, 6, 7], "Python"]     |        |  Nilai dalam variabel my_array: |
|   for index, nilai in enumerate(my_array, start=1):	 |     |   1, 2, 3, ..., 9 |
|       print(f"NILAI {index}: {nilai}")	 |     |   NILAI 1: 1|
|....   | 	... | .... |
- 🔭 Source Code yang telah saya buat dapat di akses pada link ini [Source code Tugas Della](https://colab.research.google.com/drive/1EOcdNTBMvzQSh6A3Xb3KIQ6yGXsdch4l#scrollTo=GQjG0O1AN8Kq&line=1&uniqifier=1)
