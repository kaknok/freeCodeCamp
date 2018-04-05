Sekali lagi, inilah diagram elemen untuk referensi Anda:

![](/assets/hviuZwe.png)

**Nesting berarti meletakkan satu elemen kedalam elemen yang lain**

contohnya:

```html
<p>Here's a <a href="https://freecodecamp.org"> link to Free Code Camp</a> for you to follow.</p>
```



###### soal:

Sekarang tempatkan elemen `a` yang ada dalam elemen p baru \(tepat setelah elemen h2 yang ada\) sehingga paragraf sekitarnya mengatakan "View more cat photos", tetapi hanya "cat photos" adalah tautan, dan teks sisanya adalah teks biasa.

* buatlah elemen `a` yang me-link-kan ke "http://www.freecatphotoapp.com".
* elemen `a` harus menggunakan teks anchor "cat photos:
* buat sebuah elemen `p` baru diseikitar elemen `a`
* elemen `a` harus harus di _nest_ dengan elemen `p`
* elemen `p` harus memiliki teks "View more " bukan "View more"
* pastikan elemen `p` dan `a` sudah ditutup

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

  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }

  .smaller-image {
    width: 100px;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<a href="http://www.freecatphotoapp.com">cat photos</a>

<img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

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

  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }

  .smaller-image {
    width: 100px;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p> View more cat photos
  <a href="http://www.freecatphotoapp.com">cat photos</a>
</p>



<img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>

```





