## [Tambahkan Baris dengan baris-template-grid](https://learn.freecodecamp.org/responsive-web-design/css-grid/add-rows-with-grid-template-rows)

Grid yang Anda buat di tantangan terakhir akan mengatur jumlah baris secara otomatis. Untuk menyesuaikan baris secara manual, gunakan properti **grid-template-rows** dengan cara yang sama yang Anda gunakan **grid-template-columns** dalam tantangan sebelumnya.

#### cosol:

```
Add two rows to the grid that are 50px tall each.

container class should have a grid-template-rows property with two units of 50px.
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
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 100px 100px 100px;
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

![](/assets/kedo.jpg)

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
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 100px 100px 100px;
    /* add your code below this line */
    grid-template-rows: 50px 50px;
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

###### ![](/assets/aawwee.jpg) jadi sedikit lebih besar kotak2 ny



