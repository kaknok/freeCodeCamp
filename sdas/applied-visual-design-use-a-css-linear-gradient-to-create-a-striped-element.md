## Desain Visual Terapan: Gunakan CSS Linear Gradient untuk Membuat Elemen Striped

Fungsi **repeating-linear-gradient\(\)** sangat mirip dengan **linear-gradient \(\)** dengan perbedaan utama yang mengulangi pola gradien yang ditentukan. **repeating-linear-gradient\(\)** menerima berbagai nilai, tetapi untuk kesederhanaan, Anda akan bekerja dengan nilai sudut dan nilai warna berhenti dalam tantangan ini.

Nilai sudut adalah arah gradien. Berhenti warna seperti nilai lebar yang menandai tempat transisi berlangsung, dan diberikan dengan persentase atau sejumlah piksel.

Dalam contoh yang ditunjukkan di editor kode, gradien dimulai dengan warna kuning pada 0 piksel yang memadukan ke warna biru kedua pada 40 piksel dari awal. Karena pemberhentian warna berikutnya juga pada 40 piksel, gradien segera berubah ke warna hijau ketiga, yang dengan sendirinya memadukan ke dalam nilai warna keempat merah seperti yang 80 piksel dari awal gradien.

Untuk contoh ini, ada baiknya untuk berpikir tentang warna berhenti sebagai pasangan di mana setiap dua warna menyatu.

```
0px [yellow -- blend -- blue] 40px [green -- blend -- red] 80px
```

Jika setiap dua warna nilai berhenti adalah warna yang sama, pencampuran tidak terlihat karena warnanya di antara warna yang sama, diikuti dengan transisi yang keras ke warna berikutnya, sehingga Anda akan berakhir dengan garis.



#### cosol:

```
Make stripes by changing the repeating-linear-gradient() to use a gradient angle of 45deg, 
then set the first two color stops to yellow, and finally the second two color stops to black.

The angle of the repeating-linear-gradient() should be 45deg.
The angle of the repeating-linear-gradient() should no longer be 90deg
The color stop at 0 pixels should be yellow.
One color stop at 40 pixels should be yellow.
The second color stop at 40 pixels should be black.
The last color stop at 80 pixels should be black.
```

```css
<style>

  div{ 
    border-radius: 20px;
    width: 70%;
    height: 400px;
    margin:  50 auto;
    background: repeating-linear-gradient(
      90deg,
      yellow 0px,
      blue 40px,
      green 40px,
      red 80px
    );
  }

</style>

<div></div>
```

![](/assets/a.jpg)



#### jasol:

```css
<style>

  div{ 
    border-radius: 20px;
    width: 70%;
    height: 400px;
    margin:  50 auto;
    background: repeating-linear-gradient(
      45deg,
      yellow 0px,
      yellow 40px,
      black 40px,
      black 80px
    );
  }

</style>

<div></div>
```

![](/assets/aw.jpg)

