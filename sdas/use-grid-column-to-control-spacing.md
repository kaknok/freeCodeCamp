## [Gunakan grid-kolom untuk Mengontrol Spasi](https://learn.freecodecamp.org/responsive-web-design/css-grid/use-grid-column-to-control-spacing)

Hingga saat ini, semua properti yang telah dibahas adalah untuk peti kemas. Properti grid-column adalah yang pertama untuk digunakan pada item grid itu sendiri.

Garis horizontal dan vertikal hipotetis yang menciptakan grid disebut sebagai garis. Garis-garis ini diberi nomor dimulai dengan 1 di sudut kiri atas grid dan bergerak ke kanan untuk kolom dan turun untuk baris, menghitung ke atas.

Ini adalah garis yang terlihat seperti grid 3x3:

![](/assets/000000.jpg)



Untuk mengontrol jumlah kolom yang akan digunakan suatu item, Anda dapat menggunakan properti kolom-grid bersama dengan nomor baris yang Anda inginkan untuk memulai dan berhenti.



Inilah contohnya:

```css
grid-column: 1 / 3;
```

Ini akan membuat item dimulai pada garis vertikal pertama dari grid di sebelah kiri dan menjangkau garis ke-3 dari grid, mengkonsumsi dua kolom.

