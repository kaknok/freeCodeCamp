Ada beberapa font default yang tersedia di semua browser. Ini termasuk Monospace, Serif dan Sans-Serif

Ketika satu font tidak tersedia, Anda dapat memberi tahu browser untuk "menurunkan" font lain.

Misalnya, jika Anda ingin elemen menggunakan font Helvetica, tetapi juga menurunkan font Sans-Serif ketika Helvetica tidak tersedia, Anda dapat menggunakan gaya CSS ini:

```css
p {
  font-family: Helvetica, Sans-Serif;
}
```



###### contoh soal:

Sekarang komentari panggilan Anda ke Google Fonts, sehingga font Lobster tidak tersedia. Perhatikan bagaimana hal itu menurun ke font Monospace.

* elemen h2 make font Lobster
* font h2 harus diganti dengan font Monospace apabila font Lobster tidak bisa dipakai
* bari comment pada link font google dengan memberikan `<!--` didepannya
* pastikan kau menutup comment dengan menambahlan `-->`

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
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```



###### jawab:

```css

<!--
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
-->


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

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```



