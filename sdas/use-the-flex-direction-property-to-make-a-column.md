## [Gunakan Properti arah-fleksibel untuk Membuat Kolom](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/use-the-flex-direction-property-to-make-a-column)

Dua tantangan terakhir menggunakan properti **flex-direction** diatur ke baris. Properti ini juga dapat membuat kolom dengan menumpuk secara vertikal anak-anak dari wadah fleksibel.

#### cosol:

```
Add the CSS property flex-direction to the #box-container element, and give it a value of column.

The #box-container element should have a flex-direction property set to column.
```

```css
<style>
  #box-container {
    display: flex;
    height: 500px;
    
  }
  #box-1 {
    background-color: dodgerblue;
    width: 50%;
    height: 50%;
  }

  #box-2 {
    background-color: orangered;
    width: 50%;
    height: 50%;
  }</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```

![](/assets/aas.jpg)

#### jasol:

```
<style>
  #box-container {
    display: flex;
    height: 500px;
    flex-direction: column;
  }
  #box-1 {
    background-color: dodgerblue;
    width: 50%;
    height: 50%;
  }

  #box-2 {
    background-color: orangered;
    width: 50%;
    height: 50%;
  }</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```

![](/assets/aswq.jpg)

