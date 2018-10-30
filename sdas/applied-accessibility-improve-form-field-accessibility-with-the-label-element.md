## [Aksesibilitas yang Diterapkan: Tingkatkan Aksesibilitas Field Form dengan Elemen Label](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility/improve-form-field-accessibility-with-the-label-element "koala")

Meningkatkan aksesibilitas dengan markup HTML semantik berlaku untuk menggunakan kedua nama tag yang tepat serta atribut. Beberapa tantangan berikutnya mencakup beberapa skenario penting menggunakan atribut dalam bentuk.



Tag label membungkus teks untuk item kontrol bentuk tertentu, biasanya nama atau label untuk pilihan. Ikatan ini berarti bagi item dan membuat formulir lebih mudah dibaca. Atribut untuk label label secara eksplisit mengaitkan label itu dengan kontrol formulir dan digunakan oleh pembaca layar.



Anda belajar tentang tombol radio dan labelnya dalam pelajaran di bagian HTML Dasar. Dalam pelajaran itu, kami membungkuskan elemen input tombol radio di dalam elemen label bersama dengan teks label untuk membuat teks dapat diklik. Cara lain untuk mencapai ini adalah dengan menggunakan atribut for for sebagaimana dijelaskan dalam pelajaran ini.



Nilai atribut untuk harus sama dengan nilai atribut id dari kontrol form. Inilah contohnya:

```php
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
</form>
```





