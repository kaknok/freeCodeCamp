## [Gunakan Properti yang sejajar](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/use-the-align-self-property)

Properti akhir untuk item flex adalah **align-self**. Properti ini memungkinkan Anda menyesuaikan keselarasan masing-masing item secara individual, alih-alih mengatur semuanya sekaligus. Ini berguna karena teknik penyesuaian umum lainnya menggunakan properti CSS **float**, **clear**, dan **vertical-align** tidak berfungsi pada item flex.



**align-self** menerima nilai yang sama dengan **align-items** dan akan mengesampingkan nilai apa pun yang ditetapkan oleh properti **align-items**.

#### cosol:

```
Add the CSS property align-self to both #box-1 and #box-2. 
Give #box-1 a value of center and give #box-2 a value of flex-end.

The #box-1 element should have the align-self property set to a value of center.
The #box-2 element should have the align-self property set to a value of flex-end.
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

```css
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  #box-1 {
    background-color: dodgerblue;
    align-self: center;
    height: 200px;
    width: 200px;
  }
  #box-2 {
    background-color: orangered;
    align-self: flex-end;
    height: 200px;
    width: 200px;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```

![](/assets/wwaaff.jpg)

