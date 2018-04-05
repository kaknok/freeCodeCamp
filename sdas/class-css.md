Class adalah style yang dapat digunakan kembali yang dapat ditambahkan ke elemen HTML.

contoh: 

> &lt;style&gt;
>
>   .blue-text {
>
>     color: blue;
>
>   }
>
> &lt;/style&gt;

pada contoh diatas kita telah membuat sebuah Class yang bernama `blue-text` dengan `<style>` tag

kau bisa menerapkan sebuah Class untuk sebuah elemen HTML seperti ini:

> &lt;h2 class="blue-text"&gt;CatPhotoApp&lt;/h2&gt;

perhatikan pada elemen style CSS mu, Class harus dimulai dengan tanda titik `.` dan pada awal elemen HTML mu Class di deklarasikan tanpa tanda titik.

###### Contoh soal:

Didalam elemen style, gantilah  selector _**h2**_ menjadi `.red-text` dan update nilai dari color dari biru menjadi merah

berikan elemen _**h2 **_atribut_** **_Class dengan nilai `red-text`

* elemen _**h2**_ harus merah
* elemen _**h2**_ harus mempunyai Class `red-text`
* stylesheet mu harus deklarasikan class `red-text`dan color drubah jadi merah
* jangan gunakan inline style seperti `style="color: red"`

> &lt;style&gt;
>
>   h2 {
>
>     color: blue;
>
>   }
>
> &lt;/style&gt;
>
>
>
> &lt;h2&gt;CatPhotoApp&lt;/h2&gt;
>
>
>
> &lt;p&gt;Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.&lt;/p&gt;



###### Jawab:

> ###### &lt;style&gt;
>
> ######   h2 {
>
> ######     color: red;
>
> ######   }
>
> ######   
>
> ######   .red-text{
>
> ######     color:red;
>
> ######   }
>
> ######   
>
> ###### &lt;/style&gt;
>
> ###### 
>
> ###### &lt;h2 class="red-text"&gt;CatPhotoApp&lt;/h2&gt;
>
> ###### 
>
> ###### &lt;p&gt;Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.&lt;/p&gt;



