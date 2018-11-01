## [Tambahkan Kolom dengan grid-template-kolom](https://learn.freecodecamp.org/responsive-web-design/css-grid/add-columns-with-grid-template-columns)

Cukup membuat elemen grid tidak membuat Anda sangat jauh. Anda perlu menentukan struktur grid juga. Untuk menambahkan beberapa kolom ke grid, gunakan properti **grid-template-columns** pada penampung grid seperti yang ditunjukkan di bawah ini:

```css
.container {
   display: grid;
   grid-template-columns: 50px 50px;
}
```



Ini akan memberikan grid Anda dua kolom yang masing-masing memiliki lebar 50px.



Jumlah parameter yang diberikan ke properti **grid-template-columns** menunjukkan jumlah kolom dalam grid, dan nilai setiap parameter menunjukkan lebar setiap kolom.

