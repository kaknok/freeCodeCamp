#### Desain Visual Terapan: Mengunci Elemen ke Induknya dengan Pemosisian Mutlak

Pilihan berikutnya untuk properti posisi CSS adalah mutlak, yang mengunci elemen di tempat relatif terhadap penampung induknya. Tidak seperti posisi relatif, ini menghilangkan elemen dari aliran normal dokumen, sehingga item di sekitarnya mengabaikannya. Properti CSS offset \(atas atau bawah dan kiri atau kanan\) digunakan untuk mengatur posisi.



Satu nuansa dengan posisi absolut adalah bahwa ia akan dikunci relatif terhadap leluhur terdekatnya. Jika Anda lupa menambahkan aturan posisi ke item induk, \(ini biasanya dilakukan menggunakan posisi: relatif;\), browser akan terus mencari rantai dan akhirnya default ke tag body.



