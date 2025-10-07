# Lab3Web

## Nama: Bagus aditya hermawan
## Nim: 312410382
## Kelas: TI.24.A.3
## Mata kuliah: Pemrograman Web 1

## Langkah-langkah Praktikum

### 1. Membuat dokumen HTML dengan nama file lab3_list.html

#### ![Gambar 1](ss/yos1.png).


#### Ouput
![Gambar 1](screenshot/slor8.png).


### 2. Menambahkan CSS Internal

#### Input
![Gambar 1](screenshot/slor9.png).

#### Ouput
![Gambar 1](screenshot/slor10.png).


### 3. Menambahkan Inline CSS

#### Input
![Gambar 1](screenshot/slor11.png).

#### Output
![Gambar 1](screenshot/slor12.png).


### 4. Membuat dan Menambahkan Eksternal CSS
Terlebih dahulu membuat file style_eksternal.css untuk menaruh CSS.

#### Input
![Gambar 1](screenshot/slor13.png).

Menambahkan tag (link) agar file HTML dan CSS dapat terhubung.
![Gambar 1](screenshot/slor14.png).

#### Output
![Gambar 1](screenshot/slor15.png).


### 5. Menambahkan CSS Selector

Menambahkan id dan class pada Eksternal CSS.
#### Input
![Gambar 1](screenshot/slor16.png).

#### Ouput
![Gambar 1](screenshot/slor17.png).






### Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!

3. Apa perbedaan ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Dekalarasi manakah yang akan ditampi;kan pada browser? Berikan penjelasan dan contohnya!

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! <p id="paragraf-1" class="text-paragraf">

### Jawaban

1. Eksperimen:
#### input CSS:
![Gambar 1](screenshot/slor18.png).

![Gambar 1](screenshot/slor19.png).

![Gambar 1](screenshot/slor20.png).

#### Ouput:
![Gambar 1](screenshot/slor21.png).

2. Perbedaannya itu tag h1 ketika di css maka semua tag h1 yang ada di file akan terkena perubahab dari css yang diberikan. sementara untuk #intro h1 itu tidak semua h1 yang ada di file akan berubah, dan yang mengalami perubahan hanya id dengan #intro h1.

3. Perbedaannya CSS Internal itu CSS yang ditulis/diketik dalam satu file dan tempatnya saya biasa menaruh di bawah tittle.
#### Contoh:
![Gambar 1](screenshot/slor3.png).

CSS Eksternal itu CSS yang diketik/ditulis di file yang berbeda. jadi harus menggunakan link rel untuk menghubungkan antara file HTML dan CSS. 
#### Contoh:
File html
![Gambar 1](screenshot/slor1.png).

File css
![Gambar 1](screenshot/slor2.png).

Untuk Inline CSS itu biasanya tag CSS yang langsung diketik dibaris tag HTML seperti (P style="background-color: blue; dst").
#### Contoh:
![Gambar 1](screenshot/slor4.png).

4. Menurut saya yang akan dideklarasikan CSSnya adalah yang (id), dikarenakan (id) itu lebih spesifik/lebih kuat seperti halnya warna putih(class) ketika dicampur warna lain(id) maka warna yang akan muncul adalah warna lain(id).
contoh:
#### Input:
![Gambar 1](screenshot/slor5.png).

#### Output

![Gambar 1](screenshot/slor6.png).

Jadi, kesimpulannya (id) yang akan di deklarasikan CSS nya.
