## [Sejajarkan Semua Item secara Horizontal menggunakan item justify](https://learn.freecodecamp.org/responsive-web-design/css-grid/align-all-items-horizontally-using-justify-items)

Terkadang Anda ingin semua item di Grid CSS Anda untuk berbagi kesejajaran yang sama. Anda dapat menggunakan properti yang telah dipelajari sebelumnya dan menyelaraskannya satu per satu, atau Anda dapat menyelaraskannya secara horizontal dengan menggunakan justify-items pada container grid Anda. Properti ini dapat menerima semua nilai yang sama yang Anda pelajari dalam dua tantangan sebelumnya, perbedaannya adalah bahwa ia akan memindahkan semua item di grid kita ke penyelarasan yang diinginkan.

#### cosol:

```
Use this property to center all our items horizontally.

container class should have a justify-items property that has the value of center.
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
    /* add your code below this line */
    
    /* add your code above this line */
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





