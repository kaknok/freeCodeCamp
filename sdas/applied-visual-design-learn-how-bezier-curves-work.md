## Desain Visual Terapan: Pelajari Bagaimana Kurva Bezier Bekerja

Tantangan terakhir memperkenalkan properti **animation-timing-function** dan beberapa kata kunci yang mengubah kecepatan animasi selama durasinya. CSS menawarkan opsi selain kata kunci yang memberikan kontrol yang lebih baik terhadap bagaimana animasi dimainkan, melalui penggunaan kurva Bezier.

Dalam animasi CSS, kurva Bezier digunakan dengan fungsi **cubic-bezier**. Bentuk kurva menggambarkan bagaimana animasi dimainkan. Kurva hidup pada sistem koordinat 1 oleh 1. Sumbu X dari sistem koordinat ini adalah durasi animasi \(menganggapnya sebagai skala waktu\), dan sumbu Y adalah perubahan dalam animasi.

Fungsi **cubic-bezier** terdiri dari empat poin utama yang duduk di grid 1 oleh 1 ini: **p0, p1, p2**, dan **p3**. **p0** dan **p3** ditetapkan untuk Anda - mereka adalah titik awal dan akhir yang selalu terletak masing-masing pada titik asal \(0, 0\) dan \(1, 1\). Anda menetapkan nilai x dan y untuk dua titik lainnya, dan di mana Anda menempatkannya di grid mendikte bentuk kurva untuk animasi untuk mengikuti. Ini dilakukan dalam CSS dengan menyatakan nilai x dan y dari poin **p1** dan **p2** "anchor" dalam bentuk: **\(x1, y1, x2, y2\)**. Menarik semuanya, inilah contoh kurva Bezier dalam kode CSS:

```css
animation-timing-function: cubic-bezier(0.25, 0.25, 0.75, 0.75);
```




