## [Gunakan area grid Tanpa Membuat Templat Area](https://learn.freecodecamp.org/responsive-web-design/css-grid/use-grid-area-without-creating-an-areas-template)

Properti **grid-area** yang Anda pelajari dalam tantangan terakhir dapat digunakan dengan cara lain. Jika grid Anda tidak memiliki templat bidang untuk referensi, Anda dapat membuat area dengan cepat agar suatu item ditempatkan seperti ini:

```css
item1 {area-grid: 1/1/2/4; }
```

Ini menggunakan nomor baris yang Anda pelajari sebelumnya untuk menentukan di mana area untuk item ini nantinya. Angka-angka dalam contoh di atas mewakili nilai-nilai ini:

```css
grid-area: horizontal line to start at / vertical line to start at / horizontal line to end at 
/ vertical line to end at;
```

Jadi item dalam contoh akan mengkonsumsi baris antara baris 1 dan 2, dan kolom antara garis 1 dan 4.



#### cosol:

```
Using the grid-area property, place the element with item5 class between the third and 
fourth horizontal lines and between the first and fourth vertical lines.

item5 class should have a grid-area property that has the value of 3/1/4/4.
```

```css
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  
  .item5 {
    background: PaleGreen;
    /* add your code below this line */
    
    
    /* add your code above this line */
  }
  .container {
    font-size: 40px;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
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
```

![](/assets/13.jpg)

#### jasol:

```css
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  
  .item5 {
    background: PaleGreen;
    /* add your code below this line */
    
    grid-area: 3/1/4/4;    
    /* add your code above this line */
  }
  .container {
    font-size: 40px;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
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
```

![](/assets/141.jpg)

