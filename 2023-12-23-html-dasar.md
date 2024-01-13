---
layout: post
title: HTML Dasar "hello world"
---

<p>Sebelum lebih jauh belajar HTML kita persipkan dulu beberapa pelengkap untuk belajar bahasa markup ini. yang perlu kita siapkan adalah aplikasi code editor. kode editor bebas dan banyak sekali di internet, silahkan pilih dan install untuk di gunakan</p>

<p> Setelah menginstal code editor silahkan ketik syntax di bawah ini</p>

```
<!DOCTYPE html>
<html>
    <head>
        <title>Hello World</title>
    </head>

    <body>
        "Hello world"
    </body>

</html>

```

lalu simpan, **perhatikan** ketika menyimpan pastikan dengan cara :
- klik file > save as
- lalu di beri nama/judul "latihan.html" (untuk nama file bebas tapi jangan sampai lupa di akhir nama file harus ada _**.html**_).
- lalu buka dengan web browser ( klik kanan file yang tadi di buat, lalu pilih menu open with, pilih web browser kesukaan kamu) 

selanjutnya yang akan kita pelajari kali adalah element, tag, dan atribut.

element, tag dan atribut merupakan tiga bagian penting dalam HTML seperti syntax di atas.

## Element ##


Element adalah komponen yang menyusun dokument HTML. Adapun element pada Syntax HTML di atas meliputi 
**HTML**, **head**, **title**, **body**. Sedangkan element dalam HTML ada banyak, silahkan pelajari lebih lanjut [Element HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).

Element di bentuk dari tag pembuka, tag isi, dan tag penutup, peratikan syntax di bawah ini:

```
<p>hallo guys!!</p>

```

**Keterangan :**


1. _<p>_ adalah tag pembuka.
2. "hallo guys!!" adalah isi tag.
3. _</p>_ adalah tag penutup.


## Tag ##

Tag adalah sebuah penanda awal dan akhiran dari sebuah element HTML yang di buat dengan kurung siku <> yang berisi tag yang kadang di tambahi atribut. 

Contoh:

```
<p align="center">"Hello World"</p>

```
**Keterangan :**


1. _<p>_ adalah tag pembuka.
2. "Hallo world' adalah isi tag.
3. _</p>_ adalah tag penutup.
4. align="center" contoh atribut

tag selalu di tulis berpasangan, ada tag pembuka dan dan penutupnya, meskipun ada beberapa tag yang tidak memiliki pasangan. tag ada sekitar 250 tag.

kita **tidak** harus menghafal semua, namun kita harus tahu aturan penulisan dan beberapa tag wajib HTML. perhatikan di bawah ini:

- _<!DOCTYPE html>_ pengenal jenis document.
- _<HTML>_ tag utama html.
- _<head>_ tag bagian kepala web, dimana kita letakkan css dan atau java script dan juga meta google.
- _<title>_ tag judul web kita.
- _<body>_ tag isi web yang kita buat.

**catatan:**
- pastikan menghafal tag wajib.
- tulis dengan huruf kecil.
- pastikan menutup tag.


## Atribut ##
Atribut adalah kata kunci khusus yang berada di dalam tag pembuka. Atribut juga disebut sebagai _modifier_ yang akan menentukan perilaku element.

Contoh:

```
<tag atribut="nilai">isi tag</tag>
```

```
<p align="center">"Hello World"</p>

```
**Keterangan :**


1. _<p>_ adalah tag pembuka.
2. "Hallo world' adalah isi tag.
3. _</p>_ adalah tag penutup.
4. align="center" contoh atribut

Jenis-jenis atribut HTML

1. Atribut Global adalah atribut yang bisa ditambahkan di semua element HTML
2. Atribut event adalah atribut yang di gunakan untuk menentukan aksi yang akan dilakukan saat terjadi sesuatu pada element.
3. Atribut khusus adalah atribut yang hanya bisa di pakai pada element tertentu dan kadang atribut ini tidak bisa di pakai di atribut lain.

_lanjut ke pembahasan selanjutnya_ 

[Tag HTML]({{site.baseurl}}/tag/)
