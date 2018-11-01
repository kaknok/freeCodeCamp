## [Gunakan baris-grid ke Control Spacing](https://learn.freecodecamp.org/responsive-web-design/css-grid/use-grid-row-to-control-spacing)

Tentu saja, Anda dapat membuat item mengkonsumsi beberapa baris seperti yang Anda bisa dengan kolom. Anda menentukan garis horizontal yang Anda inginkan item untuk memulai dan berhenti menggunakan properti **grid-row** pada item grid.

#### cosol:

```
Make the element with the item5 class consume the last two rows.

item5 class should have a grid-row property that has the value of 2 / 4.
```

```css
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  
  .item5 {
    background: PaleGreen;
    grid-column: 2 / 4;
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

![](/assets/14.jpg)

#### jasol:

```css
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}
  
  .item5 {
    background: PaleGreen;
    grid-column: 2 / 4;
    /* add your code below this line */
    grid-row: 2 / 4;
    
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

![](/assets/144.jpg)

