## Desain Visual Terapan: Elemen Hidup dengan Harga Variabel

Ada berbagai cara untuk mengubah tingkat animasi dari elemen animasi yang serupa. Sejauh ini, ini telah dicapai dengan menerapkan properti **animation-iteration-count** dan pengaturan aturan **@keyframes**.

Untuk mengilustrasikan, animasi di sebelah kanan terdiri dari dua "stars" yang masing-masing penurunan ukuran dan opacity pada tanda 20% dalam aturan **@keyframes**, yang menciptakan animasi binar-binar. Anda dapat mengubah aturan **@keyframes** untuk salah satu elemen sehingga bintang bersinar dengan kecepatan yang berbeda.

#### cosol:

```
Alter the animation rate for the element with the class name of star-1 
by changing its @keyframes rule to 50%.

The @keyframes rule for the star-1 class should be 50%.
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
    animation-name: twinkle-1;
    animation-duration: 1s;
  }
    .star-2 {
    margin-top: 25%;
    margin-left: 25%;
    animation-name: twinkle-2;
    animation-duration: 1s;
  }

  @keyframes twinkle-1 {
    20% {
      transform: scale(0.5);
      opacity: 0.5;
    }
  }
  @keyframes twinkle-2 {
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
```

###### ![](/assets/tt.jpg)     dua titik ini berkelap kelip serempak \(bintang kelap-kelip\)

#### jasol:

```css
  @keyframes twinkle-1 {
    50% {
      transform: scale(0.5);
      opacity: 0.5;
    }
  }
```

###### ![](/assets/tt.jpg) dua titik ini berkelap kelip bergantian \(bintang kelap-kelip\)

#### 


