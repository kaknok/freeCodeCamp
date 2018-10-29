## Desain Visual Terapan: Modifikasi Mode Isi dari Animasi



Perhatikan bagaimana animasi me-reset setelah 500ms berlalu, menyebabkan tombol untuk kembali ke warna asli. Anda ingin tombol tetap berwarna \(highlighted\).



Ini dapat dilakukan dengan menyetel properti **animation-fill-mode** ke **forwards**. **animation-fill-mode** menentukan gaya yang diterapkan ke elemen ketika animasi telah selesai. Anda dapat mengaturnya seperti ini:

```css
animation-fill-mode: forwards;
```



