## [Aksesibilitas Terapan: Meningkatkan Aksesibilitas Bagan dengan Elemen Gambar](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility/improve-chart-accessibility-with-the-figure-element)

HTML5 memperkenalkan elemen **figure**, bersama dengan **figcaption** terkait. Digunakan bersama, barang-barang ini membungkus representasi visual \(seperti gambar, diagram, atau bagan\) bersama dengan caption-nya. Ini memberikan peningkatan aksesibilitas dua kali lipat oleh konten yang terkait semantik pengelompokan, dan menyediakan alternatif teks yang menjelaskan **figure**.

Untuk visualisasi data seperti bagan, keterangan dapat digunakan untuk mencatat tren atau kesimpulan untuk pengguna dengan gangguan penglihatan secara singkat. Tantangan lain mencakup cara memindahkan versi tabel dari data grafik di luar layar \(menggunakan CSS\) untuk pengguna pembaca layar.

Berikut ini contoh - perhatikan bahwa **figcaption** masuk ke dalam tag **figure** dan dapat digabungkan dengan elemen lain:

```php
<figure>
  <img src="roundhouseDestruction.jpeg" alt="Photo of Camper Cat executing a roundhouse kick">
  <br>
  <figcaption>
    Master Camper Cat demonstrates proper form of a roundhouse kick.
  </figcaption>
</figure>
```



