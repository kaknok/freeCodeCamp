elemen `a`. juga disebut dengan `anchor` digunakan untuk menautkan ke konten di luar halaman.

Berikut diagram elemen. Dalam hal ini, elemen digunakan di tengah elemen paragraf, yang berarti tautan akan muncul di tengah-tengah kalimat.

![](/assets/hviuZwe.png)



conthnya:

```html
<p>Here's a <a href="http://freecodecamp.org"> link to Free Code Camp</a> for you to follow.</p>
```



###### contoh soal:

buat sebuah elemen `a` dengan link ke `http://freecatphotoapp.com` dan `teks anchor` mya "cat photos"

* elemen `a` harus make `anchor text` "cat photos"
* dibutuhkan elemen `a` yang di link-kan ke `http://freecatphotoapp.com`
* pastikan elemen `a` sudah di tutup



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

<img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

<p class="red-text"> <a href="http://freecatphotoapp.com">cat photos</a> Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>

```



