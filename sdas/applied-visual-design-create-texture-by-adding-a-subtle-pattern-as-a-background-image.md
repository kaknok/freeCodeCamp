## Desain Visual Terapan: Buat Tekstur dengan Menambahkan Pola Halus sebagai Gambar Latar Belakang

Salah satu cara untuk menambahkan tekstur dan minat ke latar belakang dan membuatnya lebih menonjol adalah dengan menambahkan pola halus. Kuncinya adalah keseimbangan, karena Anda tidak ingin latar belakang menonjol terlalu banyak, dan mengambil dari latar depan. Properti latar belakang mendukung fungsi **url \(\)** untuk menautkan ke gambar tekstur atau pola yang dipilih. Alamat tautan dibungkus dalam tanda kutip di dalam tanda kurung.

#### cosol:

```
Using the url of https://i.imgur.com/MJAkxbh.png, 
set the background of the whole page with the body selector.

Your body element should have a background property set to a url() with the given link.
```

#### jasol:

```css
<style>
  body {
    background: url(
      https://i.imgur.com/MJAkxbh.png
    );
  }
</style>
```



