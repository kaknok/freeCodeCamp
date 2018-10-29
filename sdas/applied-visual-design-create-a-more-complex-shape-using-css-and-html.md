## Desain Visual Terapan: Buat Bentuk Lebih Kompleks Menggunakan CSS dan HTML

Salah satu bentuk paling populer di dunia adalah bentuk hati, dan dalam tantangan ini Anda akan membuatnya dengan menggunakan CSS murni. Tapi pertama-tama, Anda perlu memahami **: :before** and **: :after** pseudo-elements. Elemen-elemen pseudo ini digunakan untuk menambahkan sesuatu sebelum atau setelah elemen yang dipilih. Dalam contoh berikut, a **: :before** pseudo-element digunakan untuk menambahkan persegi panjang ke elemen dengan class hati:

```css
.heart::before {
  content: "";
  background-color: yellow;
  border-radius: 25%;
  position: absolute;
  height: 50px;
  width: 70px;
  top: -50px;
  left: 5px;
}
```

Untuk **: :before** and **: :after** pseudo-elements berfungsi dengan benar, mereka harus memiliki properti konten yang didefinisikan. Properti ini biasanya digunakan untuk menambahkan hal-hal seperti foto atau teks ke elemen yang dipilih. Ketika **: :before** and     **: :after** pseudo-elements digunakan untuk membuat bentuk, properti konten masih diperlukan, tetapi itu diatur ke string kosong.

Dalam contoh di atas, elemen dengan kelas hati memiliki **: :before** pseudo-elemen yang menghasilkan persegi panjang kuning dengan tinggi dan lebar 50px dan 70px, masing-masing. Persegi panjang ini memiliki sudut bulat karena radius batas 25% dan diposisikan benar-benar pada 5px dari kiri dan 50px di atas bagian atas elemen.

