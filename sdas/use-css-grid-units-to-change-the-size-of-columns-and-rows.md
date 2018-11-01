## [Gunakan unit Grid CSS untuk Mengubah Ukuran Kolom dan Baris](https://learn.freecodecamp.org/responsive-web-design/css-grid/use-css-grid-units-to-change-the-size-of-columns-and-rows)

Anda dapat menggunakan unit absolut dan relatif seperti px dan em di CSS Grid untuk menentukan ukuran baris dan kolom. Anda dapat menggunakan ini juga:



fr: menetapkan kolom atau baris ke sebagian kecil dari ruang yang tersedia,



otomatis: menetapkan kolom atau baris ke lebar atau tinggi kontennya secara otomatis,



%: menyesuaikan kolom atau baris ke lebar persen wadahnya.



Inilah kode yang menghasilkan output dalam pratinjau:



```css
grid-template-columns: auto 50px 10% 2fr 1fr;
```

Cuplikan ini membuat lima kolom. Kolom pertama seluas isinya, kolom kedua adalah 50px, kolom ketiga adalah 10% dari wadahnya, dan untuk dua kolom terakhir; ruang yang tersisa dibagi menjadi tiga bagian, dua dialokasikan untuk kolom keempat, dan satu untuk yang kelima.

