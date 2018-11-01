## [Buat Layout Fleksibel Menggunakan auto-fill](https://learn.freecodecamp.org/responsive-web-design/css-grid/create-flexible-layouts-using-auto-fill)

Fungsi pengulangan dilengkapi dengan opsi yang disebut pengisian otomatis. Ini memungkinkan Anda untuk secara otomatis memasukkan sebanyak mungkin baris atau kolom sesuai dengan ukuran yang Anda inginkan tergantung pada ukuran wadah. Anda dapat membuat tata letak yang fleksibel saat menggabungkan **auto-fill** dengan **minmax**.

Dalam pratinjau, **grid-template-columns** diatur ke

```css
repeat(auto-fill, minmax(60px, 1fr));
```

Saat penampung berubah ukuran, penyetelan ini terus menyisipkan kolom 60px dan meregangkannya hingga dapat memasukkan yang lain.

Catatan

Jika penampung Anda tidak dapat memuat semua barang Anda dalam satu baris, itu akan memindahkannya ke yang baru.



#### cosol:

```
In the first grid, use auto-fill with repeat to fill the grid with columns 
that have a minimum width of 60px and maximum of 1fr. Then resize the preview to see auto-fill in action.

container class should have a grid-template-columns property with repeat and auto-fill 
that will fill the grid with columns that have a minimum width of 60px and maximum of 1fr.
```

```css
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  .item5{background:PaleGreen;}
  
  .container {
    font-size: 40px;
    min-height: 100px;
    width: 100%;
    background: LightGray;
    display: grid;
    /* change the code below this line */
    
    grid-template-columns: repeat(3, minmax(60px, 1fr));
    
    /* change the code above this line */
      grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
  }
  .container2 {
    font-size: 40px;
    min-height: 100px;
    width: 100%;
    background: Silver;
    display: grid;
    grid-template-columns: repeat(3, minmax(60px, 1fr));
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
  }
</style>
<div class="container">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
<div class="container2">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
```

![](/assets/131.jpg)

#### jasol:

```css
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  .item5{background:PaleGreen;}
  
  .container {
    font-size: 40px;
    min-height: 100px;
    width: 100%;
    background: LightGray;
    display: grid;
    /* change the code below this line */
    
    grid-template-columns: repeat(auto-fill, minmax(60px, 1fr));
    
    /* change the code above this line */
      grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
  }
  .container2 {
    font-size: 40px;
    min-height: 100px;
    width: 100%;
    background: Silver;
    display: grid;
    grid-template-columns: repeat(3, minmax(60px, 1fr));
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
  }
</style>
<div class="container">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
<div class="container2">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
```

![](/assets/113a.jpg)

