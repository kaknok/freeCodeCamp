## [Mengurangi Pengulangan Menggunakan Fungsi Pengulangan](https://learn.freecodecamp.org/responsive-web-design/css-grid/reduce-repetition-using-the-repeat-function)

Ketika Anda menggunakan **grid-template-columns** dan **grid-template-rows** untuk menentukan struktur kisi, Anda memasukkan nilai untuk setiap baris atau kolom yang Anda buat.

Katakanlah Anda menginginkan kotak dengan 100 baris dengan tinggi yang sama. Sangat tidak praktis untuk memasukkan 100 nilai secara individual. Untungnya, ada cara yang lebih baik - dengan menggunakan fungsi **repeat** untuk menentukan berapa kali Anda ingin kolom atau baris Anda diulang, diikuti dengan koma dan nilai yang ingin Anda ulangi.

Berikut ini contoh yang akan membuat grid 100 baris, setiap baris dengan tinggi 50px.

```css
grid-template-rows: repeat (100, 50px);grid-template-rows: repeat(100, 50px);
```

Anda juga dapat mengulangi beberapa nilai dengan fungsi pengulangan, dan memasukkan fungsi di antara nilai-nilai lain ketika mendefinisikan struktur kisi. Inilah yang saya maksud:

```css
grid-template-columns: repeat(2, 1fr 50px) 20px;
```

Ini diterjemahkan menjadi:

```css
grid-template-columns: 1fr 50px 1fr 50px 20px;
```

Catatan

**1fr 50px** diulang dua kali diikuti oleh 20px.

