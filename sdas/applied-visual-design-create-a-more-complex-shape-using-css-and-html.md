## Desain Visual Terapan: Buat Bentuk Lebih Kompleks Menggunakan CSS dan HTML

Salah satu bentuk paling populer di dunia adalah bentuk hati, dan dalam tantangan ini Anda akan membuatnya dengan menggunakan CSS murni. Tapi pertama-tama, Anda perlu memahami **: :before** and **: :after** pseudo-elements. Elemen-elemen pseudo ini digunakan untuk menambahkan sesuatu sebelum atau setelah elemen yang dipilih. Dalam contoh berikut, a **: :before** pseudo-element digunakan untuk menambahkan persegi panjang ke elemen dengan class hati:

```css
.heart::before {
  content: "";
  background-color: yellow;
  border-radius: 25%;
  position: absolute;
  height: 50px;
  width: 70px;
  top: -50px;
  left: 5px;
}
```

Untuk **: :before** and **: :after** pseudo-elements berfungsi dengan benar, mereka harus memiliki properti konten yang didefinisikan. Properti ini biasanya digunakan untuk menambahkan hal-hal seperti foto atau teks ke elemen yang dipilih. Ketika **: :before** and     **: :after** pseudo-elements digunakan untuk membuat bentuk, properti konten masih diperlukan, tetapi itu diatur ke string kosong.

Dalam contoh di atas, elemen dengan kelas hati memiliki **: :before** pseudo-elemen yang menghasilkan persegi panjang kuning dengan tinggi dan lebar 50px dan 70px, masing-masing. Persegi panjang ini memiliki sudut bulat karena radius batas 25% dan diposisikan benar-benar pada 5px dari kiri dan 50px di atas bagian atas elemen.

#### cosol:

```
Transform the element on the screen to a heart. 
In the heart ::after selector, change the background-color to pink and the border-radius to 50%.

Next, target the element with the class heart (just heart) and fill in the transform property. 
Use the rotate() function with -45 degrees. (rotate() works the same way that skewX() and skewY() do).

Finally, in the heart ::before selector, set its content property to an empty string.

The background-color property of the heart ::after selector should be pink.
The border-radius of the heart ::after selector should be 50%.
The transform property for the heart class should use a rotate() function set to -45 degrees.
The content of the heart ::before selector should be an empty string.
```

```css
<style>
.heart {
  position: absolute;
  margin: auto;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background-color: pink;
  height: 50px;
  top: 0px;
  left: 25px;
}
.heart::before {
  content: ;
  background-color: pink;
  border-radius: 50%;
  position: absolute;
  width: 50px;
  height: 50px;
  top: -25px;
  left: 0px;
}
</style>
<div class = "heart"></div>
```

![](/assets/hart.jpg)

#### jasol:

```css
<style>
.heart {
  position: absolute;
  margin: auto;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background-color: pink;
  height: 50px;
  width: 50px;
  transform: rotate(-45deg);
}
.heart::after {
  background-color: pink;
  content: "";
  border-radius: 50%;
  position: absolute;
  width: 50px;
  height: 50px;
  top: 0px;
  left: 25px;
}
.heart::before {
  content: "";
  background-color: pink;
  border-radius: 50%;
  position: absolute;
  width: 50px;
  height: 50px;
  top: -25px;
  left: 0px;
}
</style>
<div class = "heart"></div>
```

![](/assets/hartt.jpg)

