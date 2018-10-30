## [Aksesibilitas yang Diterapkan: Bungkus Konten dalam Elemen artikel](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility/wrap-content-in-the-article-element)

**article** adalah salah satu elemen HTML5 baru yang menambahkan makna semantik pada markup Anda. **article** adalah elemen sectioning, dan digunakan untuk membungkus konten independen, mandiri. Tag berfungsi dengan baik dengan entri blog, posting forum, atau artikel berita.

Menentukan apakah konten dapat berdiri sendiri biasanya merupakan penilaian panggilan, tetapi ada beberapa tes sederhana yang dapat Anda gunakan. Tanyakan pada diri sendiri apakah Anda menghapus semua konteks di sekitarnya, apakah konten tersebut masih masuk akal? Demikian pula untuk teks, apakah konten akan bertahan jika ada dalam umpan RSS?

Ingat bahwa orang-orang yang menggunakan teknologi bantu bergantung pada markup yang terencana dan semantik untuk lebih memahami pekerjaan Anda.

##### Catatan tentang bagian dan div

elemen **section** juga baru dengan HTML5, dan memiliki makna semantik yang sedikit berbeda dari **article**. **article** adalah untuk konten yang berdiri sendiri, dan **section** untuk mengelompokkan konten yang terkait tematik. Mereka dapat digunakan satu sama lain, sesuai kebutuhan. Misalnya, jika sebuah buku adalah **article**, maka setiap bab adalah **section**. Ketika tidak ada hubungan antara kelompok konten, lalu gunakan **div**.

```php
<div> - groups content
<section> - groups related content
<article> - groups independent, self-contained content
```



