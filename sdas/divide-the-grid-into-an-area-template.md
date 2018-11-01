## [Bagilah Grid ke dalam Templat Area](https://learn.freecodecamp.org/responsive-web-design/css-grid/divide-the-grid-into-an-area-template)

Anda dapat mengelompokkan sel-sel grid Anda ke suatu area dan memberi nama khusus pada area tersebut. Lakukan ini dengan menggunakan **grid-template-areas** pada wadah seperti ini:

```css
grid-template-areas:
  "header header header"
  "advert content content"
  "footer footer footer";
```

Kode di atas menggabungkan tiga sel teratas menjadi sebuah area adalah **header**, tiga sel bawah menjadi area **footer**, dan yang membuat dua area di baris tengah; **advert** dan **content**.

Catatan

Setiap kata dalam kode mewakili sel dan setiap pasangan tanda kutip mewakili satu baris.

Selain label khusus, Anda dapat menggunakan periode \(.\) Untuk menetapkan sel kosong di grid.

