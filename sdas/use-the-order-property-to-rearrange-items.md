## [Gunakan pesanan Properti untuk Mengatur Ulang Item](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/use-the-order-property-to-rearrange-items)

Properti **order** digunakan untuk memberi tahu CSS urutan bagaimana item flex muncul dalam wadah fleksibel. Secara default, item akan muncul dalam urutan yang sama seperti yang ada di sumber HTML. Properti mengambil angka sebagai nilai, dan angka negatif dapat digunakan.

#### cosol:

```
Add the CSS property order to both #box-1 and #box-2. Give #box-1 a value of 2 and give #box-2 a value of 1.

The #box-1 element should have the order property set to a value of 2.
The #box-2 element should have the order property set to a value of 1.
```

```css
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  #box-1 {
    background-color: dodgerblue;
    
    height: 200px;
    width: 200px;
  }
  #box-2 {
    background-color: orangered;
    
    height: 200px;
    width: 200px;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```

![](/assets/asdawdsadasf.jpg)

#### jasol:





