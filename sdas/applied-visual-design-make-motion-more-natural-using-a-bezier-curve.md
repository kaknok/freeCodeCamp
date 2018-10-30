## [Desain Visual Terapan: Membuat Gerak Lebih Alami Menggunakan Kurva Bezier](https://learn.freecodecamp.org/responsive-web-design/applied-visual-design/make-motion-more-natural-using-a-bezier-curve)

Tantangan ini menjiwai elemen untuk meniru gerakan bola yang disulap. Tantangan sebelumnya meliputi kurva Bezier kubik linear dan mudah-keluar, namun tidak menggambarkan gerakan juggling secara akurat. Anda perlu menyesuaikan kurva Bezier untuk ini.



Animasi-fungsi-waktu secara otomatis berkelok-kelok pada setiap bingkai utama ketika hitungan animasi-iterasi diatur ke tak terbatas. Karena ada aturan mainframe yang ditetapkan di tengah durasi animasi \(pada 50%\), ini menghasilkan dua progresi animasi yang identik pada gerakan naik dan turun bola.



Kurva Bezier kubik berikut mensimulasikan gerakan juggling:

```css
cubic-bezier(0.3, 0.4, 0.5, 1.6);
```





