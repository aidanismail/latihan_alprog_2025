## Latihan 1

> file: latihan_1.cpp

### Deskripsi

Rani sedang belajar tentang operasi pada matriks dua dimensi. Ia ingin membuat program yang dapat menghitung penjumlahan dan pengurangan antara dua buah matriks A dan B.
Bantulah Rani membuat program yang meminta pengguna untuk memasukkan ukuran matriks (baris dan kolom), kemudian mengisi elemen-elemen matriks A dan B, lalu menampilkan hasil operasi penjumlahan dan pengurangannya.

### Format Input

Baris pertama: jumlah baris (baris)
Baris kedua: jumlah kolom (kolom)
Beberapa baris berikutnya: elemen-elemen matriks A
Beberapa baris berikutnya: elemen-elemen matriks B

### Format Output

Tampilkan hasil operasi:
Matriks hasil penjumlahan (A + B)
Matriks hasil pengurangan (A - B)

### Contoh

- Sample Input 1

  Masukkan jumlah baris: 2
  Masukkan jumlah kolom: 3

  Masukkan elemen matriks A:
  1 2 3
  4 5 6

  Masukkan elemen matriks B:
  6 5 4
  3 2 1

- Sample Output 1

  Hasil Penjumlahan (A + B):
  7 7 7
  7 7 7

  Hasil Pengurangan (A - B):
  -5 -3 -1
  1 3 5

### Penjelasan

Dari dua matriks di atas:

A = [1 2 3] B = [6 5 4]
[4 5 6] [3 2 1]

Maka hasil penjumlahan dan pengurangannya dihitung per elemen sesuai operasi masing-masing.

## Latihan 2

> file: latihan_2.cpp

### Deskripsi

Raka ingin membuat program untuk mengecek apakah sebuah kata merupakan palindrom atau tidak.
Palindrom adalah kata yang dibaca sama dari depan maupun dari belakang (contoh: katak, level, madam).

Buatlah program yang meminta pengguna untuk memasukkan sebuah kata tanpa spasi, menyimpannya ke dalam array karakter, kemudian mengecek apakah kata tersebut palindrom.

### Format Input

Sebuah kata tanpa spasi.

### Format Output

Pesan hasil pengecekan, yaitu:

- "Kata tersebut adalah palindrom" jika sama dibaca dari depan dan belakang.
- "Kata tersebut bukan palindrom" jika berbeda.

### Contoh

- Sample Input 1

  katak

- Sample Output 1

  Kata tersebut adalah palindrom

- Sample Input 2

  program

- Sample Output 2

  Kata tersebut bukan palindrom

### Penjelasan

Kata katak terbaca sama dari kiri maupun kanan, sedangkan program tidak, sehingga hasil berbeda.

## Latihan 3

> file: latihan_3.cpp

### Deskripsi

Fina ingin membuat program untuk menghitung berapa kali setiap angka muncul di dalam sebuah array.
Program akan meminta jumlah elemen, kemudian pengguna memasukkan angka satu per satu. Setelah itu, program akan menampilkan berapa kali setiap angka muncul.

### Format Input

- Baris pertama: jumlah elemen (n)
- Baris berikutnya: n buah bilangan integer

### Format Output

Untuk setiap angka yang muncul, tampilkan pesan:

- Angka <nilai> muncul <jumlah> kali

### Contoh

- Sample Input

  Masukkan jumlah elemen: 6
  Masukkan elemen ke-1: 2
  Masukkan elemen ke-2: 3
  Masukkan elemen ke-3: 2
  Masukkan elemen ke-4: 5
  Masukkan elemen ke-5: 3
  Masukkan elemen ke-6: 2

- Sample Output

  Angka 2 muncul 3 kali
  Angka 3 muncul 2 kali
  Angka 5 muncul 1 kali

### Penjelasan

Angka 2 dimasukkan sebanyak 3 kali, 3 sebanyak 2 kali, dan 5 sebanyak 1 kali, maka hasil program menampilkan jumlah kemunculan tiap angka.
