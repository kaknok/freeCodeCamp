## [Align Elements Menggunakan Properti justify-content](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/align-elements-using-the-justify-content-property)

Kadang-kadang barang-barang flex dalam wadah fleksibel tidak mengisi semua ruang dalam wadah. Adalah umum untuk ingin memberi tahu CSS cara menyelaraskan dan melonggarkan item flex dengan cara tertentu. Untungnya, properti **justify-content** memiliki beberapa opsi untuk melakukan ini. Tetapi pertama, ada beberapa terminologi penting yang harus dipahami sebelum meninjau opsi-opsi itu.

[Di sini adalah gambar yang berguna menunjukkan deretan untuk menggambarkan konsep di bawah ini.](https://www.w3.org/TR/css-flexbox-1/images/flex-direction-terms.svg)

![](/assets/mess.jpg)

Ingat bahwa pengaturan wadah fleksibel sebagai baris menempatkan item fleksibel bersebelahan dari kiri ke kanan. Wadah fleksibel yang disetel sebagai kolom menempatkan item lentur dalam tumpukan vertikal dari atas ke bawah. Untuk masing-masing, arah item flex diatur disebut sumbu utama. Untuk sebuah baris, ini adalah garis horizontal yang memotong setiap item. Dan untuk kolom, sumbu utama adalah garis vertikal melalui item.

Ada beberapa opsi untuk bagaimana meluruskan benda-benda flex di sepanjang garis yang merupakan poros utama. Salah satu yang paling umum digunakan adalah **justify-content: center; **, yang meluruskan semua item flex ke pusat di dalam wadah fleksibel. Pilihan lain termasuk:

* **flex-start**: meratakan item ke awal dari wadah fleksibel. Untuk berturut-turut, ini mendorong item ke sebelah kiri wadah. Untuk kolom, ini mendorong item ke bagian atas penampung.
* **flex-end**: meluruskan item ke ujung wadah flex. Untuk berturut-turut, ini mendorong barang di sebelah kanan wadah. Untuk kolom, ini mendorong item ke bagian bawah penampung.
* **space-between**: menyelaraskan item ke pusat sumbu utama, dengan ruang ekstra ditempatkan di antara item. Item pertama dan terakhir didorong ke bagian paling ujung dari wadah fleksibel. Sebagai contoh, berturut-turut barang pertama berada di sisi kiri wadah, item terakhir berada di sisi kanan wadah, lalu item lain di antara keduanya diberi jarak secara merata.
* **space-around**: mirip dengan **space-between** tetapi item pertama dan terakhir tidak terkunci ke tepi wadah, ruang didistribusikan di sekitar semua item

#### cosol:

```
An example helps show this property in action. Add the CSS property justify-content to the #box-container 
element, and give it a value of center.

Bonus
Try the other options for the justify-content property in the code editor to see their differences. 
But note that a value of center is the only one that will pass this challenge.
(Coba opsi lain untuk konten yang membenarkan untuk melihat perbedaannya. 
Tetapi perhatikan bahwa nilai pusat hanya satu yang akan melewati tantangan ini.)

The #box-container element should have a justify-content property set to a value of center.
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
    width: 25%;
    height: 100%;
  }
  #box-2 {
    background-color: orangered;
    width: 25%;
    height: 100%;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```

![](/assets/uka.jpg)

#### jasol:

```css
<style>
  #box-container {
    background: gray;
    display: flex;
    height: 500px;
    justify-content: center; /* ini yg ditambahkan */
  }
  #box-1 {
    background-color: dodgerblue;
    width: 25%;
    height: 100%;
  }
  #box-2 {
    background-color: orangered;
    width: 25%;
    height: 100%;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```

![](/assets/akko.jpg)

