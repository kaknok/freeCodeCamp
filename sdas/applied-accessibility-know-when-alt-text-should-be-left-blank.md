## [Aksesibilitas Terapan: Ketahui Kapan Teks Alt Harus Dibiarkan Kosong](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility/know-when-alt-text-should-be-left-blank)

Anda belajar bahwa memasukkan atribut **alt** pada img tag adalah wajib. Namun, terkadang gambar dikelompokkan dengan keterangan yang sudah menjelaskannya, atau hanya digunakan untuk hiasan saja. Dalam kasus ini, teks **alt** mungkin tampak berlebihan atau tidak perlu.

Dalam situasi ketika gambar sudah dijelaskan dengan konten teks, atau tidak menambahkan makna ke halaman, **img** masih membutuhkan atribut **alt**, tetapi dapat diatur ke string kosong. Inilah contohnya:

```php
<img src="visualDecoration.jpeg" alt="">
```

Gambar latar belakang biasanya termasuk dalam label 'dekoratif' juga. Namun, mereka biasanya diterapkan dengan aturan CSS, dan karena itu bukan bagian dari proses pembaca layar markup.

##### NOTE: _Untuk gambar dengan caption, Anda mungkin masih ingin memasukkan teks alt, karena ini membantu mesin telusur mengatalog konten gambar._



