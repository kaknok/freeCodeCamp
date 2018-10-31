## [Gunakan Properti lentur-arah untuk Membuat Row](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/use-the-flex-direction-property-to-make-a-row)

Menambahkan **display: flex** ke suatu elemen mengubahnya menjadi wadah fleksibel \(flex container\). Ini memungkinkan untuk menyelaraskan setiap anak dari elemen tersebut ke dalam baris atau kolom. Anda melakukan ini dengan menambahkan properti **flex-direction** ke item induk dan mengaturnya ke baris atau kolom. Membuat baris akan menyelaraskan anak-anak secara horizontal, dan membuat kolom akan menyelaraskan anak-anak secara vertikal.

Pilihan lain untuk **flex-direction** adalah row-reverse dan column-reverse.

Catatan

Nilai default untuk properti **flex-direction** adalah baris.

#### cosol:

```
Add the CSS property flex-direction to the #box-container element, and give it a value of row-reverse.

The #box-container element should have a flex-direction property set to row-reverse.
```

```php
<style>
  #box-container {
    display: flex;
    height: 500px;
    
  }
  #box-1 {
    background-color: dodgerblue;
    width: 50%;
    height: 50%;
  }
  #box-2 {
    background-color: orangered;
    width: 50%;
    height: 50%;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```



