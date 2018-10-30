## [Desain Visual Terapan: Pelajari Bagaimana Kurva Bezier Bekerja](https://learn.freecodecamp.org/responsive-web-design/applied-visual-design/learn-how-bezier-curves-work)

Tantangan terakhir memperkenalkan properti **animation-timing-function** dan beberapa kata kunci yang mengubah kecepatan animasi selama durasinya. CSS menawarkan opsi selain kata kunci yang memberikan kontrol yang lebih baik terhadap bagaimana animasi dimainkan, melalui penggunaan kurva Bezier.

Dalam animasi CSS, kurva Bezier digunakan dengan fungsi **cubic-bezier**. Bentuk kurva menggambarkan bagaimana animasi dimainkan. Kurva hidup pada sistem koordinat 1 oleh 1. Sumbu X dari sistem koordinat ini adalah durasi animasi \(menganggapnya sebagai skala waktu\), dan sumbu Y adalah perubahan dalam animasi.

Fungsi **cubic-bezier** terdiri dari empat poin utama yang duduk di grid 1 oleh 1 ini: **p0, p1, p2**, dan **p3**. **p0** dan **p3** ditetapkan untuk Anda - mereka adalah titik awal dan akhir yang selalu terletak masing-masing pada titik asal \(0, 0\) dan \(1, 1\). Anda menetapkan nilai x dan y untuk dua titik lainnya, dan di mana Anda menempatkannya di grid mendikte bentuk kurva untuk animasi untuk mengikuti. Ini dilakukan dalam CSS dengan menyatakan nilai x dan y dari poin **p1** dan **p2** "anchor" dalam bentuk: **\(x1, y1, x2, y2\)**. Menarik semuanya, inilah contoh kurva Bezier dalam kode CSS:

```css
animation-timing-function: cubic-bezier(0.25, 0.25, 0.75, 0.75);
```

Dalam contoh di atas, nilai x dan y ekivalen untuk setiap titik \(x1 = 0,25 = y1 dan x2 = 0,75 = y2\), yang jika Anda ingat dari kelas geometri, menghasilkan garis yang memanjang dari titik asal ke titik \(1 , 1\). Animasi ini adalah perubahan linear elemen selama durasi animasi, dan sama dengan menggunakan kata kunci **linear**. Dengan kata lain, itu berubah dengan kecepatan konstan.

#### cosol:

```
For the element with the id of ball1, 
change the value of the animation-timing-function property from linear to its equivalent cubic-bezier function
value. Use the point values given in the example above.

The value of the animation-timing-function property for the element with the id ball1 should be the linear-equivalent cubic-bezier function.
The value of the animation-timing-function property for the element with the id ball2 should not change.
```

```css
<style>

  .balls{
    border-radius: 50%;
    background: linear-gradient(
      35deg,
      #ccffff,
      #ffcccc
    );
    position: fixed;  
    width: 50px;
    height: 50px;
    margin-top: 50px;
    animation-name: bounce;
    animation-duration: 2s;
    animation-iteration-count: infinite;
  }
  #ball1 { 
    left: 27%;
    animation-timing-function: linear;
  }
  #ball2 { 
    left: 56%;
    animation-timing-function: ease-out;
  }
  @keyframes bounce {
  0% {
    top: 0px;
  } 
  100% {
    top: 249px;
  }
} 

</style>

<div class="balls" id="ball1"></div>
<div class="balls" id="ball2"></div>
```



