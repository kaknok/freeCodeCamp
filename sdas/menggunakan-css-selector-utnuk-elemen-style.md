Dengan CSS, ada ratusan properties yang bisa kita gunakan untuk mengganti  tampilan halaman.

saat kau membuat _&lt;h2 style="color: red"&gt;CatPhotoApp&lt;/h2&gt;_, kau akan memberikan elemen _**h2**_ inline style \(`css diletakan didalam elemen HTML)`

ada satu cara untuk menambahkan style pada elemen tapi cara yang lebih baik menggunakan CSS, kepanjangan dari Cascading Style Sheet

CSS bisa diletakkan di bagian heading, contohnya:

> &lt;style&gt;
>
> &lt;/style&gt;

didalam elemen style, bisa dibuat `selector CSS` untuk semua elemen _**h2. **_ sebagai contoh, jika kita ingin semua elemen _**h2**_ menjadi merah, maka elemen style mu seharusnya begini:

> &lt;style&gt;
>
> h2 {color: red;}
>
> &lt;/style&gt;

untuk di ingat, bahwa menggunakan pembuka dan penutup `curly braces ( { dan } )`pada elemen style.    kau juga harus memastikan elemen style berada pada pembuka dan penutup tag style dan pastikan menambahkan semicolon `( ; )` pada tiap akhir elemen style.

###### Contoh Soal:

Hapuslah atribut style elemen _**h2**_ dan buatlah sebuah style CSS dan tambahkan CSS yang dibutuhkan utnuk merubah semua elemen _**h2 **_ menjadi biru

* hapus atribut style dari elemen _**h2**_
* buat elemen style
* elemen _**h2**_ menjadi biru
* pastikan deklarasi \_**h2 **\_sudah ada semicolon `;` dan closing brace `}`
* pastikan elemen style nya valid dan memiliki tag penutup

> &lt;h2 style="color: red"&gt;CatPhotoApp&lt;/h2&gt;
>
> &lt;p&gt;Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.&lt;/p&gt;



###### Jawab:

> h2 {
>
>     color:blue;
>
>   }
>
>   &lt;/style&gt;
>
>
>
> &lt;h2&gt;CatPhotoApp&lt;/h2&gt;
>
> &lt;p&gt;Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.&lt;/p&gt;



