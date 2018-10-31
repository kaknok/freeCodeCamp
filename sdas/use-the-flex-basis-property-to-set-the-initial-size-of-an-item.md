## [Gunakan Properti flex-basis untuk Mengatur Ukuran Awal Item](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/use-the-flex-basis-property-to-set-the-initial-size-of-an-item)

Properti **flex-base** menentukan ukuran awal dari item sebelum CSS membuat penyesuaian dengan **flex-shrink** atau **flex-grow**.



Satuan yang digunakan oleh properti **flex-base** sama dengan properti ukuran lainnya \(**px, em,%,** dll.\). Nilai item ukuran **auto** berdasarkan konten.

#### cosol:

```
Set the initial size of the boxes using flex-basis. 
Add the CSS property flex-basis to both #box-1 and #box-2. 
Give #box-1 a value of 10em and #box-2 a value of 20em.

The #box-1 element should have a flex-basis property.
The #box-1 element should have a flex-basis value of 10em.
The #box-2 element should have the flex-basis property.
The #box-2 element should have a flex-basis value of 20em.
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
    flex-basis: 10em;
  }
  #box-2 {
    background-color: orangered;
    height: 200px;
    flex-basis: 20em;
  }
</style>
  
<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```

![](/assets/asdasdw.jpg)

