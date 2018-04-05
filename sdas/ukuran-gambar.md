CSS memiliki properti yang disebut `width` yang mengontrol lebar elemen. Sama seperti dengan font, kita akan menggunakan px \(piksel\) untuk menentukan lebar gambar.



Misalnya, jika kami ingin membuat kelas CSS yang disebut `larger-image` yang memberi elemen HTML lebar 500 pixel, kami akan menggunakan:

```css
<style>
  .larger-image {
    width: 500px;
  }
</style>
```

###### contoh soal

Buat kelas yang disebut `smaller-image` dan gunakan untuk mengubah ukuran gambar sehingga hanya selebar 100 piksel.

* elemen img make class `smaller-image`
* lebar gambarmu 100 pixel. browser zoom 100%

```css
link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
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
</style>

<h2 class="red-text">CatPhotoApp</h2>

<img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```



###### jawab:

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
  
  .smaller-image{
    width: 100px;

  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<img class="smaller-image" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```



