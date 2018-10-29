## Desain Visual Terapan: Gunakan CSS Transform Property skewX yang Condong / Miring pada sebuah Elemen Sepanjang X-Axis

Fungsi selanjutnya dari properti transform adalah **skewX\(\)**, yang menyorot elemen yang dipilih sepanjang sumbu X \(horizontal\) dengan suatu derajat tertentu.

Kode berikut ini memutar elemen paragraf dengan -32 derajat sepanjang sumbu X.

```css
p {
  transform: skewX(-32deg);
}
```

#### cosol:

```
Skew the element with the id of bottom by 24 degrees along the X-axis by using the transform property.

The element with id bottom should be skewed by 24 degrees along its X-axis.
```

```css
<style>
  div { 
    width: 70%;
    height: 100px;
    margin:  50px auto;
  }
  #top {
    background-color: red;
  }
  #bottom {
    background-color: blue;
    
  }
</style>

<div id="top"></div>
<div id="bottom"></div>
```

![](/assets/redo.jpg)



#### jasol:

```css
<style>
  div { 
    width: 70%;
    height: 100px;
    margin:  50px auto;
  }
  #top {
    background-color: red;
  }
  #bottom {
    background-color: blue;
    transform: skewX(24deg);
  }
</style>

<div id="top"></div>
<div id="bottom"></div>
```

![](/assets/redos.jpg)



