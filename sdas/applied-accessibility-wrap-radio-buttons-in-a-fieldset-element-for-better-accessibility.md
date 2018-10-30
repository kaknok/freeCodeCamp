## [Aksesibilitas yang Diterapkan: Bungkus Tombol Radio dalam Elemen Fieldset untuk Aksesibilitas yang Lebih Baik](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility/wrap-radio-buttons-in-a-fieldset-element-for-better-accessibility)

Topik formulir selanjutnya mencakup aksesibilitas tombol radio. Setiap pilihan diberi **label** dengan atribut **for** yang mengikat **id** dari item yang sesuai sebagaimana tercakup dalam tantangan terakhir. Karena tombol radio sering datang dalam kelompok di mana pengguna harus memilih satu, ada cara untuk secara semantis menunjukkan pilihan adalah bagian dari satu set.

Tag **fieldset** mengelilingi seluruh pengelompokan tombol radio untuk mencapai ini. Sering menggunakan tag **legend** untuk memberikan deskripsi untuk pengelompokan, yang dibaca oleh pembaca layar untuk setiap pilihan dalam elemen **fieldset**.

Pembungkus **fieldset** dan tag **legend** tidak diperlukan ketika pilihannya sudah jelas, seperti pemilihan jenis kelamin. Menggunakan **label** dengan atribut **for** untuk setiap tombol radio sudah cukup.

Inilah contohnya:

```php
<form>
  <fieldset>
    <legend>Choose one of these three items:</legend>
    <input id="one" type="radio" name="items" value="one">
    <label for="one">Choice One</label><br>
    <input id="two" type="radio" name="items" value="two">
    <label for="two">Choice Two</label><br>
    <input id="three" type="radio" name="items" value="three">
    <label for="three">Choice Three</label>
  </fieldset>
</form>
```



