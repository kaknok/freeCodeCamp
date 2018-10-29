## Desain Visual Terapan: Buat Grafik Menggunakan CSS

Dengan memanipulasi pemilih dan properti yang berbeda, Anda dapat membuat bentuk yang menarik. Salah satu yang lebih mudah untuk dicoba adalah bentuk bulan sabit. Untuk tantangan ini Anda perlu bekerja dengan properti **box-shadow** yang menetapkan bayangan elemen, bersama dengan properti **border-radius** yang mengontrol kebulatan sudut elemen.

Anda akan menciptakan objek bulat, transparan dengan bayangan tajam yang sedikit diimbangi ke samping - bayangan sebenarnya akan menjadi bentuk bulan yang Anda lihat.

Untuk membuat objek bulat, properti **border-radius** harus disetel ke nilai 50%.

Anda mungkin ingat dari tantangan sebelumnya bahwa properti **box-shadow** membutuhkan nilai untuk **offset-x,** **offset-y**, **blur-**radius, **spread-radius** dan nilai warna dalam urutan itu. Nilai-nilai **blur-radius** dan **spread-radius** adalah opsional.

#### cosol:

```
Manipulate the square element in the editor to create the moon shape. 
First, change the background-color to transparent, 
then set the border-radius property to 50% to make the circular shape. 
Finally, change the box-shadow property to set the offset-x to 25px, the offset-y to 10px, 
blur-radius to 0, spread-radius to 0, and color to blue.

The value of the background-color property should be set to transparent.
The value of the border-radius property should be set to 50%.
The value of the box-shadow property should be set to 25px for offset-x, 
    10px for offset-y, 0 for blur-radius, 0 for spread-radius, and finally blue for the color.
```

```css
<style>
.center
{
  position: absolute;
  margin: auto;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  width: 100px;
  height: 100px;

  background-color: blue;
  border-radius: 0px;
  box-shadow: 25px 10px 10px 10px green; 
}

</style>
<div class="center"></div>
```

![](/assets/aaw.jpg)

#### jasol:

```

```



