# Lab2 PEMOGRAMAN WEB

# CSS Dasar

Nama    : Nadya Khairunnisa

NIM     : 312210133

Kelas   : TI.22.A.1

# Intruksi Praktikum

1. Persiapkan text editor misalnya VSCode
   
2. Lalu buat file baru terlebih dahulu, dengan nama "lab2_css_dasar.html"

3. Buat struktur dasar dari dokumen HTML

4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya

5. Lakukan validasi dokumen css dengan mengakses https://jigsaw.w3.org/css-validator/    

# Langkah-Langkah Praktikum

1. Pertama kita buat dokumen HTML seperti gambar berikut

![lab2 awal](https://github.com/nadyakhorun/Lab2_CSS_Dasar/assets/115801823/01b2bd0e-44e9-48be-a3ef-299d71c8848e)

2. Setelah itu kita langsung run untuk melihat hasilnya, seperti gambar berikut

![lab2 awal 1](https://github.com/nadyakhorun/Lab2_CSS_Dasar/assets/115801823/5bababb0-19f4-4b01-b500-1a4131e8f080)

3. Lalu kita akan membuat deklarasi CSS Internal seperti gambar berikut

![lab2 baru](https://github.com/nadyakhorun/Lab2_CSS_Dasar/assets/115801823/d6724d1a-b51f-4e9e-bad7-dcc32f60d074)

4. Selanjutnya kita akan run kembali untuk melihat hasilnya, seperti gambar berikut

![lab2 baru1](https://github.com/nadyakhorun/Lab2_CSS_Dasar/assets/115801823/07e63556-3001-423d-8264-f27bebe0a9e8)

5. Setelah itu tambahkan deklarasi inline CSS pada tag < p > seperti berikut.
![lab2 baru2](https://github.com/nadyakhorun/Lab2_CSS_Dasar/assets/115801823/121220f1-03a2-49c8-ab14-ac0354d79dd9)

6. Kemudian kita run kembali untuk melihat hasil yang terbarunya, seperti gambar berikut

![lab2 baru3](https://github.com/nadyakhorun/Lab2_CSS_Dasar/assets/115801823/63185038-c306-4a75-9ad2-361843c0ee7e)

7. Selanjutnya kita buat CSS Eksternal, buat file baru terlebih dahulu dengan nama file "style_eksternal.css" seperti gambar berikut

![lab2 awal 6](https://github.com/nadyakhorun/Lab2_CSS_Dasar/assets/115801823/c7a70099-5580-4a13-8dae-2b521c763935)

8. Selanjutnya membuat deklarasi CSS seperti gambar dibawah

![lab2 baru4](https://github.com/nadyakhorun/Lab2_CSS_Dasar/assets/115801823/6b20e25b-996d-412f-9a10-34aa8bb6661f)

9. Kemudian tambahkan tag < link > untuk merujuk file css yang sudah dibuat pada bagian < head > seperti gambar berikut

![lab2 baru5](https://github.com/nadyakhorun/Lab2_CSS_Dasar/assets/115801823/2a202915-9bcb-43c5-b747-44709bc7ca0e)

10. Setelah itu kita coba dirun kembali untuk melihat hasilnya, seperti gambar dibawah

![lab2 baru6](https://github.com/nadyakhorun/Lab2_CSS_Dasar/assets/115801823/7c62d331-54db-4c0c-ab5c-fbf0a05bbdf9)

11. Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file "style_eksternal.css",
tambahkan kode berikut.

![lab2 baru7](https://github.com/nadyakhorun/Lab2_CSS_Dasar/assets/115801823/5a86f1fb-24fc-4498-b753-3e9f39db12ac)

12. Lalu dirun kembali untuk melihat hasil yang terbarunya seperti dibawah ini

![lab2 baru8 hasil akhir](https://github.com/nadyakhorun/Lab2_CSS_Dasar/assets/115801823/d31fcaa4-991c-4480-8e63-a57d97845274)

Pertanyaan
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

   jawab :
   
3. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!

   jawab :

   - h1 {...} : Deklarasi ini akan merubah semua elemen "h1".

   - intro h1 {...} : Deklarasi ini lebih spesifik, maksud nya adalah pendeklarasian yang mengacu kepada 
     pemberian atribut pada elemen "h1" dengan menambahkan id "intro".

4. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!

   jawab :

   Ketika kita mendeklarasikan secara bersamaan antara INTERNAL EKSTERNAL dan INLINE yang akan ditampilkan 
   pada Browser adalah INLINE, karena INLINE memiliki prioritas dibanding EKSTERNAL atau pun INTERNAL 
   seperti contoh yang saya buat, saya membuat dokumen baru HTML kemudian saya buat Elemen {h1}yang 
   kemudian saya akan deklarasikan di CSS INTERNAL EKSTERNAL dan juga INLINE Dengan property {color} dengan 
   warna yang berbeda,jika INTERNAL {color: orange} sementara EKSTERNAL {color:aqua;} dan INLINE {color: 
   red;} yang terpanggil dibrowser adalah INLINE karena memiliki prioritas.

   Jadi yang terpanggil adalah CSS INLINE karena memiliki prioritas tinggi dibanding CSS deklarasi lainnya.
   
5. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya!      (    < p id="paragraf-1" class="text-paragraf" >    )

# SEKIAN, TERIMA KASIH
