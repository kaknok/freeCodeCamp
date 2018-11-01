## [Bagilah Grid ke dalam Templat Area](https://learn.freecodecamp.org/responsive-web-design/css-grid/divide-the-grid-into-an-area-template)

Anda dapat mengelompokkan sel-sel grid Anda ke suatu area dan memberi nama khusus pada area tersebut. Lakukan ini dengan menggunakan **grid-template-areas** pada wadah seperti ini:

```css
grid-template-areas:
  "header header header"
  "advert content content"
  "footer footer footer";
```

Kode di atas menggabungkan tiga sel teratas menjadi sebuah area adalah **header**, tiga sel bawah menjadi area **footer**, dan yang membuat dua area di baris tengah; **advert** dan **content**.

Catatan

Setiap kata dalam kode mewakili sel dan setiap pasangan tanda kutip mewakili satu baris.

Selain label khusus, Anda dapat menggunakan periode **\(.\)** Untuk menetapkan sel kosong di grid.

#### cosol:

```
Place the area template so that the cell labeled advert becomes an empty cell.

container class should have a grid-template-areas property similar to the preview but has . 
instead of the advert area.
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
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
    /* change code below this line */
    
    grid-template-areas:
      "header header header"
      "advert content content"
      "footer footer footer";
    /* change code above this line */
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
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
    /* change code below this line */
    
    grid-template-areas:
      "header header header"
      ". content content"
      "footer footer footer";
    /* change code above this line */
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

