Border CSS memiliki properti seperti `style`, `color`, dan `width`

Misalnya, jika kita ingin membuat merah, 5 piksel perbatasan di sekitar elemen HTML, kita bisa menggunakan kelas ini:

```css
<style>
  .thin-red-border {
    border-color: red;
    border-width: 5px;
    border-style: solid;
  }
</style>
```

###### contoh soal:

Buat class yang disebut `thick-green-border` yang menempatkan perbatasan hijau 10-piksel-lebar dengan style `solid` di sekitar elemen HTML, dan terapkan class itu ke foto kucing tadi.

Ingat bahwa Anda dapat menerapkan beberapa class ke elemen dengan memisahkan setiap class dengan spasi di dalam atribut class. Sebagai contoh:

```css
<img class="class1 class2">
```

* img make class`smaller-image`
* img make class `thick-green-border`
* image border width `10px`
* image border style `solid`
* border si sekitar `img` harus ijau

```css
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, Monospace;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }

  .smaller-image {
    width: 100px;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<img class="smaller-image" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```





###### jawab

```css
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, Monospace;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }

  .smaller-image {
    width: 100px;
  }
  
  .thick-green-border{
    border-width: 10px;
    border-style: solid;
    border-color: green;
</style>

<h2 class="red-text">CatPhotoApp</h2>

<img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```



