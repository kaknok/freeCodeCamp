## [Aksesibilitas yang Diterapkan: Gunakan tabindex untuk Menentukan Urutan Keyboard Fokus untuk Beberapa Elemen](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility/use-tabindex-to-specify-the-order-of-keyboard-focus-for-several-elements)

Atribut tabindex juga menentukan urutan tab yang tepat dari elemen. Ini dicapai ketika nilai atribut diatur ke angka positif 1 atau lebih tinggi.



Mengatur tabindex = "1" akan membawa fokus keyboard ke elemen tersebut terlebih dahulu. Kemudian siklus melalui urutan nilai tabindex yang ditentukan \(2, 3, dll\), sebelum pindah ke default dan tabindex = "0" item.



Penting untuk dicatat bahwa ketika urutan tab diatur dengan cara ini, itu menimpa urutan default \(yang menggunakan sumber HTML\). Ini dapat membingungkan pengguna yang mengharapkan untuk memulai navigasi dari bagian atas halaman. Teknik ini mungkin diperlukan dalam beberapa keadaan, tetapi dalam hal aksesibilitas, berhati-hatilah sebelum menerapkannya.



Inilah contohnya:

```php
<div tabindex="1">I get keyboard focus, and I get it first!</div>
```

```php
<div tabindex="2">I get keyboard focus, and I get it second!</div>
```



