## Desain Visual Terapan: Pelajari tentang Warna Komplementer

Teori warna dan dampaknya pada desain adalah topik yang mendalam dan hanya dasar-dasar yang tercakup dalam tantangan berikut. Di situs web, warna dapat menarik perhatian pada konten, membangkitkan emosi, atau menciptakan keharmonisan visual. Menggunakan kombinasi warna yang berbeda benar-benar dapat mengubah tampilan situs web, dan banyak pikiran dapat memilih palet warna yang berfungsi dengan konten Anda.

Roda warna adalah alat yang berguna untuk memvisualisasikan bagaimana warna saling berkaitan - ini adalah lingkaran di mana warna yang mirip adalah tetangga dan warna yang berbeda jauh terpisah. Ketika dua warna saling berhadapan di roda, mereka disebut warna pelengkap. Mereka memiliki karakteristik bahwa jika mereka digabungkan, mereka "membatalkan" satu sama lain dan menciptakan warna abu-abu. Namun, ketika ditempatkan berdampingan, warna-warna ini tampak lebih hidup dan menghasilkan kontras visual yang kuat.

Beberapa contoh warna pelengkap dengan kode hex mereka adalah:

```css
red (#FF0000) and cyan (#00FFFF)
green (#00FF00) and magenta (#FF00FF)
blue (#0000FF) and yellow (#FFFF00)
```

Ini berbeda dari model warna RYB usang yang banyak dari kita diajarkan di sekolah, yang memiliki warna dasar dan pelengkap yang berbeda. Teori warna modern menggunakan model RGB tambahan \(seperti pada layar komputer\) dan model CMY \(K\) subtraktif \(seperti dalam pencetakan\). Baca [di sini](https://en.wikipedia.org/wiki/Color_model) untuk informasi lebih lanjut tentang subjek yang rumit ini.

Ada banyak alat pemetik warna yang tersedia secara online yang memiliki opsi untuk menemukan pelengkap warna.

Catatan

Untuk semua tantangan warna: Menggunakan warna dapat menjadi cara ampuh untuk menambahkan minat visual ke suatu halaman. Namun, warna saja tidak boleh digunakan sebagai satu-satunya cara untuk menyampaikan informasi penting karena pengguna dengan gangguan penglihatan mungkin tidak memahami konten itu. Masalah ini akan dibahas lebih detail dalam tantangan Aksesibilitas Terapan.

#### cosol:

`Change thebackground-colorproperty of theblueandyellowclasses to their respective colors. Notice how the colors look different next to each other than they do compared against the white background.`

`Thedivelement with classblueshould have abackground-colorof blue.`

`Thedivelement with classyellowshould have abackground-colorof yellow.`

```css
<style>
  body {
    background-color: #FFFFFF;
  }
  .blue {
    background-color: #000000;
  }
  .yellow {
    background-color: #000000;
  }
  div {
    display: inline-block;
    height: 100px;
    width: 100px;
  }
</style>
<div class="blue"></div>
<div class="yellow"></div>
```

![](/assets/bl1.jpg)

#### jasol:

```css
<style>
  body {
    background-color: #FFFFFF;
  }
  .blue {
    background-color: #0000FF;
  }
  .yellow {
    background-color: #FFFF00;
  }
  div {
    display: inline-block;
    height: 100px;
    width: 100px;
  }
</style>
<div class="blue"></div>
<div class="yellow"></div>
```

![](/assets/bl2.jpg)

