## [**Aksesibilitas yang Diterapkan: Membuat Elemen Hanya Dapat Dilihat oleh Pembaca Layar dengan Menggunakan CSS Kustom**](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility/make-elements-only-visible-to-a-screen-reader-by-using-custom-css)

Pernahkah Anda memperhatikan bahwa semua tantangan aksesibilitas yang diterapkan sejauh ini belum menggunakan CSS? Ini untuk menunjukkan pentingnya garis besar dokumen logis, dan menggunakan tag semantik yang berarti di sekitar konten Anda sebelum memperkenalkan aspek desain visual.

Namun, keajaiban CSS juga dapat meningkatkan aksesibilitas pada halaman Anda ketika Anda ingin menyembunyikan konten secara visual yang hanya dimaksudkan untuk pembaca layar. Ini terjadi ketika informasi berada dalam format visual \(seperti bagan\), tetapi pengguna pembaca layar memerlukan presentasi alternatif \(seperti tabel\) untuk mengakses data. CSS digunakan untuk memposisikan elemen-elemen pembaca layar saja dari area visual jendela browser.

Berikut ini contoh aturan CSS yang mencapai ini:

```css
.sr-only {
  position: absolute;
  left: -10000px;
  width: 1px;
  height: 1px;
  top: auto;
  overflow: hidden;
}
```

Catatan

Pendekatan CSS berikut TIDAK akan melakukan hal yang sama:

* `display: none;`or`visibility: hidden;`hides content for everyone, including screen reader users
* Zero values for pixel sizes, such as`width: 0px; height: 0px;`removes that element from the flow of your document, meaning screen readers will ignore it



