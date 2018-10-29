## Desain Visual Terapan: Gunakan Animasi CSS untuk Merubah Status Hover dari Sebuah Tombol

You can use CSS`@keyframes`to change the color of a button in its hover state.

Here's an example of changing the width of an image on hover:



Anda bisa menggunakan CSS **@keyframes **untuk mengganti warna sebuah **button **pada saat di hover.

berukut adalah contoh dari mengganti width gambar saat di hover:

```css
<style>
  img:hover {
    animation-name: width;
    animation-duration: 500ms;
  }

  @keyframes width {
    100% {
      width: 40px;
    }
  }
</style>

<img src="https://bit.ly/smallgooglelogo" alt="Google's Logo" />
```



