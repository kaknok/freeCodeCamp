## [Gunakan Gambar Retina untuk Resolusi Resolusi Tinggi](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-principles/use-a-retina-image-for-higher-resolution-displays)

Cara paling sederhana untuk membuat gambar Anda tampak "retina" \(dan mengoptimalkannya untuk tampilan retina\) adalah dengan menentukan nilai lebar dan tinggi mereka sebagai hanya setengah dari file asli.

Berikut ini contoh gambar yang hanya menggunakan setengah dari tinggi dan lebar asli:

```css
<style>
  img { height: 250px; width: 250px; }
</style>
<img src="coolPic500x500" alt="A most excellent picture">
```

#### cosol:

```
Set the width and height of the img tag to half of their original values. 
In this case, both the original height and the original width are 200px.

Your img tag should have a width of 100 pixels.
Your img tag should have a height of 100 pixels.
```

```css
<style>
  
</style>

<img src="https://s3.amazonaws.com/freecodecamp/FCCStickers-CamperBot200x200.jpg" 
alt="freeCodeCamp sticker that says 'Because CamperBot Cares'">
```



