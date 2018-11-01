## [Tempatkan Item di Area Grid Menggunakan Properti area grid](https://learn.freecodecamp.org/responsive-web-design/css-grid/place-items-in-grid-areas-using-the-grid-area-property)

Setelah membuat templat area untuk penampung grid Anda, seperti yang ditunjukkan pada tantangan sebelumnya, Anda dapat menempatkan item di area khusus Anda dengan merujuk nama yang Anda berikan. Untuk melakukan ini, Anda menggunakan properti area-grid pada item seperti ini:

```css
.item1 {grid-area: header; }
```

Ini memungkinkan grid mengetahui bahwa Anda ingin kelas item1 masuk ke area bernama header. Dalam hal ini, item akan menggunakan seluruh baris teratas karena seluruh baris itu disebut sebagai area header.

#### cosol:

```
Place an element with the item5 class in the footer area using the grid-area property.

item5 class should have a grid-area property that has the value of footer.
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
    grid-template-areas: 
      "header header header"
      "advert content content"
      "footer footer footer";
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
    grid-area: footer;

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
    grid-template-areas: 
      "header header header"
      "advert content content"
      "footer footer footer";
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

![](/assets/18.jpg)

