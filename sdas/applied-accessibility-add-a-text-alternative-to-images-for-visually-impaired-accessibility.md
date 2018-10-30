## [Aksesibilitas yang Diterapkan: Menambahkan Teks Alternatif untuk Gambar untuk Aksesibilitas Gangguan Penglihatan](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility/add-a-text-alternative-to-images-for-visually-impaired-accessibility)

Kemungkinan Anda pernah melihat atribut **alt** pada tag **img** dalam tantangan lain. Teks **Alt** mendeskripsikan isi gambar dan menyediakan alternatif teks. Ini membantu jika gambar gagal dimuat atau tidak dapat dilihat oleh pengguna. Ini juga digunakan oleh mesin pencari untuk memahami apa yang berisi gambar untuk memasukkannya dalam hasil pencarian. Inilah contohnya:

```php
<img src="importantLogo.jpeg" alt="Company logo">
```

Orang dengan gangguan penglihatan bergantung pada pembaca layar untuk mengubah konten web menjadi antarmuka audio. Mereka tidak akan mendapatkan informasi jika hanya disajikan secara visual. Untuk gambar, pembaca layar dapat mengakses atribut alt dan membaca isinya untuk menyampaikan informasi penting.

Teks **alt** yang bagus pendek tetapi deskriptif, dan dimaksudkan untuk secara singkat menyampaikan makna gambar. Anda harus selalu menyertakan atribut **alt** pada gambar Anda. Sesuai spesifikasi HTML5, ini sekarang dianggap wajib.

#### cosol:

```
Camper Cat happens to be both a coding ninja and an actual ninja, 
and is building a website to share his knowledge. 
The profile picture he wants to use shows his skills, and should be appreciated by all site visitors. 
Add an alt attribute in the img tag, that explains Camper Cat is doing karate. 
(The image src doesn't link to an actual file, so you should see the alt text in the display.)

Your img tag should have an alt attribute, and it should not be empty.
```

```php
<img src="doingKarateWow.jpeg">
```





