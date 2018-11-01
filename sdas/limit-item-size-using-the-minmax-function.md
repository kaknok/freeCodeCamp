## [Batas Ukuran Barang Menggunakan Fungsi minmax](https://learn.freecodecamp.org/responsive-web-design/css-grid/limit-item-size-using-the-minmax-function)

Ada fungsi built-in lain untuk digunakan dengan **grid-template-columns** dan **grid-template-rows** yang disebut **minmax**. Ini digunakan untuk membatasi ukuran item ketika ukuran kontainer grid berubah. Untuk melakukan ini, Anda perlu menentukan kisaran ukuran yang dapat diterima untuk item Anda. Berikut ini contohnya:

```css
grid-template-columns: 100px minmax(50px, 200px);
```

Pada kode di atas, **grid-template-columns** diatur untuk membuat dua kolom; yang pertama adalah lebar 100px, dan yang kedua memiliki lebar minimum 50px dan lebar maksimum 200px.



#### cosol:

```
Using the minmax function, 
replace the 1fr in the repeat function with a column size that has the minimum width of 90px 
and the maximum width of 1fr, and resize the preview panel to see the effect.

container class should have a grid-template-columns property that is set to repeat 3 columns 
with the minimum width of 90px and maximum width of 1fr.
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
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    /* change the code below this line */
    
    grid-template-columns: repeat(3, 1fr);
    
    /* change the code above this line */
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
  .item5{background:PaleGreen;}
  
  .container {
    font-size: 40px;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    /* change the code below this line */
    
    grid-template-columns:  repeat(3, minmax(90px, 1fr) );
    
    /* change the code above this line */
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

###### ![](/assets/13.jpg)  panel di resize akan membesar dan mengecil 



