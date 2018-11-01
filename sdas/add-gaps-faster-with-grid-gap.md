## [Tambahkan Celah Lebih Cepat dengan jeda kotak](https://learn.freecodecamp.org/responsive-web-design/css-grid/add-gaps-faster-with-grid-gap)

**grid-gap** adalah properti singkat untuk **grid-row-gap** dan **grid-column-gap** dari dua tantangan sebelumnya yang lebih mudah digunakan. Jika **grid-gap** memiliki satu nilai, itu akan menciptakan gap / celah antara semua baris dan kolom. Namun, jika ada dua nilai, itu akan menggunakan yang pertama untuk mengatur kesenjangan antara baris dan nilai kedua untuk kolom.

### cosol:

```
Use grid-gap to introduce a 10px gap between the rows and 20px gap between the columns.

container class should have a grid-gap property 
that introduces 10px gap between the rows and 20px gap between the columns.
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
    grid-template-columns: 1fr 1fr 1fr  ;
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

![](/assets/12.jpg)

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
    grid-template-columns: 1fr 1fr 1fr  ;
    grid-template-rows: 1fr 1fr 1fr;
    /* add your code below this line */
    grid-gap: 10px 20px;
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

![](/assets/13.jpg)

