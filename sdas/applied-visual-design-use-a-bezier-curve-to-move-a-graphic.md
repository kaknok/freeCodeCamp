## [Desain Visual Terapan: Gunakan Kurva Bezier untuk Memindahkan Grafis](https://learn.freecodecamp.org/responsive-web-design/applied-visual-design/use-a-bezier-curve-to-move-a-graphic)

Tantangan sebelumnya membahas kata kunci kemudahan-keluar yang menggambarkan perubahan animasi yang mempercepat pertama dan kemudian melambat pada akhir animasi. Di sebelah kanan, perbedaan antara kata kunci kemudahan-keluar \(untuk elemen biru\) dan kata kunci linear \(untuk elemen merah\) ditunjukkan. Kemajuan animasi yang mirip dengan kata kunci kemudahan-keluar dapat dicapai dengan menggunakan fungsi kurva Cubic Bezier khusus.



Secara umum, mengubah titik jangkar p1 dan p2 mendorong pembuatan kurva Bezier yang berbeda, yang mengontrol bagaimana animasi berlangsung sepanjang waktu. Berikut ini contoh kurva Bezier menggunakan nilai untuk meniru gaya kemudahan:

```css
animation-timing-function: cubic-bezier(0, 0, 0.58, 1);
```

Ingat bahwa semua fungsi kubik-bezier dimulai dengan p0 pada \(0, 0\) dan diakhiri dengan p3 pada \(1, 1\). Dalam contoh ini, kurva bergerak lebih cepat melalui sumbu Y \(dimulai pada 0, pergi ke nilai p1 y dari 0, kemudian pergi ke nilai p2 y dari 1\) daripada bergerak melalui sumbu X \(0 untuk memulai, lalu 0 untuk p1, hingga 0,58 untuk p2\). Akibatnya, perubahan dalam elemen animasi berlangsung lebih cepat daripada waktu animasi untuk segmen itu. Menjelang akhir kurva, hubungan antara perubahan nilai x dan y berbalik - nilai y bergerak dari 1 ke 1 \(tidak ada perubahan\), dan nilai x bergerak dari 0,58 ke 1, membuat perubahan animasi semakin lambat dibandingkan dengan durasi animasi.



