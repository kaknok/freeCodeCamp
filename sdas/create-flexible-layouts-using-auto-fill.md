## [Buat Layout Fleksibel Menggunakan auto-fill](https://learn.freecodecamp.org/responsive-web-design/css-grid/create-flexible-layouts-using-auto-fill)

Fungsi pengulangan dilengkapi dengan opsi yang disebut pengisian otomatis. Ini memungkinkan Anda untuk secara otomatis memasukkan sebanyak mungkin baris atau kolom sesuai dengan ukuran yang Anda inginkan tergantung pada ukuran wadah. Anda dapat membuat tata letak yang fleksibel saat menggabungkan **auto-fill** dengan **minmax**.



Dalam pratinjau, **grid-template-columns** diatur ke

```css
repeat(auto-fill, minmax(60px, 1fr));
```

Saat penampung berubah ukuran, penyetelan ini terus menyisipkan kolom 60px dan meregangkannya hingga dapat memasukkan yang lain.



Catatan

Jika penampung Anda tidak dapat memuat semua barang Anda dalam satu baris, itu akan memindahkannya ke yang baru.

