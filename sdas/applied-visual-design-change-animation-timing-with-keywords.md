## Desain Visual Terapan: Ubah Waktu Animasi dengan Kata Kunci

Dalam animasi CSS, properti **animation-timing-function** mengontrol seberapa cepat elemen animasi berubah selama durasi animasi. Jika animasi adalah mobil yang bergerak dari titik A ke titik B dalam waktu tertentu \(**animation-duration** Anda\), **animation-timing-function** mengatakan bagaimana mobil mempercepat dan mengurangi kecepatan selama perjalanan.

Ada sejumlah kata kunci standar yang tersedia untuk opsi populer. Misalnya, 

* nilai default adalah **ease**, yang mulai lambat, mempercepat di tengah, dan kemudian melambat lagi pada akhirnya. 
* Pilihan lain termasuk **ease-out**, yang cepat di awal kemudian melambat, 
* **ease-in**, yang lambat di awal, kemudian mempercepat di akhir, 
* atau **linear**, yang menerapkan kecepatan animasi konstan di seluruh.

#### cosol:

```
For the elements with id of ball1 and ball2, add an animation-timing-function property to each, 
and set #ball1 to linear, and #ball2 to ease-out. 
Notice the difference between how the elements move during the animation but end together, 
since they share the same animation-duration of 2 seconds.

The value of the animation-timing-function property for the element with the id ball1 should be linear.
The value of the animation-timing-function property for the element with the id ball2 should be ease-out.
```

```css
<style>

  .balls {
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
    left:27%;
    }
  #ball2 { 
    left:56%;

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

###### ![](/assets/bu/.jpg) dua bulatan ini bergerak seperti bola jatuh serempak dan terus berulang

#### jasol:

```css
  #ball1 { 
    left:27%;
    animation-timing-function: linear;
  }
  #ball2 { 
    left:56%;
    animation-timing-function: ease-out;
  }
```

###### ![](/assets/bu.jpg) dua bulatan ini akan jatuh tidak serempak



