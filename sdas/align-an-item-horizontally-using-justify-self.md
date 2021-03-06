## [Sejajarkan Item secara Horizontal menggunakan pembenaran diri](https://learn.freecodecamp.org/responsive-web-design/css-grid/align-an-item-horizontally-using-justify-self)

Di CSS Grid, konten dari setiap item terletak di kotak yang disebut sebagai sel. Anda dapat menyelaraskan posisi konten dalam selnya secara horizontal menggunakan properti **justify-self** pada item grid. Secara default, properti ini memiliki nilai **stretch**, yang akan membuat konten mengisi seluruh lebar sel. Properti Grid CSS ini menerima nilai lain juga:

* **start**: selaraskan konten di sebelah kiri sel,

* **center**: selaraskan konten di tengah sel,

* **end**: selaraskan konten di sebelah kanan sel.

#### cosol:

```
Use the justify-self property to center the item with the class item2.

item2 class should have a justify-self property that has the value of center.
```

```css
<style>
  .item1{background: LightSkyBlue;}
  
  .item2 {
    background: LightSalmon;
    /* add your code below this line */
    
    
    /* add your code above this line */
  }
  
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  .item5{background:PaleGreen;}
  
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
  .item1{background: LightSkyBlue;}
  
  .item2 {
    background: LightSalmon;
    /* add your code below this line */
    justify-self: center;
    
    /* add your code above this line */
  }
  
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  .item5{background:PaleGreen;}
  
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

![](/assets/15.jpg)

