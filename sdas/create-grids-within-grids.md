## [Buat Grids dalam Grids](https://learn.freecodecamp.org/responsive-web-design/css-grid/create-grids-within-grids)

Mengubah elemen menjadi grid hanya mempengaruhi perilaku keturunan langsungnya. Jadi dengan mengubah turunan langsung menjadi grid, Anda memiliki grid dalam grid.



Sebagai contoh, dengan mengatur properti **display** dan **grid-template-columns** dari elemen dengan kelas **item3**, Anda membuat grid dalam grid Anda.

#### cosol:

```
Turn the element with the item3 class into a grid with two columns with a width of auto 
and 1fr using display and grid-template-columns.

item3 class should have a grid-template-columns property with auto and 1fr as values.
item3 class should have a display property with the value of grid.
```

```css
<style>
  .container {
    font-size: 1.5em;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: auto 1fr;
    grid-template-rows: auto 1fr auto;
    grid-gap: 10px;
    grid-template-areas:
      "advert header"
      "advert content"
      "advert footer";
  }
  .item1 {
    background: LightSkyBlue;
    grid-area: header;
  }
  
  .item2 {
    background: LightSalmon;
    grid-area: advert;
  }
  
  .item3 {
    background: PaleTurquoise;
    grid-area: content;
    /* enter your code below this line */
    
    
    /* enter your code above this line */
  }
  
  .item4 {
    background: lightpink;
    grid-area: footer;
  }
  
  .itemOne {
    background: PaleGreen;
  }
  
  .itemTwo {
    background: BlanchedAlmond;
  }
  
</style>

<div class="container">
  <div class="item1">header</div>
  <div class="item2">advert</div>
  <div class="item3">
    <div class="itemOne">paragraph1</div>
    <div class="itemTwo">paragraph2</div>
  </div>
  <div class="item4">footer</div>
</div>
```

![](/assets/12q.jpg)

#### jasol:

```css

```



