## Desain Visual Terapan: Animate Multiple Elements di Variable Rates

Dalam tantangan sebelumnya, Anda mengubah kecepatan animasi untuk dua elemen animasi yang serupa dengan mengubah aturan **@keyframes** mereka. Anda dapat mencapai tujuan yang sama dengan memanipulasi **animation-duration** beberapa elemen.

Dalam animasi yang berjalan di editor kode, ada tiga "stars" di langit yang bersinar dengan kecepatan yang sama pada putaran terus menerus. Untuk membuatnya berkelap-kelip dengan laju yang berbeda, Anda dapat mengatur properti **animation-duration** ke nilai yang berbeda untuk setiap elemen.

#### cosol:

```
Set the animation-duration of the elements 
with the classes star-1, star-2, and star-3 to 1s, 0.9s, and 1.1s, respectively.

The animation-duration property for the star with class star-1 should remain at 1s.
The animation-duration property for the star with class star-2 should be 0.9s.
The animation-duration property for the star with class star-3 should be 1.1s.
```

```css
<style>
  .stars {
    background-color: white;
    height: 30px;
    width: 30px;
    border-radius: 50%;
    animation-iteration-count: infinite;
  }

  .star-1 {
    margin-top: 15%; 
    margin-left: 60%;
    animation-duration: 1s;
    animation-name: twinkle;
  }
    .star-2 {
    margin-top: 25%;
    margin-left: 25%;
    animation-duration: 1s;
    animation-name: twinkle;
  }

  .star-3 {
    margin-top: 10%;
    margin-left: 50%;
    animation-duration: 1s;
    animation-name: twinkle;
  }
  @keyframes twinkle {
    20% {
      transform: scale(0.5);
      opacity: 0.5;
    }
  }

  #back {
    position: fixed;
    padding: 0;
    margin: 0;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(black, #000099, #66c2ff, #ffcccc, #ffeee6);
  }
</style>
<div id="back"></div>
<div class="star-1 stars"></div>
<div class="star-2 stars"></div>
<div class="star-3 stars"></div>
```

###### ![](/assets/tt2.jpg) tiga bintang ini kelap kelip serempak

#### jasol:

```css
  .star-1 {
    margin-top: 15%; 
    margin-left: 60%;
    animation-duration: 1s;
    animation-name: twinkle;
  }
  .star-2 {
    margin-top: 25%;
    margin-left: 25%;
    animation-duration: 0.9s;
    animation-name: twinkle;
  }

  .star-3 {
    margin-top: 10%;
    margin-left: 50%;
    animation-duration: 1.1s;
    animation-name: twinkle;
  }
```

###### ![](/assets/tt2.jpg) tiga bintang ini berganti2 kelap kelip berdasarkan waktu dari animation-duration



