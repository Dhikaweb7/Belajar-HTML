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

# KEGUNAAN HTML 
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

# ALAT YANG DIPERLUKAN
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
sudut pembuka dan di akhiri dengan kurung sudut penutup ``(<tag>)``, sedangkan pada tag penutup
,diawali dengan kurung sudut pembuka, backslash, dan diakhiri dengan penutup kurung sudut 

``<
tag>``

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
