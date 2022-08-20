# Belajar-HTML 📂
  Belajar pemrograman web 
  pada kali ini saya akan membagikan tutorial mengenai belajar <a href="https://id.wikipedia.org/wiki/HTML">HTML (Hypertext Markup Language)</a>
  
# APA ITU HTML 
  Apa itu HTMl ? mungkin pertanyaan inilah yang terbersit pada benak anda yang
baru mulai masuk kedalam dunia web programming. HTML merupakan bahasa markah untuk web
yang wajib di kuasai bagi seorang web developer. karena HTML merupakan unsur dasar
dari pembangunan sebuah website. jika di ibaratkan HTML menjadi pondasi pada sebuah rumah
atau bangunan. karena bentuk pada halaman website di buat menggunakan HTML. ini akan di jelaskan tentang pengertian dari HTML
dan sekilas tentang sejarah HTML dan perkembangannya 

# KEGUNAAN HTML 💽
  HTML berfungsi sebagai pondasi sebuah halaman website. adapun yang dapat di lakukan
dengan HTML adalah sebagai berikut :

- Membungkus element-element tertentu sesuai kebutuhan.
- Membuat heading atau format judul.
- Membuat Tabel.
- Membuat List.
- Membuat Paragraf.
- Membuat Form.
- Membuat Tombol.
- Membuat huruf tebal.
- Membuat huruf miring.
- Menampilkan gambar.
- Menampilkan video.

Dan banyak lainnya yang akan kita pelajari pada penjelasan selanjutnya
Sampai saat ini HTML sudah sampai pada versi 5. HTML5 sudah memiliki banyak sekali
fitur tambahan salah satunya, dengan HTML5 memungkinkan kita untuk membuat streaming
video tanpa bantuan adobe flash. untuk tutorial cara membuat streaming video dengan HTML5
juga akan kita bahas pada buku tutorial belajar HTML dasar ini.
jadi kesimpulan dari pengertian HTML ini adalah HTML merupakan pondasi dasar dari
pembuatan sebuah website. untuk mengeksekusi atau menjalankan file html harus menggunakan
web browser dan file html di simpan dengan ekstensi ``.html`` (dot html).

# ALAT YANG DIPERLUKAN ✅
  <details>
  <summary>
  Browser
  </summary>
  <br>
  Browser merupakan aplikasi yang akan kita gunakan untuk menjalankan code program
html yang sudah kita tulis. browser ini ialah syarat yang harus anda penuhi jika anda belajar web
programing. untuk browser itu sendiri bisa digunakan yang sudah disediakan oleh sistem operasi
langsung ataupun bisa juga digunakan aplikasi browser yang lain seperti: Mozilla Firefox,
Opera, Chrome dan sebagainya.
  </details>
<details>
  <summary>
  Text Editor 
  </summary>
  <br>
  Text Editor merupakan aplikasi yang digunakan untuk menulis syntax atau kode program,
disini khususnya untuk penulisan kode program HTML itu sendiri. Text editor sendiri sangatlah
banyak yang bisa digunakan untuk penulisan kode HTML, contohnya seperti Notepad yang
disediakan oleh sistem operasi windows, Textedit yang disediakan oleh sistem operasi Mac dan
Nano yang disediakan oleh sistem operasi linux. Text editor berbeda dengan Word Processor
(Microsoft Word, King Soft, WordPerfect). Itu dikarenakan text editor tidak bisa digunakan
untuk mengatur format document serta tidak disediakan fitur-fitur yang bisa digunakan untuk
desktop publishing
</details>

# Mengenal Tag, Element, Atribut HTML

Setelah sebelumnya kita membahas tentang Pengenalan HTML, Text Editor. kini kita
akan memasuki tutorial pengenalan dan penggunaan Tag, Element dan Atribut dalam HTMl.
Ketiga pembahasan ini merupakan dasar dalam penulisan kode HTML atau dasar dari seluruh
tampilan halaman web yang ada di internet.

# Tag HTML

Tag merupakan kode yang digunakan untuk memperkenalkan pada web browser untuk
apa text HTML yang ditulis. HTML membutuhkan cara memperkenalkan text yang ditulis
didalamnya kepada web browser. baik text itu berupa list, paragraf, link dan sebagainya.
disinilah di gunakan tag. dalam penulisan tag, hampir semua menggunakan pembuka dan
penutup tag, dimana objek yang di maksudkan berada diantara pembuka dan penutup tag. berikut
penulisan tag yang digunakan dalam HTML

```html
<tag> Objek yang diisi </tag>

```
Perbedaan antara tag pembuka dan tag penutup yaitu, pada tag pembuka diawali kurung
sudut pembuka dan di akhiri dengan kurung sudut penutup ``<tag>``, sedangkan pada tag penutup
,diawali dengan kurung sudut pembuka, backslash, dan diakhiri dengan penutup kurung sudut 

``</tag>``

jenis tag yang sering digunakan dalam html
berikut beberapa jenis tag yang akan sering anda jumpai kalo di web programing :

|   Tag HTML.     |   KEGUNAAN    |
| --------------- | ------------- |
|   <!– ….–>      |   Digunakan untuk memberi sebuah komentar atau keterangan |
| ``<a>link</a>`` | Mendefinisikan sebuah anchor, digunakan untuk saling menautkan antara satu dokumen HTML ke dokumen HTML yang lain ``membuat link`` |
| ``<b> </b>`` | Membuat teks menjadi tebal |
| ``<p>  </p>`` | Membuat pargraf |
| ``<h1> </h1>``  | Membuat heading satu |
| ``<h2> </h2>``  | Membuat heading dua |
| ``<body>``  | Mendefinisikan body/isi dokument html |
| ``<head>``  | Mendefinisikan bagian kepala dokumen html |
| ``<title>``     | Mendefiniskan judul halaman |
| ``<div>``      | Mendefinisikan halaman |
| ``<link>``     | Mendefinisikan hubungan antar dokumen |
| ``<script>``   | Mendefinisikan client-side script |
| ``<table>``    | Mendefinisikan table |
| ``<th>``      | Mendefinisikan sel header di dalam sebuah table |
| ``<td>``        | Mendefinisikan sel di dalam sebuah table |
| ``<tr>``        | Membuat baris di dalam sebuah table |
| ``<ul>``        | Mendefinisikan daftar dalam format bullet |
| ``<li>``        | mendefinisikan list |

# Element di HTML
Element pada HTML merupakan isi atau objek yang berada pada tag. maksudnya, isi
yang ada diantara tag pembuka dan tag penutup di sebut dengan elemen misalkan :

```html
<!DOCTYPE html>
<html>
<head>
  <title>SMK RADEN PAKU | X TKJ 1</title>
</head>
<body>
 <strong>
  <h2>Pengenalan atribut HTML</h2>
 </strong>
</body>
</html>
```

pada contoh diatas ``<h2>`` adalah heading dua ``<h2>`` merupakan element ``h2`` dan isinya ini adalah
heading dua. dalam element ini bisa berupa text ataupun tag lain misalnya ``<link>`` dan
sebagainya.

# Atribut 🍁
  Atribut merupakan informasi tambahan yang digunakan di dalam tag pembuka. informasi
ini bisa berupa instruksi untuk memberikan efek warna, ketebalan, dll. atribut bisanya memiliki 2 bagian yaitu nama dan nilai, dapat ditulis dengan ( 
``` name=”value” ```  ). penulisan nilai/value diapit
oleh dua tanda kutip (bisa digunakan kutip satu atau kutip dua).
Penulisan atribut pada HTML diawali dengan penulisan tag, didalam tag berikan atribut
dan element dari tag itu sendiri berikut contoh penulisan atribut pada HTML :

```html 

<!DOCTYPE html>
<html>
<head>
  <title>SMK RADEN PAKU | X TKJ 1</title>
</head>
 <body>
  <h2 align="center">Pengenalan atribut HTML</h2>
 </body>
</html>

```

Perhatikan pada syntax di atas :
- ``<h2>`` adalah tag heading 2
- ``align`` adalah nama dari atribut
- ``center`` adalah nilai/value dari atribut
- ``“Pengenalan atribut HTML”`` adalah element dari tag h2
Tidak semua tag ini membutuhkan atribut di dalamnya, namun bagi anda yang bergelut di
web programing akan sering menjumpai tag yang didalamnya terdapat atribut.

# Heading 🌿
Heading merupakan element atau tag HTML yang berfungsi untuk menunjukkan bagian
penting pada halaman web. element tag heading ini memiliki 6 tingkatan yang berurutan yaitu ``<h1>`` , ``<h2>``, ``<h3>`` , ``<h4>`` , ``<h5>`` , ``<h6>`` yang bisa digunakan untuk menambah ke struktur halaman
web. perbedaan masing-masing heading yaitu besar hingga kecil teks. contohnya tag/element

``<h1>`` lebih besar dari element/tag ``<h2>`` dan seterusnya.
Penggunaan masing-masing heading juga berbeda, berikut penggunaan masing-masing
tag/element heading yang sering digunakan pada pengolahan halaman web :
- ``<h1>`` adalah heading yang digunakan untuk penulisan judul utama dari dokumen
- ``<h2>`` adalah heading yang digunakan sebagai sub dari ``<h1>``
- ``<h3>`` adalah heading yang digunakan sebagai sub dari ``<h2>``

untuk penggunaan ``<h4>`` ``<h4>`` ``<h5>`` ``<h6>`` tergantung programmer sendiri untuk memperindah
halaman web sesuai keperluan.
berikut contoh penerapan masing-masing element/tag heading :

```html

<!DOCTYPE html>
<html>
<head>
<title></title>
</head>
<body>
<h1>ini adalah heading 1</h1>
<h2>ini adalah heading 2</h2>
<h3>ini adalah heading 3</h3>
<h4>ini adalah heading 4</h4>
<h5>ini adalah heading 5</h5>
<h6>ini
adalah heading 6</h6>
</body>
</html>

```
ketika dijalankan di browser maka hasilnya akan seperti ini :

![heading](https://user-images.githubusercontent.com/107765982/185721868-372a19d2-a882-481a-ad00-fb93e40714cb.jpeg)


# Format Text Pada HTML ⌨️

Dalam penuliasan HTML sangat sering menggunakan format text didalamanya. baik itu
dalam penulisan judul, ataupun isi dari konten/halaman
website sendiri. Berikut beberapa
penjelasan dan contoh dari Format Text Pada HTML

Format yang umum digunakan:

- Membuat huruf tebal ( Bold )
untuk membuat teks menjadi tebal pada
 tampilan halaman web
, bisa
 menggunakan tag
``<b>`` berikut
 contoh
syntax HTML untuk membuat format text tebal 

```html
 <b>ini teks tebal</b> 
```
- Membuat huruf miring ( Italic )
untuk membuat teks miring pada HTML, kita bisa menggunakan tag ``<i>``. contohnya:

```html
<i>ini text miring</i>
```

- Membuat huruf bergaris bawah (underline) pada HTML
untuk membuat teks underline/garis bawah pada HTML kita bias menggunakan tag ``<u>``.
contohnya :

```html
<u>ini text underline</u>
```
# Format text yang sering digunakan dalam HTML

| Tag | Deskripsi |
| --- | --------- |
| ``<b>``  | format text bold/tebal |
| ``<i>``  | format text italic/miring |
| ``<u>``   | format text underline/garis bawah |
| ``<small>`` | format text kecil |
| ``<strong>`` | format text yang hampir sama dengan format bold |
| ``<sub>`` | format subscripted teks |
| ``<sup>`` | format superscripted teks |
| ``<ins>`` | format text garis bawah | 
| ``<del>`` | format text dengan garis di tengah |
| ``<mark>`` | format text yang berwarna (seperti stabilo) |

Ini tag tag yang dipelajari diatas :

```html

<!DOCTYPE html>
<html>
 <head>
    <title>belajar format format text</title>
 </head>
 <body>


   <!-- ini komentar pada html dan tidak akan bisa di lihat user pada website , tag komentar hanya berguna bagi programmer untuk menandai bagian bagian yang perlu di tandai --->
   <!-- tag <br> digunakan untuk membuat baris baru --->
<b>ini format format text tebal</b>
   <br>
   <i>ini format text italic</i>
   <br>
   <u>ini format text underline</u>
   <br>
   <em>ini format text em</em><br>
   <small>ini format text small</small><br/>
   <strong>ini format text strong</strong><br/>
   <sub>ini format text sub</sub><br/>
   <sup>ini format text sup</sup><br/>
   <ins>ini format text ins</ins><br/>
   <del>ini format text del</del><br/>
   <mark>ini format text mark</mark>
 </body>
</html>

```
