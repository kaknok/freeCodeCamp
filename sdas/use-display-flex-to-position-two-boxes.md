## [Gunakan display: flex to Position Two Boxes](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/use-display-flex-to-position-two-boxes)

Bagian ini menggunakan gaya tantangan bergantian untuk menunjukkan bagaimana menggunakan CSS untuk memosisikan elemen secara fleksibel. Pertama, tantangan akan menjelaskan teori, maka tantangan praktis menggunakan komponen tweet sederhana akan menerapkan konsep flexbox.

Menempatkan properti CSS **display: flex;** pada elemen memungkinkan Anda untuk menggunakan properti fleksibel lainnya untuk membangun halaman responsif.

#### cosol:

```
Add the CSS property display to #box-container and set its value to flex.
```

```css
<style>
  #box-container {
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

  }
</style>
<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```



