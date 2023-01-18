# Nama : Naza Sefti Prianita

# NIM : 312210306

# Kelas : TI.22.A3

# Praktikum 11 (Pertemuan 15)

# Penjelasan

- !pip install pandas digunakan untuk menginstall package pandas di python. Package pandas digunakan untuk memanipulasi data dalam bentuk tabel (dataframe) dan digunakan untuk data analysis. Fungsi dari package pandas sangat luas, seperti melakukan operasi pada data, mengimport dan mengeksport data dari berbagai format, dan lainnya. !pp install request digunakan untuk menginstall package request di python. Package request digunakan untuk melakukan HTTP request dari python.

- !pip install BeautifulSoup4 digunakan untuk menginstall package BeautifulSoup4 digunakan untuk mengelola data dari HTML atau XML.

- import pandas as pd digunakan untuk mengimport library pandas dan penyebutnya sebagai pd. Library pandas digunakan untuk memanipulasi data dalam bentuk tabel (dataframe) dan digunakan untuk data analysis.

- from bs4 import BeautifulSoup digunakan untuk mengimport class BeautifulSoup dari package BeautifulSoup4. Class BeautifulSoup digunakan untuk mengolah data dari HTML atau XML.

![pip](https://user-images.githubusercontent.com/115772516/213188218-bdd61634-67e7-48a7-ba04-693d28c1295b.jpeg)

# Penjelasan

- mengambil data lowongan kerja dari situs web Glints. Dengan menggunakan library Python'request', kodingan mengirim permintaan GET ke URL "https://glints.com/id/lowongan-kerja" yang merupakan halaman web yang berisi informasi lowongan kerja. kemudian, dengan menggunakan library'BeautifulSoup', kodingan menganalisis konten halaman web yang didapat dari permintaan GET tersebut dengan menggunakan parser HTML.

- Selanjutnya, kodingan mencari semua elemen HTML dengan atribut 'div' dan 'id' yang sesuai, yaitu '__next'. Kemudian, dari elemen-elemen tersebut, kodingan mengekstrak informasi pekerjaan, lokasi, dan nama perusahaan dengan mencari elemen yang memiliki atribut 'class' yang sesuai. Informasi yang diambil kemudian disimpan dalam sebuah list yang sesuai.

- Setelah itu, kodingan menggunakan library pandas untuk membuat dataframe dari list yang didapat dan menyimpannya dalam variabel 'df'. Kemudian kodingan mencetak dataframe tersebut, sehingga kita dapat melihat informasi lowongan kerja yang diambil dari situs web Glints.

![output](https://user-images.githubusercontent.com/115772516/213190824-27cb93d8-a919-49c5-b05a-c3185bd4903c.jpeg)
