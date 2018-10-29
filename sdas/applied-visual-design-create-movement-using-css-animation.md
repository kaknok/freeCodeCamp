## Desain Visual Terapan: Buat Gerakan Menggunakan Animasi CSS



Ketika elemen memiliki posisi tertentu, seperti **fixed** atau **relative**, properti CSS offset kanan, kiri, atas, dan bawah dapat digunakan dalam aturan animasi untuk membuat gerakan.



Seperti yang ditunjukkan pada contoh di bawah ini, Anda dapat mendorong item ke bawah kemudian ke atas dengan mengatur properti teratas keyframe 50% menjadi 50px, tetapi setelah itu diatur ke 0px untuk bingkai kunci pertama \(0%\) dan yang terakhir \(100%\).

```css
@keyframes rainbow {
  0% {
    background-color: blue;
    top: 0px;
  }
  50% {
    background-color: green;
    top: 50px;
  }
  100% {
    background-color: yellow;
    top: 0px;
  }
}
```



