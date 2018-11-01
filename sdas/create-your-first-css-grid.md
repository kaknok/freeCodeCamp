## [Buat Grid CSS Pertama Anda](https://learn.freecodecamp.org/responsive-web-design/css-grid/create-your-first-css-grid)

Ubah elemen HTML apa pun menjadi penampung grid dengan menyetel properti **display** ke **grid**. Ini memberi Anda kemampuan untuk menggunakan semua properti lain yang terkait dengan CSS Grid.



Catatan

Dalam CSS Grid, elemen induk disebut sebagai _container_ dan anak-anaknya disebut _items_.

#### cosol:

```
Change the display of the div with the container class to grid.

container class should have a display property with a value of grid.
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

![](/assets/aswwq.jpg)

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
    /* add your code below this line */
    
      display: grid;    
    
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

![](/assets/aswwq.jpg)

