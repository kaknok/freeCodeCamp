#### Desain Visual Terapan: Mengubah Posisi Relatif Elemen

CSS memperlakukan setiap elemen HTML sebagai kotaknya sendiri, yang biasanya disebut sebagai Box Model \(Model Kotak\) CSS. Item Block-level secara otomatis memulai pada baris baru \(pikirkan judul, paragraf, dan div\) sementara item inline tetap di dalam konten sekitarnya \(seperti gambar atau span\). Tata letak standar elemen dengan cara ini disebut aliran normal dokumen, tetapi CSS menawarkan properti posisi untuk mengesampingkannya.

Ketika posisi elemen diatur ke relatif, ini memungkinkan Anda untuk menentukan bagaimana CSS harus memindahkannya relatif terhadap posisinya saat ini dalam aliran normal halaman. Ini berpasangan dengan properti CSS offset kiri atau kanan, dan atas atau bawah. Ini mengatakan berapa banyak piksel, persentase, atau ems untuk memindahkan item dari tempat yang biasanya diposisikan. Contoh berikut memindahkan paragraf 10 piksel dari bawah:

```css
p {
  position: relative;
  bottom: 10px;
}
```

Mengubah posisi elemen menjadi relatif tidak menghapusnya dari aliran normal - elemen lain di sekitarnya tetap berperilaku seolah-olah item itu berada di posisi defaultnya.

Catatan:

Pemosisian memberi Anda banyak fleksibilitas dan kuasa atas tata letak visual halaman. Sangat bagus untuk diingat bahwa tidak masalah posisi elemen, markup HTML yang mendasarinya harus diatur dan masuk akal ketika dibaca dari atas ke bawah. Ini adalah bagaimana pengguna dengan gangguan penglihatan \(yang bergantung pada alat bantu seperti pembaca layar\) mengakses konten Anda.

