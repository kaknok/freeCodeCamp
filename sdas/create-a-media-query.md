## Buat Permintaan Media

Media Queries adalah teknik baru yang diperkenalkan di CSS3 yang mengubah penyajian konten berdasarkan ukuran viewport yang berbeda. Area pandang adalah area yang terlihat pengguna dari halaman web, dan berbeda tergantung pada perangkat yang digunakan untuk mengakses situs.

Media Queries terdiri dari jenis media, dan jika jenis media itu sesuai dengan jenis perangkat dokumen ditampilkan, gaya diterapkan. Anda dapat memiliki banyak pemilih dan gaya di dalam permintaan media Anda seperti yang Anda inginkan.

Berikut ini contoh query media yang mengembalikan konten ketika lebar perangkat kurang dari atau sama dengan 100 piksel:

```php
@media (max-width: 100px) {/ * Aturan CSS * /}
```

dan kueri media berikut mengembalikan konten ketika tinggi perangkat lebih dari atau sama dengan 350 piksel:

```php
@media (min-height: 350px) {/ * Aturan CSS * /}
```

Ingat, CSS di dalam kueri media hanya diterapkan jika jenis media cocok dengan perangkat yang digunakan.

#### cosol:

```
Add a media query, so that the p tag has a font-size of 10px when the device's height is less than 
or equal to 800px.

Your p element should have the font-size of 10px when the device height is less than or equal to 800px.
Declare a @media query for devices with a height less than or equal to 800px.
```

```css
<style>
  p {
    font-size: 20px;
  }

  /* Add media query below */

</style>

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus quis tempus massa. 
Aenean erat nisl, gravida vel vestibulum cursus, interdum sit amet lectus. Sed sit amet quam nibh. 
Suspendisse quis tincidunt nulla. In hac habitasse platea dictumst. Ut sit amet pretium nisl. 
Vivamus vel mi sem. Aenean sit amet consectetur sem. Suspendisse pretium, purus et gravida consequat, 
nunc ligula ultricies diam, at aliquet velit libero a dui.</p>
```

![](/assets/q.jpg)

#### jasol:

```css
<style>
  p {
    font-size: 10px;
    height: 800px;
  }

  /* Add media query below */
  @media (max-height: 800px) { /* CSS Rules */ }
</style>

<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus quis tempus massa. 
Aenean erat nisl, gravida vel vestibulum cursus, interdum sit amet lectus. Sed sit amet quam nibh. 
Suspendisse quis tincidunt nulla. In hac habitasse platea dictumst. Ut sit amet pretium nisl. 
Vivamus vel mi sem. Aenean sit amet consectetur sem. Suspendisse pretium, purus et gravida consequat, 
nunc ligula ultricies diam, at aliquet velit libero a dui.</p>
```

![](/assets/wq.jpg)

