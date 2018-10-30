## [Buat Gambar Responsif](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-principles/make-an-image-responsive)

Membuat gambar yang responsif dengan CSS sebenarnya sangat sederhana. Alih-alih menerapkan lebar mutlak ke elemen:

```css
img { width: 720px; }
```

anda bisa menggunakan:

```css
img {
  max-width: 100%;
  display: block;
  height: auto;
}
```

Properti dengan **max-width** 100% menskala gambar agar sesuai dengan lebar wadahnya, tetapi gambar tidak akan membentang lebih lebar dari lebar aslinya. Mengatur properti **display** untuk memblokir perubahan gambar dari elemen inline \(default-nya\), ke elemen blok pada barisnya sendiri. Properti **height** otomatis menjaga rasio aspek asli gambar.

#### cosol:

```
Add style rules for the img tag to make it responsive to the size of its container. 
It should display as a block-level element, it should fit the full width of its container without stretching,
and it should keep its original aspect ratio.
 
Your img tag should have a max-width set to 100%.
Your img tag should have a display set to block.
Your img tag should have a height set to auto
```

```css
<style>
  
</style>

<img src="https://s3.amazonaws.com/freecodecamp/FCCStickerPack.jpg" alt="freeCodeCamp stickers set">
```

![](/assets/samp.jpg)

#### jasol:

```css
<style>
  img {
      display: block;
      max-width: 100%;
      height: auto;
  }
</style>

<img src="https://s3.amazonaws.com/freecodecamp/FCCStickerPack.jpg" alt="freeCodeCamp stickers set">
```

###### ![](/assets/samp.jpg)kayak ga ada yg beda



