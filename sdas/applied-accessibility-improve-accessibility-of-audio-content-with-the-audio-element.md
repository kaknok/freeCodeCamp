## [Aksesibilitas yang Diterapkan: Meningkatkan Aksesibilitas Konten Audio dengan Elemen audio](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility/improve-accessibility-of-audio-content-with-the-audio-element)

Elemen audio HTML5 memberikan makna semantik ketika membungkus konten aliran suara atau audio dalam markup Anda. Konten audio juga membutuhkan alternatif teks agar dapat diakses oleh orang-orang yang tuli atau tuli. Ini dapat dilakukan dengan teks di dekatnya pada halaman atau tautan ke transkrip.



Tag audio mendukung atribut kontrol. Ini menunjukkan pemutaran default browser, jeda, dan kontrol lainnya, dan mendukung fungsionalitas keyboard. Ini adalah atribut boolean, yang berarti tidak membutuhkan nilai, kehadirannya pada tag mengaktifkan pengaturan.



Inilah contohnya:

```php
<audio id="meowClip" controls>
  <source src="audio/meow.mp3" type="audio/mpeg" />
  <source src="audio/meow.ogg" type="audio/ogg" />
</audio>
```

##### Catatan

_Konten multimedia biasanya memiliki komponen visual dan pendengaran. Diperlukan sinkronisasi keterangan dan transkrip sehingga pengguna dengan gangguan visual dan / atau pendengaran dapat mengaksesnya. Umumnya, pengembang web tidak bertanggung jawab membuat teks atau transkrip, tetapi perlu tahu untuk menyertakannya._

