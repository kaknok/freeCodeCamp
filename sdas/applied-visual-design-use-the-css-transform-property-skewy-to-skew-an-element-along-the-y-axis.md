## Desain Visual Terapan: Gunakan CSS Transform Property miring ke Skew an Elemen Sepanjang Y-Axis

Mengingat bahwa skewX \(\) fungsi skews elemen yang dipilih sepanjang X-axis dengan tingkat tertentu, maka tidak mengherankan bahwa properti skewY \(\) skews elemen di sepanjang Y \(vertikal\) axis.

#### casol:

```
Skew the element with the id of top -10 degrees along the Y-axis by using the transform property.

The element with id top should be skewed by -10 degrees along its Y-axis.
```

```css
<style>
  div { 
    width: 70%;
    height: 100px;
    margin: 50px auto;
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

![](/assets/sol.jpg)

#### jasol:



