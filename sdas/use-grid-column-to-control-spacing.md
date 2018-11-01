## [Gunakan grid-kolom untuk Mengontrol Spasi](https://learn.freecodecamp.org/responsive-web-design/css-grid/use-grid-column-to-control-spacing)

Hingga saat ini, semua properti yang telah dibahas adalah untuk peti kemas. Properti grid-column adalah yang pertama untuk digunakan pada item grid itu sendiri.

Garis horizontal dan vertikal hipotetis yang menciptakan grid disebut sebagai garis. Garis-garis ini diberi nomor dimulai dengan 1 di sudut kiri atas grid dan bergerak ke kanan untuk kolom dan turun untuk baris, menghitung ke atas.

Ini adalah garis yang terlihat seperti grid 3x3:

![](/assets/000000.jpg)

Untuk mengontrol jumlah kolom yang akan digunakan suatu item, Anda dapat menggunakan properti kolom-grid bersama dengan nomor baris yang Anda inginkan untuk memulai dan berhenti.

Inilah contohnya:

```css
grid-column: 1 / 3;
```

Ini akan membuat item dimulai pada garis vertikal pertama dari grid di sebelah kiri dan menjangkau garis ke-3 dari grid, mengkonsumsi dua kolom.

#### COSOL:

```
Make the item with the class item5 consume the last two columns of the grid.

item5 class should have a grid-column property that has the value of 2 / 4.
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
    grid-column: 2 / 4;
    
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

![](/assets/14.jpg)

