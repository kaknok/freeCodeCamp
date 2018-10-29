## Desain Visual Terapan: Sesuaikan Hue of a Color

Warna memiliki beberapa karakteristik termasuk warna, saturasi, dan ringan. CSS3 memperkenalkan properti **hsl \(\) **sebagai cara alternatif untuk memilih warna dengan langsung menyatakan karakteristik ini.



Hue adalah apa yang orang umumnya anggap sebagai 'warna'. Jika Anda menggambarkan spektrum warna yang dimulai dengan warna merah di sebelah kiri, bergerak melalui hijau di tengah, dan biru di kanan, rona adalah tempat warna cocok di sepanjang garis ini. Dalam **hsl \(\)**, hue menggunakan konsep roda warna sebagai ganti spektrum, di mana sudut warna pada lingkaran diberikan sebagai nilai antara 0 dan 360.



Saturasi adalah jumlah abu-abu dalam warna. Warna yang sepenuhnya jenuh tidak memiliki warna abu-abu di dalamnya, dan warna yang sedikit jenuh hampir sepenuhnya abu-abu. Ini diberikan sebagai persentase dengan 100% sepenuhnya jenuh.



Ringan adalah jumlah putih atau hitam dalam warna. Persentase diberikan mulai dari 0% \(hitam\) hingga 100% \(putih\), di mana 50% adalah warna normal.



Berikut ini beberapa contoh penggunaan **hsl \(\) **dengan warna-warna terang normal yang penuh saturasi:

| Color | HSL |
| :--- | :--- |
| red | hsl\(0, 100%, 50%\) |
| yellow | hsl\(60, 100%, 50%\) |
| green | hsl\(120, 100%, 50%\) |
| cyan | hsl\(180, 100%, 50%\) |
| blue | hsl\(240, 100%, 50%\) |
| magenta | hsl\(300, 100%, 50%\) |



#### cosol:

```
Change the background-color of each div element based on the class names (green, cyan, or blue) using hsl(). 
All three should have full saturation and normal lightness.

Your code should use the hsl() property to declare the color green.
Your code should use the hsl() property to declare the color cyan.
Your code should use the hsl() property to declare the color blue.
The div element with class green should have a background-color of green.
The div element with class cyan should have a background-color of cyan.
The div element with class blue should have a background-color of blue.
```

```css
<style>
  body {
    background-color: #FFFFFF;
  }
  
  .green {
    background-color: #000000;
  }
  
  .cyan {
    background-color: #000000;
  }
  
  .blue {
    background-color: #000000;
  }
  
  div {
    display: inline-block;
    height: 100px;
    width: 100px;
  }
</style>
  
<div class="green"></div>
<div class="cyan"></div>
<div class="blue"></div>
```

![](/assets/bll.jpg)



#### jasol:

```css
<style>
  body {
    background-color: #FFFFFF;
  }
  
  .green {
    background-color: hsl(120, 100%, 50%)
;
  }
  
  .cyan {
    background-color: hsl(180, 100%, 50%);
  }
  
  .blue {
    background-color: hsl(240, 100%, 50%);
  }
  
  div {
    display: inline-block;
    height: 100px;
    width: 100px;
  }
</style>
  
<div class="green"></div>
<div class="cyan"></div>
<div class="blue"></div>
```

![](/assets/bll1.jpg)



