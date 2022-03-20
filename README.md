# **Praktikum 2**
  ---------------
|Nama			|Kelas		|NIM		|
|-----			|-----		|-----		|
|Syahru	Raga Ramdhani	|TI.20.A.2	|312010354	|

## **Pertanyaan dan Tugas**
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen `h1` `{...}` dengan `#intro h1 {...}`? berikan penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat _ID_ dan _Class_, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?Berikan penjelasan dan contohnya! `(<p id="paragraf-1" class="text-paragraf">)`

## **Langkah-Langkah Praktikum**
### **Langkah 1**
* Membuat Dokumen HTML seperti berikut.
![Img](/Img/Capture1.PNG)
* Lalu buka browser untuk melihat hasilnya.
![Img](/Img/Capture2.PNG)</br>
### **Langkah 2**
* Tambahkah CSS seperti berikut pada bagian head dokumen.
![Img](/Img/Capture3.PNG)
* Lalu save perubahannya, dan lakukan refresh pada browser untuk melihat hasilnya.
![Img](/Img/Capture4.PNG)</br>
### **Langkah 3**
* Kemudian tambahkan deklarasi inline CSS pada tag `<p>` seperti berikut.</br>
``` <p style="text-align: center; color: #ccd8e4;"> ``` <br/>
* Save kembali untuk melihat hasilnya pada browser.
![Img](/Img/Capture5.PNG)</br>
### **Langkah 4**
* Buatlah file baru kemudian membuat deklarasi CSS seperti berikut.
![Img](/Img/Capture6.PNG)
* Kemudian tambahkan tag `<link>` untuk merujuk file css yg sudah dibuat pada bagian `<head>`
```
 <head>
    <!-- menyisipkan css eksternal -->
    <link rel="stylesheet" href="style_eksternal.css" type="text/css">
  </head>
```
* Lalu save kemudian save kembali untuk melihat hasilnya pada browser.
![Img](/Img/Capture7.PNG)</br>
### **Langkah 5**
* Lalu tambahkan CSS selector menggunakan Id dan Class Selector. Pada file CSS, Tambahkan kode berikut.
![Img](/Img/Capture8.PNG)
* Kemudian save kembali untuk melihat hasilnya pada browser.
![Img](/Img/Capture9.PNG)