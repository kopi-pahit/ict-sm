---
layout: post
title: Table: padding & spacing
---



Cell padding adalah jarak antara tepi sel dan isi sel.

Secara default padding diatur ke 0.

perhatikan syntax berikut:

```

<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
th, td {
  padding: 15px;
}
</style>
</head>
<body>

<h2>Cellpadding</h2>
<p>Cell padding specifies the space between the cell content and its borders.</p>

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>

```


Untuk menambahkan padding hanya di bagian atas isi, gunakan properti _padding-top_


Dan yang properti yang lainnya sebagai berikut: _padding-bottom, padding-left, dan padding-right_


spacing sel adalah jarak antar sel.

Secara default, spasi diatur ke 2 piksel.

Untuk mengubah spasi antar sel tabel, gunakan border-spacing properti CSS pada table elemen:

```

<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
}
table {
  border-spacing: 30px;
}
</style>
</head>
<body>

<h2>Cellspacing</h2>
<p>Change the space between the cells with the border-spacing property.</p>

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>

</body>
</html>

```
untuk mencoba dan sumber syntax clik link berikut: 
[dadding table](
https://www.w3schools.com/html/html_table_padding_spacing.asp)
_lanjut ke pembahasan selanjutnya_ 

[Form HTML]({{site.baseurl}}/Form/)