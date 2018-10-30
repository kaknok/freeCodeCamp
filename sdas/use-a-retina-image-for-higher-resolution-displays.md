## [Gunakan Gambar Retina untuk Resolusi Resolusi Tinggi](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-principles/use-a-retina-image-for-higher-resolution-displays)

Cara paling sederhana untuk membuat gambar Anda tampak "retina" \(dan mengoptimalkannya untuk tampilan retina\) adalah dengan menentukan nilai lebar dan tinggi mereka sebagai hanya setengah dari file asli.



Berikut ini contoh gambar yang hanya menggunakan setengah dari tinggi dan lebar asli:

```css
<style>
  img { height: 250px; width: 250px; }
</style>
<img src="coolPic500x500" alt="A most excellent picture">
```



