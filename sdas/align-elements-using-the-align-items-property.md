## [Align Elements Menggunakan Properti align-items](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/align-elements-using-the-align-items-property)

Properti **align-items** mirip dengan **justify-content**. Ingat bahwa properti **justify-content** menyejajarkan item flex di sepanjang sumbu utama. Untuk baris, sumbu utama adalah garis horizontal dan untuk kolom adalah garis vertikal.

Wadah fleksibel juga memiliki sumbu silang yang merupakan kebalikan dari sumbu utama. Untuk baris, sumbu silang adalah vertikal dan untuk kolom, sumbu silang adalah horisontal.

CSS menawarkan properti **align-items** untuk menyelaraskan item flex sepanjang sumbu silang. Untuk berturut-turut, ia memberi tahu CSS cara mendorong item di seluruh baris ke atas atau ke bawah dalam penampung. Dan untuk kolom, cara mendorong semua barang ke kiri atau ke kanan di dalam wadah.

Nilai-nilai yang berbeda tersedia untuk menyelaraskan item termasuk:

* **flex-start**: meratakan item ke awal dari wadah fleksibel. Untuk baris, ini meratakan item ke bagian atas penampung. Untuk kolom, ini meluruskan item di sebelah kiri wadah.
* **flex-end**: meluruskan item ke ujung wadah flex. Untuk baris, ini meratakan item ke bagian bawah penampung. Untuk kolom, ini meratakan item di sebelah kanan penampung.
* **center**: menyelaraskan item ke pusat. Untuk baris, ini secara vertikal menyelaraskan item \(ruang yang sama di atas dan di bawah item\). Untuk kolom, ini secara horizontal meluruskannya \(ruang yang sama ke kiri dan kanan item\).
* **stretch**: regangkan barang untuk mengisi wadah fleksibel. Misalnya, baris item direntangkan untuk mengisi wadah fleksibel dari atas ke bawah.
* **baseline**: menyelaraskan item ke baseline mereka. Baseline adalah konsep teks, anggap saja sebagai garis yang digunakan huruf-huruf.

#### cosol:

```
An example helps show this property in action. Add the CSS property align-items to the #box-container element
and give it a value of center.

Bonus
Try the other options for the align-items property in the code editor to see their differences. 
But note that a value of center is the only one that will pass this challenge.

The #box-container element should have an align-items property set to a value of center.
```

```css
<style>
  #box-container {
    background: gray;
    display: flex;
    height: 500px;
    
  }
  #box-1 {
    background-color: dodgerblue;
    width: 200px;
    font-size: 24px;
  }
  #box-2 {
    background-color: orangered;
    width: 200px;
    font-size: 18px;
  }
</style>
<div id="box-container">
  <div id="box-1"><p>Hello</p></div>
  <div id="box-2"><p>Goodbye</p></div>
</div>
```

![](/assets/moto.jpg)

#### jasol:

```css
<style>
  #box-container {
    background: gray;
    display: flex;
    height: 500px;
    align-items: center; /* yang ini dirubah*/
  }
  #box-1 {
    background-color: dodgerblue;
    width: 200px;
    font-size: 24px;
  }
  #box-2 {
    background-color: orangered;
    width: 200px;
    font-size: 18px;
  }
</style>
<div id="box-container">
  <div id="box-1"><p>Hello</p></div>
  <div id="box-2"><p>Goodbye</p></div>
</div>
```

###### ![](/assets/baseline.jpg) baseline \(ga nyentuh semua \(goodbye\)\)

###### ![](/assets/flex-end.jpg) flex-end

###### ![](/assets/flex-start.jpg)flex-start \(nyentuh ke atas semua\)

###### ![](/assets/center.jpg) center



