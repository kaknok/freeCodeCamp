## [Buat Gap Kolom Menggunakan grid-kolom-gap](https://learn.freecodecamp.org/responsive-web-design/css-grid/create-a-column-gap-using-grid-column-gap)

Sejauh ini dalam grid yang telah Anda buat, semua kolom saling berdekatan. Terkadang Anda menginginkan celah di antara kolom. Untuk menambahkan celah di antara kolom, gunakan properti grid-column-gap seperti ini:



```css
grid-column-gap: 10px;
```

Ini menciptakan 10px ruang kosong di antara semua kolom.



#### cosol:

```
Give the columns in the grid a 20px gap.

container class should have a grid-column-gap property that has the value of 20px.
```

```css
<style>
  .d1{background:LightSkyBlue;}
  .d2{background:LightSalmon;}
  .d3{background:PaleTurquoise;}
  .d4{background:LightPink;}
  .d5{background:PaleGreen;}
  
  .container {
    font-size: 40px;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    /* add your code below this line */
    
    /* add your code above this line */
  }
</style>
  
<div class="container">
  <div class="d1">1</div>
  <div class="d2">2</div>
  <div class="d3">3</div>
  <div class="d4">4</div>
  <div class="d5">5</div>
</div>
```

![](/assets/1.jpg)

#### jasol:

```css
<style>
  .d1{background:LightSkyBlue;}
  .d2{background:LightSalmon;}
  .d3{background:PaleTurquoise;}
  .d4{background:LightPink;}
  .d5{background:PaleGreen;}
  
  .container {
    font-size: 40px;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    /* add your code below this line */
    grid-column-gap: 20px;    
    /* add your code above this line */
  }
</style>
  
<div class="container">
  <div class="d1">1</div>
  <div class="d2">2</div>
  <div class="d3">3</div>
  <div class="d4">4</div>
  <div class="d5">5</div>
</div>
```

![](/assets/11.jpg)

