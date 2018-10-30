## [Desain Visual Terapan: Membuat Gerak Lebih Alami Menggunakan Kurva Bezier](https://learn.freecodecamp.org/responsive-web-design/applied-visual-design/make-motion-more-natural-using-a-bezier-curve)

Tantangan ini menjiwai elemen untuk meniru gerakan bola yang disulap. Tantangan sebelumnya meliputi kurva Bezier kubik **linear** dan **ease-out**, namun tidak menggambarkan gerakan juggling secara akurat. Anda perlu menyesuaikan kurva Bezier untuk ini.

**animation-timing-function** secara otomatis berkelok-kelok pada setiap bingkai utama ketika **animation-iteration-count** diatur ke tak terbatas. Karena ada aturan mainframe yang ditetapkan di tengah durasi animasi \(pada 50%\), ini menghasilkan dua progresi animasi yang identik pada gerakan naik dan turun bola.

Kurva Bezier kubik berikut mensimulasikan gerakan juggling:

```css
cubic-bezier(0.3, 0.4, 0.5, 1.6);
```

_Perhatikan bahwa nilai y2 lebih besar dari 1. Meskipun kurva kubik Bezier dipetakan pada sistem koordinat 1 oleh 1, dan hanya dapat menerima nilai x dari 0 hingga 1, nilai y dapat diatur ke angka yang lebih besar dari satu. Ini menghasilkan gerakan memantul yang ideal untuk mensimulasikan bola juggling._



