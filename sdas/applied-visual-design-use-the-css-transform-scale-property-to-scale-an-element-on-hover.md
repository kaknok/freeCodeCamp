## Desain Visual Terapan: Gunakan CSS Transform scale Property to Scale an Element on Hover

Properti **transform** memiliki berbagai fungsi yang memungkinkan Anda mengukur, memindahkan, memutar, miring, dll., Elemen Anda. Ketika digunakan dengan pseudo-class seperti **:hover** yang menentukan status suatu elemen tertentu, properti **transform** dapat dengan mudah menambah interaktivitas ke elemen Anda.



Berikut ini contoh untuk menskalakan elemen paragraf ke 2,1 kali ukuran aslinya ketika pengguna mengarahkannya ke atasnya:

```css
p:hover {
  transform: scale(2.1);
}
```

#### cosol:

```
Add a CSS rule for the hover state of the div 
and use the transform property to scale the div element to 1.1 times its original size 
when a user hovers over it.

The size of the div element should scale 1.1 times when the user hovers over it.
```

```css
<style>
  div { 
    width: 70%;
    height: 100px;
    margin:  50px auto;
    background: linear-gradient(
      53deg,
      #ccfffc,
      #ffcccf
    );
  }
  
  
  
</style>

<div></div>
```



