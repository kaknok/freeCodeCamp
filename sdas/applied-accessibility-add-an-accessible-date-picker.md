## [Aksesibilitas yang Diterapkan: Tambahkan Pemilih Tanggal yang Dapat Diakses](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility/add-an-accessible-date-picker)

Formulir sering menyertakan bidang **input**, yang dapat digunakan untuk membuat beberapa kontrol bentuk yang berbeda. Atribut **type** pada elemen ini menunjukkan jenis masukan apa yang akan dibuat.



Anda mungkin telah memperhatikan **text** dan **submit** jenis masukan dalam tantangan sebelumnya, dan HTML5 memperkenalkan opsi untuk menentukan **date** field. Tergantung pada dukungan browser, pemilih tanggal muncul di bidang masukan saat fokus, yang membuat **input** formulir menjadi lebih mudah untuk semua pengguna.



Untuk peramban yang lebih lama, jenisnya akan menjadi default untuk **text**, sehingga membantu untuk menunjukkan kepada pengguna format tanggal yang diharapkan di label atau sebagai teks placeholder untuk berjaga-jaga.



Inilah contohnya:

```php
<label for="input1">Enter a date:</label>
<input type="date" id="input1" name="input1">
```



