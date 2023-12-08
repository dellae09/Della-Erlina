# _Della Erlina - Tugas PBO_ 
<h1 align="center">Hai! Semua 👋</h1>
<h3 align="center"> Disini saya akan menjelaskan mengenai tugas PBO saya</h3>

<img align="right" height="150" src="https://i.imgflip.com/65efzo.gif"  />

<h3 align="left"> Perkenalan</h3>
<h5 align="left"> Nama  : Della Erlina </h5>
<h5 align="left"> NPM   : G1F022019</h5>
<h5 align="left"> Prodi : Sistem Informasi</h5>
<h5 align="left"> Fakultas Teknik Universitas Bengkulu</h5>

## Pokok Bahasan
Pada halaman ini saya menjelaskan 3 soal dari tugas PBO yang telah di berikan
1.  Buatlah perulangan hingga 100 menggunakan Python dengan output sebagai berikut:
2.  Buatlah program bebas, dengan menerapkan if else pada:
   
   -  For Loops
  
  -  While Loops
  
3. Buatlah sebuah variabel dengan tipe data array, kemudian tampilkan semua nilai dalam variabel tersebut menggunakan perulangan for!

## Soal No 1 : Buatlah perulangan hingga 100 menggunakan Python!
Disini saya menggunakan 3 versi

1.1 Kode pertama yang saya buat 
```sh
# Perulangan hingga 100 menggunakan Python

for i in range(1, 101):
    if i % 10 != 0:
        print(i)
    else:
        print("Della Erlina")
        print("Della Erlina")
        print("Della Erlina")

```
<div align="center">
  
![gambar 1](https://github.com/dellae09/Della-Erlina/assets/150639048/e423f7cc-df68-4c7e-ab8b-38aec5290000)
  
<h5 align="center"> Gambar 1.1 Source Code Pertama </h5> 

| Kode Python  |  Output Data|
| ------------ | -----|
| for i in range(1, 101) |Mulai iterasi i dari 1 hingga 100 |
| if i % 10 != 0      |kondisi yang memeriksa  nilai iterasi i bukan kelipatan 10 |
|     print(i)	 |Cetak nilai i |
|   else:      |Jika i adalah kelipatan 10 |
|       print("Della Erlina")   |Cetak "Della Erlina" satu kali |
|       print("Della Erlina")	     |Cetak "Della Erlina" satu kali |
|       print("Della Erlina")	     |Cetak "Della Erlina" satu kali |
<h5 align="center"> Tabel 1.1 Penjelasan Kode Versi 1</h5>
</div>
Penjelasan : program menggunakan perulangan for untuk mengiterasi variabel i dari 1 hingga 100. Selanjutnya, program menggunakan pernyataan if-else untuk menentukan apakah nilai i adalah kelipatan 10 atau tidak. Jika i bukan kelipatan 10, program mencetak nilai i. Jika i adalah kelipatan 10, program mencetak "Della Erlina" tiga kali.
if i % 10 != 0:: Ini adalah kondisi yang memeriksa apakah nilai iterasi i bukan kelipatan 10.
Jika bukan kelipatan 10, maka mencetak nilai iterasi itu sendiri (print(i)).
Jika kelipatan 10, maka mencetak "Della Erlina" sebanyak tiga kali dengan menggunakan tiga pernyataan print.
Akhirnya, perulangan berlanjut hingga mencapai 100.



<div align="center">

![gambar2](https://github.com/dellae09/Della-Erlina/assets/150639048/8bd8b2d1-d857-4ab3-aa77-dd8615fee018)

<h5 align="center"> Gambar 1.2 Source Code Kedua</h5>  

| Kode Python   | Output Data|
| ------------ |-----|
| for i in range(1, 101)      |Mulai iterasi i dari 1 hingga 100 |
| if i % 10 != 0      |Jika i bukan kelipatan 10 |
|     print(i)	 |1, 2, 3, ..., 9 |
|   else :    print("Della Erlina\n"*3, end="")	 |Della Erlina, Della Erlina, Della Erlina (pada setiap kelipatan 10)|
<h5 align="center"> Tabel 1.2 Penjelasan  Kode Versi 2</h5>

![gambar3](https://github.com/dellae09/Della-Erlina/assets/150639048/544bbb5b-b90a-4c74-9c55-1c6bc2495553)

<h5 align="center"> Gambar 1.3 Source Code Ketiga</h5>  

| Iterasi  | Penggunaan Kode  | Output Data|
| ------------ |---------------| -----|
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
<h5 align="center"> Tabel 1.3 Kode Versi 3</h5>
</div>
Penjelasan : Pada setiap iterasi, program memeriksa apakah nilai i adalah kelipatan 10. Jika iya, maka program mencetak "Della Erlina\n" sebanyak 3 kali. Jika tidak, program hanya mencetak nilai i. Iterasi ini berlanjut hingga i mencapai nilai 100.


## Penjelasan soal no 2
Buatlah program bebas, dengan menerapkan if else pada:
  - For Loops
  - While Loops
      
```sh
  import random

def game_tebak_angka():
    print("Selamat datang di Game Tebak Angka!")
    print("Saya akan memilih sebuah angka antara 1 dan 10. Coba tebak!")

    angka_rahasia = random.randint(1, 10)
    jumlah_percobaan = 3
 
    for percobaan in range(1, jumlah_percobaan + 1):
        tebakan = int(input(f"Percobaan ke-{percobaan}: Masukkan tebakan Anda (1-10): "))

        if tebakan == angka_rahasia:
            print("Selamat! Anda benar!")
            break
        else:
            if percobaan < jumlah_percobaan:
                print("Tebakan Anda salah. Coba lagi!")
            else:
                print(f"Maaf, Anda gagal. Angka yang benar adalah {angka_rahasia}.")

if __name__ == "__main__":
    game_tebak_angka()
```
<div align="center">

![gmbar4](https://github.com/dellae09/Della-Erlina/assets/150639048/e6ceeba3-aab0-4ad8-8d8d-053a2f848af2)

  <h5 align="center"> Gambar 2.1 Output For Loops</h5>

| Kode                                       | Keterangan                                                                                                   |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| `import random`                             | Mengimpor modul random yang digunakan untuk menghasilkan angka acak.                                        |
| `def game_tebak_angka():`                   | Mendefinisikan fungsi game_tebak_angka(), yang akan berisi logika utama dari permainan tebak angka.          |
| `print("Selamat datang di Game Tebak Angka!")` | Mencetak sambutan awal game.                                                                               |
| `print("Saya akan memilih sebuah angka antara 1 dan 10. Coba tebak!")` | Memberikan informasi kepada pemain mengenai batas angka yang akan ditebak.                            |
| `angka_rahasia = random.randint(1, 10)`    | Menghasilkan angka acak antara 1 dan 10 dan menyimpannya dalam variabel angka_rahasia sebagai jawaban yang benar. |
| `jumlah_percobaan = 3`                      | Menentukan jumlah kesempatan percobaan yang diberikan kepada pemain.                                          |
| `for percobaan in range(1, jumlah_percobaan + 1):` | Membuka perulangan for dengan rentang sesuai dengan jumlah kesempatan percobaan.                             |
| `tebakan = int(input(f"Percobaan ke-{percobaan}: Masukkan tebakan Anda (1-10): "))` | Meminta input dari pemain untuk menebak angka, dan menyimpannya dalam variabel tebakan.          |
| `if tebakan == angka_rahasia:`             | Mengecek apakah tebakan pemain benar. Jika benar, program mencetak pesan selamat dan keluar dari perulangan. |
| `print("Selamat! Anda benar!")`           | Mencetak pesan selamat ketika tebakan benar.                                                               |
| `break`                                    | Menghentikan perulangan saat tebakan benar.                                                               |
| `else:`                                    | Bagian ini dieksekusi jika tebakan pemain salah.                                                          |
| `if percobaan < jumlah_percobaan:`         | Mengecek apakah ini percobaan terakhir. Jika bukan, mencetak pesan untuk mencoba lagi.                      |
| `print("Tebakan Anda salah. Coba lagi!")` | Mencetak pesan bahwa tebakan salah dan memberikan kesempatan untuk mencoba lagi.                           |
| `else:`                                    | Bagian ini dieksekusi jika pemain sudah mencoba sebanyak jumlah_percobaan kali, tetapi tebakannya tetap salah. |
| `print(f"Maaf, Anda gagal. Angka yang benar adalah {angka_rahasia}.")` | Mencetak pesan kegagalan dan memberikan jawaban yang benar.                                          |
| `if __name__ == "__main__":`               | Mengecek apakah skrip dijalankan langsung (bukan diimpor sebagai modul). Jika ya, memanggil fungsi game_tebak_angka(). |
 
  <h5 align="center"> Tabel 2.1 Penjelasan Kode For Loops</h5>



  ![gambar5](https://github.com/dellae09/Della-Erlina/assets/150639048/84b54f2d-1db7-41c7-895b-0393c5294f6e)

  <h5 align="center"> Gambar 2.2 Gambar Output kode While Loops</h5>

| Kode | Keterangan |
| ---- | ---------- |
| `import random` | Import modul random untuk memilih kata secara acak dari daftar kata_kunci. |
| `kata_kunci = ["PYTHON", "PHP", "C++", "JAVA"]` | Inisialisasi variabel kata_kunci dengan daftar kata-kata pemrograman. |
| `kata_terpilih = random.choice(kata_kunci).upper()` | Memilih kata acak dari daftar kata_kunci dan mengonversinya menjadi huruf besar. |
| `tebakan = "_" * len(kata_terpilih)` | Membuat string tebakan yang hanya berisi garis bawah sepanjang kata_terpilih. |
| `print("Selamat datang di Game Tebak Kata!")` | Menampilkan pesan selamat datang dan informasi tentang panjang kata terpilih dan petunjuk game. |
| `kesempatan = 5` | Inisialisasi variabel kesempatan dengan nilai 5. |
| `while kesempatan > 0:` | Memulai loop while dengan syarat kesempatan > 0. |
| `print("\nKata yang harus ditebak: ", tebakan)` | Menampilkan kata yang harus ditebak dan meminta input pemain. |
| `if len(tebak) == 1 and tebak.isalpha():` | Mengecek apakah input pemain adalah huruf tunggal dan valid. |
| `if tebak in kata_terpilih:` | Jika huruf tebakan benar, mengganti garis bawah di tebakan dengan huruf yang benar. |
| `else:` | Jika huruf tebakan salah, mengurangi kesempatan dan memberikan pesan kesalahan. |
| `elif len(tebak) == len(kata_terpilih) and tebak.isalpha():` | Jika tebakan seluruh kata benar, program selesai dan menampilkan kata terpilih. |
| `else:` | Jika input tidak valid (bukan huruf atau kata), memberikan pesan kesalahan. |
| `if "_" not in tebakan:` | Jika tidak ada garis bawah di tebakan, pemain berhasil menebak dan program selesai. |
| `if kesempatan == 0:` | Jika kesempatan habis, program memberitahu pemain bahwa kata terpilih adalah... |
| `print("Jumlah huruf dalam kata yang harus ditebak adalah:", len(kata_terpilih))` | Menampilkan jumlah huruf dalam kata terpilih. |
| `if __name__ == "__main__":` | Mengeksekusi fungsi main jika program dijalankan sebagai skrip utama. |
| `main()` | Memanggil fungsi main untuk menjalankan program. |

  <h5 align="center"> Tabel 2.1 Penjelasan  While Loops</h5>
</div>


##  Penjelasan soal no 3

<div align="center">

![gambar6](https://github.com/dellae09/Della-Erlina/assets/150639048/1c3a9443-9c95-46b4-a127-54293a7fd030)

<h5 align="center"> Gambar 3 Source code Tipe Data Array</h5>

</div> 

Penjelasan:

```sh my_array = [1, "Hello", 3.14, True, [5, 6, 7], "Python"] ```

- Baris ini membuat variabel my_array dan menginisialisasinya sebagai list dengan berbagai tipe data, termasuk integer (1), string ("Hello"), float (3.14), boolean (True), list ([5, 6, 7]), dan string lagi ("Python").
  
```sh
 print("Nilai dalam variabel my_array:")
for index, nilai in enumerate(my_array, start=1):
    print(f"NILAI {index}: {nilai}")
```

- Baris ini mencetak judul atau label "Nilai dalam variabel my_array:"

- Selanjutnya, dilakukan perulangan for untuk iterasi melalui setiap elemen dalam my_array. Fungsi enumerate digunakan untuk mendapatkan indeks dan nilai setiap elemen.

- Variabel index menyimpan indeks elemen (dimulai dari 1 karena kita menggunakan start=1).

- Variabel nilai menyimpan nilai dari setiap elemen.

Dengan menggunakan f-string (format string), program mencetak informasi setiap elemen dalam format yang bersahabat, termasuk indeks elemen dan nilai elemennya.


<h5 align="left"> 🔭 Source Code yang telah saya buat dapat di akses pada link ini [Source code Tugas Della (https://colab.research.google.com/drive/1EOcdNTBMvzQSh6A3Xb3KIQ6yGXsdch4l#scrollTo=GQjG0O1AN8Kq&line=1&uniqifier=1)</h5> 

<a href="https://instagram.com/https://instagram.com/della_erlinaa?igshid=nzzlodbkywe4ng==" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="https://instagram.com/della_erlinaa?igshid=nzzlodbkywe4ng==" height="30" width="40" /></a>
</p>

