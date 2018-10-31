## [Gunakan Properti yang tumbuh secara fleksibel untuk Memperluas Item](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/use-the-flex-grow-property-to-expand-items)

Kebalikan dari **flex-shrink** adalah properti **flex-grow**. Ingat bahwa **flex-shrink** mengecilkan ukuran item ketika wadah menyusut. Properti **flex-grow** mengontrol ukuran item ketika container induk mengembang.

Menggunakan contoh serupa dari tantangan terakhir, jika satu item memiliki nilai **flex-grow** 1 dan yang lainnya memiliki nilai **flex-grow** sebesar 3, nilai satu dengan nilai 3 akan tumbuh tiga kali lebih banyak dari yang lain.

#### cosol:

```
Add the CSS property flex-grow to both #box-1 and #box-2. Give #box-1 a value of 1 and #box-2 a value of 2.

The #box-1 element should have the flex-grow property set to a value of 1.
The #box-2 element should have the flex-grow property set to a value of 2.
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
    
  }
  #box-2 {
    background-color: orangered;
    height: 200px;
    
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```

#### jasol:

```css
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  
  #box-1 {
    background-color: dodgerblue;
    height: 200px;
    flex-grow: 1;
  }
  #box-2 {
    background-color: orangered;
    height: 200px;
    flex-grow: 2;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```



