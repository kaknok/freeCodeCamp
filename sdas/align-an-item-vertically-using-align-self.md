## [Sejajarkan Item Secara vertikal menggunakan align-self](https://learn.freecodecamp.org/responsive-web-design/css-grid/align-an-item-vertically-using-align-self)

Sama seperti Anda dapat menyelaraskan item secara horizontal, ada cara untuk menyelaraskan item secara vertikal juga. Untuk melakukan ini, Anda menggunakan properti **align-self** pada item. Properti ini menerima semua nilai yang sama sebagai **justify-self** dari tantangan terakhir.

#### cosol:

```
Align the item with the class item3 vertically at the end.

item3 class should have a align-self property that has the value of end.
```

```css
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  
  .item3 {
    background: PaleTurquoise;
    /* add your code below this line */
    
    
    /* add your code above this line */
  }
  
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
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  
  .item3 {
    background: PaleTurquoise;
    /* add your code below this line */
    align-self: end;
    
    /* add your code above this line */
  }
  
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

![](/assets/111.jpg)

