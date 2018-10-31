## [Gunakan Properti Steno yang fleksibel](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/use-the-flex-shorthand-property)

Ada jalan pintas yang tersedia untuk mengatur beberapa properti yang fleksibel sekaligus. Sifat **flex-grow**, **flex-shrink**, dan **flex-basis** semuanya dapat disatukan dengan menggunakan properti **flex**.

Misalnya, **flex: 1 0 10px;** akan mengatur item ke **flex-grow: 1; **, **flex-shrink: 0; **, dan **flex-base: 10px; **.

Pengaturan properti default **flex: 0 1 auto;** .

#### cosol:

```
Add the CSS property flex to both #box-1 and #box-2. 
Give #box-1 the values so its flex-grow is 2, its flex-shrink is 2, and its flex-basis is 150px. 
Give #box-2 the values so its flex-grow is 1, its flex-shrink is 1, and its flex-basis is 150px.

These values will cause #box-1 to grow to fill the extra space at twice the rate of #box-2 when the container
 is greater than 300px and shrink at twice the rate of #box-2 when the container is less than 300px. 
300px is the combined size of the flex-basis values of the two boxes.

The #box-1 element should have the flex property set to a value of 2 2 150px.
The #box-2 element should have the flex property set to a value of 1 1 150px.
Your code should use the flex property for #box-1 and #box-2.
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
    flex: 2 2 150px;
    height: 200px;
  }
  #box-2 {
    background-color: orangered;
    flex: 1 1 150px;
    height: 200px;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```

![](/assets/olar.jpg)

