## Desain Visual Terapan: Buat Gradasi Linear Gradien Bertahap

Menerapkan warna pada elemen HTML tidak terbatas pada satu warna datar. CSS menyediakan kemampuan untuk menggunakan transisi warna, atau dikenal sebagai gradient, pada elemen. Ini diakses melalui fungsi **linear-gradient \(\)** di latar belakang properti. Berikut ini sintaks umum:



```
background: linear-gradient(gradient_direction, color 1, color 2, color 3, ...);
```



Argumen pertama menentukan arah dari mana transisi warna dimulai - itu dapat dinyatakan sebagai gelar, di mana 90 derajat membuat gradien vertikal dan 45 derajat miring seperti backslash. Argumen berikut menentukan urutan warna yang digunakan dalam gradien.

```
background: linear-gradient(90deg, red, yellow, rgb(204, 204, 255));
```

#### cosol:

```
Use a linear-gradient() for the div element's background, 
and set it from a direction of 35 degrees to change the color from #CCFFFF to #FFCCCC.

Note
While there are other ways to specify a color value, like rgb() or hsl(), use hex values for this challenge.

The div element should have a linear-gradient background with the specified direction and colors.
```

```css
  <style>

    div{ 
      border-radius: 20px;
      width: 70%;
      height: 400px;
      margin: 50px auto;
      
    }

  </style>

  <div></div>
```



#### jasol:

```css
<style>

    div{ 
      border-radius: 20px;
      width: 70%;
      height: 400px;
      margin: 50px auto;
      background: linear-gradient(35deg, #CCFFFF, #FFCCCC);
    }

</style>

<div></div>
```

![](/assets/as.jpg)

