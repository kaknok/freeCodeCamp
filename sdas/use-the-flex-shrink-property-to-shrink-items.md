## [Gunakan Properti rileks-menyusutkan ke Shrink Items](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/use-the-flex-shrink-property-to-shrink-items)

Sejauh ini, semua properti dalam tantangan berlaku untuk wadah fleksibel \(induk dari item flex\). Namun, ada beberapa properti yang bermanfaat untuk item flex.



Yang pertama adalah properti flex-shrink. Ketika digunakan, itu memungkinkan item menyusut jika wadah fleksibel terlalu kecil. Item menyusut ketika lebar wadah induk lebih kecil dari lebar gabungan semua item flex di dalamnya.



Properti flex-shrink mengambil angka sebagai nilai. Semakin tinggi angkanya, semakin banyak yang menyusut dibandingkan dengan barang-barang lainnya dalam wadah. Sebagai contoh, jika satu item memiliki nilai flex-shrink 1 dan yang lainnya memiliki nilai flex-shrink 3, yang satu dengan nilai 3 akan menyusut tiga kali lebih banyak dari yang lain.



#### cosol:

```
Add the CSS property flex-shrink to both #box-1 and #box-2. Give #box-1 a value of 1 and #box-2 a value of 2.

The #box-1 element should have the flex-shrink property set to a value of 1.
The #box-2 element should have the flex-shrink property set to a value of 2.
```

```css
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  #box-1 {
    background-color: dodgerblue;
    width: 100%;
    height: 200px;
    
  }
  #box-2 {
    background-color: orangered;
    width: 100%;
    height: 200px;
    
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```

![](/assets/erer.jpg)

#### jasol:

```css
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  #box-1 {
    background-color: dodgerblue;
    width: 100%;
    height: 200px;
    flex-shrink: 1;
  }
  #box-2 {
    background-color: orangered;
    width: 100%;
    height: 200px;
    flex-shrink: 1;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```

![](/assets/ereererererer.jpg)

