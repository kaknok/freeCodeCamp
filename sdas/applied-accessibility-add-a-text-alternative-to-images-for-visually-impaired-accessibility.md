## [Aksesibilitas yang Diterapkan: Menambahkan Teks Alternatif untuk Gambar untuk Aksesibilitas Gangguan Penglihatan](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility/add-a-text-alternative-to-images-for-visually-impaired-accessibility)

Kemungkinan Anda pernah melihat atribut **alt** pada tag **img** dalam tantangan lain. Teks **Alt** mendeskripsikan isi gambar dan menyediakan alternatif teks. Ini membantu jika gambar gagal dimuat atau tidak dapat dilihat oleh pengguna. Ini juga digunakan oleh mesin pencari untuk memahami apa yang berisi gambar untuk memasukkannya dalam hasil pencarian. Inilah contohnya:

```css
<img src="importantLogo.jpeg" alt="Company logo">
```

Orang dengan gangguan penglihatan bergantung pada pembaca layar untuk mengubah konten web menjadi antarmuka audio. Mereka tidak akan mendapatkan informasi jika hanya disajikan secara visual. Untuk gambar, pembaca layar dapat mengakses atribut alt dan membaca isinya untuk menyampaikan informasi penting.



Teks **alt** yang bagus pendek tetapi deskriptif, dan dimaksudkan untuk secara singkat menyampaikan makna gambar. Anda harus selalu menyertakan atribut **alt** pada gambar Anda. Sesuai spesifikasi HTML5, ini sekarang dianggap wajib.

