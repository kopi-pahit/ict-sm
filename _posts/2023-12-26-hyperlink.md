---
layout: post
title: HYPERLINK
---

link,hyperlink atau web link adalah sebuah koneksi dari sebuah sumber web ke sumber lain, bisa di sebut juga jika tidak ada link maka tidak ada juga web. link pada HTML menggunakan tag anchor <a></a>, perhatiam syntax di bawah untuk penulisan tag link


```
<!DOCTYPE html>
<html>
    <head>
        <title>hyperlink</title>
    </head>

    <body>

    <h1>membuat hyperlink atau link</h1>
    
    <p>Klik <a href="https://www.google.com">disini</a> untuk informasi lebih lengkap</p>

    </body>

</html>

```

syntax di atas setelah tag ada href yang mana bisa kita isi dengan external link atau internal link.

contoh bila menggunakan external link yaitu seperti di contoh "href="https://www.google.com".

bila menggunakan internal link / relatif semisal kita buat file html baru dan kita tempatkan filenya satu folder dengan file html yang berisi tag link, maka tag nya "href=/file.html" andaikan file yang ingin kita masukkan ke link berbeda folder maka kita sesuaikan dengan nama folder, misal file target ada di folder "images" maka kita ketikkan "href=/images/file.html". jika file yang memuat link dan link target sama-sama di dalam folder yang berbeda maka penulisannya sedikit berbeda, yaitu dengan menambahkan titik "href=../images/file.html" dan jika file yang memuat link target dengan nama home umpama ada di folder user, maka jika ingin kembali dengan memuat file awal maka tinggal menyesuaikan folder dimana filenya berada, contoh penulisannya "href=../user/home.html".

kita juga bisa membuat link untuk bagian-bagian artikel di dalam html. perhatikan syntax berikut:

```
<!DOCTYPE html>
<html>
    <head>
        <title>hyperlink</title>
    </head>

    <body>

    <h1>membuat hyperlink atau link</h1>
    
    <ul>
    <li><a href="#bagian1">bagian 1</a></li>
    <li><a href="#bagian2">bagian 2</a></li
    <li><a href="#bagian3">bagian 3</a></li
    </ul>
    <h2 id="bagian1">bagian 1</h2>
    <p>lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum</p>


    < id="bagian2">bagian 2</h2>
    <p>lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum</p>




     <h2 ="bagian3">bagian 3</h2>
    <p>lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum</p>
    </body>

</html>

```

jika nanti kita klik list bagian 1 maka akan ke paragraf satu, jika kita klik bagian 2 maka akan ke paragraf 2 dan seterusnya.


_lanjut ke pembahasan selanjutnya_ 
[Image HTML]({{site.baseurl}}/image/)