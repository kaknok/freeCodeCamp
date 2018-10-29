#### Desain Visual Terapan: Elemen Dorong Kiri atau Kanan dengan Properti mengambang

Alat pemosisian berikutnya tidak benar-benar menggunakan **position**, tetapi menetapkan properti **float** dari suatu elemen. Elemen mengambang dikeluarkan dari aliran normal dokumen dan didorong ke **left** atau **right** elemen induknya yang mengandung. Ini biasanya digunakan dengan properti **width** untuk menentukan berapa banyak ruang horizontal yang dibutuhkan elemen melayang.



cosol:

```
The given markup would work well as a two-column layout, 
with the section and aside elements next to each other. 
Give the #left item a float of left and the #right item a float of right.

The element with id left should have a float value of left.
The element with id right should have a float value of right.
```

```
<head>
  <style>
  #left {
    
    width: 50%;
  }
  #right {
    
    width: 40%;
  }
  aside, section {
    padding: 2px;
    background-color: #ccc;
  }
  </style>
</head>
<head>
  <style>
  #left {
    
    width: 50%;
  }
  #right {
    
    width: 40%;
  }
  aside, section {
    padding: 2px;
    background-color: #ccc;
  }
  </style>
</head>
```



