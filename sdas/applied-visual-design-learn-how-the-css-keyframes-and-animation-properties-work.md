## Desain Visual Terapan: Pelajari Bagaimana CSS @keyframes dan animasi Properties Work

Untuk menganimasikan suatu elemen, Anda perlu mengetahui tentang properti animasi dan aturan **@keyframes**. Properti animasi mengontrol bagaimana animasi harus berperilaku dan aturan **@keyframes** mengontrol apa yang terjadi selama animasi itu. Ada delapan properti animasi secara total. Tantangan ini akan membuatnya tetap sederhana dan mencakup dua hal terpenting terlebih dahulu:

**animation-name** menetapkan nama animasi, yang kemudian digunakan oleh **@keyframes** untuk memberitahu CSS yang aturannya pergi dengan animasi.

**animation-duration** mengatur lama waktu untuk animasi.

**@keyframes** adalah cara menentukan dengan tepat apa yang terjadi dalam animasi selama durasi tersebut. Ini dilakukan dengan memberikan properti CSS untuk "frame" tertentu selama animasi, dengan persentase mulai dari 0% hingga 100%. Jika Anda membandingkan ini dengan sebuah film, properti CSS untuk 0% adalah bagaimana elemen ditampilkan dalam adegan pembuka. Properti CSS untuk 100% adalah bagaimana elemen muncul di bagian akhir, tepat sebelum gulungan kredit. Kemudian CSS menerapkan sihir untuk mentransisikan elemen selama durasi yang diberikan untuk memerankan adegan. Berikut ini contoh untuk mengilustrasikan penggunaan **@keyframes** dan properti animasi:

```css
#anim {
  animation-name: colorful;
  animation-duration: 3s;
}
@keyframes colorful {
  0% {
    background-color: blue;
  }
  100% {
    background-color: yellow;
  }
}
```

Untuk elemen dengan id **anim**, cuplikan kode di atas menyetel **animation-name** menjadi **colorful** dan menyetel **animation-duration** menjadi 3 detik. Kemudian aturan **@keyframes** menautkan ke properti animasi dengan nama **colorful**. Ini menetapkan warna ke biru di awal animasi \(0%\) yang akan bertransisi menjadi kuning pada akhir animasi \(100%\). Anda tidak terbatas hanya pada transisi awal-akhir, Anda dapat mengatur properti untuk elemen untuk persentase antara 0% dan 100%.

#### cosol:

```
Create an animation for the element with the id rect, 
by setting the animation-name to rainbow and the animation-duration to 4 seconds. 
Next, declare a @keyframes rule, and set the background-color at the beginning of the animation (0%) to blue,
the middle of the animation (50%) to green, and the end of the animation (100%) to yellow.

The element with id of rect should have an animation-name property with a value of rainbow.
The element with id of rect should have an animation-duration property with a value of 4s.
The @keyframes rule should use the animation-name of rainbow.
The @keyframes rule for rainbow should use a background-color of blue at 0%.
The @keyframes rule for rainbow should use a background-color of green at 50%.
The @keyframes rule for rainbow should use a background-color of yellow at 100%.
```

```css
<style>
  div {
    height: 40px;
    width: 70%;
    background: black;
    margin: 50px auto;
    border-radius: 5px;
  }

  #rect {


  }




</style>
<div id="rect"></div>
```

                                                             ![](/assets/ab.jpg)

#### jasol:

```css
<style>
  div {
    height: 40px;
    width: 70%;
    background: black;
    margin: 50px auto;
    border-radius: 5px;
  }

  #rect {
    animation-name: rainbow;
    animation-duration: 4s;

    
  }
 
  @keyframes rainbow {
    0% {
      background-color: blue;
    }
    50%{
     background-color: green;  
    }
    100%{
      background-color: yellow;
    }
    
  }

</style>
<div id="rect"></div>
```





