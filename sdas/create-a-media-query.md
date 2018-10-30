## Buat Permintaan Media

Media Queries adalah teknik baru yang diperkenalkan di CSS3 yang mengubah penyajian konten berdasarkan ukuran viewport yang berbeda. Area pandang adalah area yang terlihat pengguna dari halaman web, dan berbeda tergantung pada perangkat yang digunakan untuk mengakses situs.



Media Queries terdiri dari jenis media, dan jika jenis media itu sesuai dengan jenis perangkat dokumen ditampilkan, gaya diterapkan. Anda dapat memiliki banyak pemilih dan gaya di dalam permintaan media Anda seperti yang Anda inginkan.



Berikut ini contoh kueri media yang mengembalikan konten ketika lebar perangkat kurang dari atau sama dengan 100 piksel:

```php
@media (max-width: 100px) {/ * Aturan CSS * /}
```





dan kueri media berikut mengembalikan konten ketika tinggi perangkat lebih dari atau sama dengan 350 piksel:



```php
@media (min-height: 350px) {/ * Aturan CSS * /}
```



Ingat, CSS di dalam kueri media hanya diterapkan jika jenis media cocok dengan perangkat yang digunakan.



