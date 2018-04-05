Sekarang, mari impor dan terapkan font Google \(perhatikan bahwa jika Google diblokir di negara Anda, Anda harus melewati tantangan ini\).



Pertama, Anda harus membuat panggilan ke Google untuk mengambil font Lobster dan memuatnya ke dalam HTML Anda.



Salin cuplikan kode berikut dan tempelkan ke bagian atas editor kode Anda:

```css
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
```

Sekarang Anda dapat mengatur Lobster sebagai nilai font-family pada elemen h2 Anda.

###### Contoh Soal:

Gunakan `font-family` Lobster ke h2

* import font Lobster
* h2 sudah diganti dengan font Lobster
* elemen p tetap make ffont Monospace

```html
<style>
  .red-text {
    color: red;
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

```html
<style>
  .red-text {
    color: red;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }
  
  h2 {
    font-family:Lobster;
  }
</style>


<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">


<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```



