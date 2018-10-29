## Desain Visual Terapan: Buat Heartbeat CSS menggunakan Hitungan Animasi Tak Terbatas

Berikut ini adalah contoh animasi berkelanjutan lainnya dengan properti **animation-iteration-count** yang menggunakan hati yang Anda rancang dalam tantangan sebelumnya.

Animasi berdetak panjang satu detik terdiri dari dua potongan animasi. Unsur-unsur **heart** \(termasuk **:before** dan **:after** potongan\) dianimasikan untuk mengubah ukuran menggunakan properti transform, dan div background dianimasikan untuk mengubah warnanya menggunakan properti **background**.

#### cosol:

```
Keep the heart beating by adding the animation-iteration-count property 
for both the back class and the heart class and setting the value to infinite. 
The heart:before and heart:after selectors do not need any animation properties.

The animation-iteration-count property for the heart class should have a value of infinite.
The animation-iteration-count property for the back class should have a value of infinite.
```

```
<style>
  .back {
    position: fixed;
    padding: 0;
    margin: 0;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: white;
    animation-name: backdiv;
    animation-duration: 1s; 
    
  }
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
    animation-name: beat;
    animation-duration: 1s;
    
  }.heart:after {
    background-color: pink;
    content: "";
    border-radius: 50%;
    position: absolute;
    width: 50px;
    height: 50px;
    top: 0px;
    left: 25px;
  }
  .heart:before {
    background-color: pink;
    content: "";
    border-radius: 50%;
    position: absolute;
    width: 50px;
    height: 50px;
    top: -25px;
    left: 0px;
  }  
  @keyframes backdiv {
    50% {
      background: #ffe6f2;
    }
  }

  @keyframes beat {
    0% {
      transform: scale(1) rotate(-45deg);
    }
    50% {
      transform: scale(0.6) rotate(-45deg);
    }
  }

</style>
<div class="back"></div>
<div class="heart"></div>
```



