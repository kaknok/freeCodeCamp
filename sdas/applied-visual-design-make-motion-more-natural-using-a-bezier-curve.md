## [Desain Visual Terapan: Membuat Gerak Lebih Alami Menggunakan Kurva Bezier](https://learn.freecodecamp.org/responsive-web-design/applied-visual-design/make-motion-more-natural-using-a-bezier-curve)

Tantangan ini menjiwai elemen untuk meniru gerakan bola yang disulap. Tantangan sebelumnya meliputi kurva Bezier kubik **linear** dan **ease-out**, namun tidak menggambarkan gerakan juggling secara akurat. Anda perlu menyesuaikan kurva Bezier untuk ini.

**animation-timing-function** secara otomatis berkelok-kelok pada setiap bingkai utama ketika **animation-iteration-count** diatur ke tak terbatas. Karena ada aturan mainframe yang ditetapkan di tengah durasi animasi \(pada 50%\), ini menghasilkan dua progresi animasi yang identik pada gerakan naik dan turun bola.

Kurva Bezier kubik berikut mensimulasikan gerakan juggling:

```css
cubic-bezier(0.3, 0.4, 0.5, 1.6);
```

_Perhatikan bahwa nilai y2 lebih besar dari 1. Meskipun kurva kubik Bezier dipetakan pada sistem koordinat 1 oleh 1, dan hanya dapat menerima nilai x dari 0 hingga 1, nilai y dapat diatur ke angka yang lebih besar dari satu. Ini menghasilkan gerakan memantul yang ideal untuk mensimulasikan bola juggling._



#### cosol:

```
Change value of the animation-timing-function of the element with the id of green to a cubic-bezier function 
with x1, y1, x2, y2 values set respectively to 0.311, 0.441, 0.444, 1.649.

The value of the animation-timing-function property for the element 
with the id green should be a cubic-bezier function with x1, y1, x2, y2 values as specified.
```

```css
<style>
  .balls {
    border-radius: 50%;
    position: fixed;  
    width: 50px;
    height: 50px;
    top: 60%;
    animation-name: jump;
    animation-duration: 2s;
    animation-iteration-count: infinite;
  }
  #red {
    background: red;
    left: 25%;
    animation-timing-function: linear;
  }
     #blue {
    background: blue;
    left: 50%;
    animation-timing-function: ease-out;
  }
  #green {
    background: green;
    left: 75%;
    animation-timing-function: cubic-bezier(0.69, 0.1, 1, 0.1);
  }
    @keyframes jump {
    50% {
      top: 10%;
    }
  }
</style>
<div class="balls" id="red"></div>
<div class="balls" id="blue"></div>
<div class="balls" id="green"></div>
```



