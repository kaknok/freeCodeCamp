## [Gunakan area grid Tanpa Membuat Templat Area](https://learn.freecodecamp.org/responsive-web-design/css-grid/use-grid-area-without-creating-an-areas-template)

Properti **grid-area** yang Anda pelajari dalam tantangan terakhir dapat digunakan dengan cara lain. Jika grid Anda tidak memiliki templat bidang untuk referensi, Anda dapat membuat area dengan cepat agar suatu item ditempatkan seperti ini:

```css
item1 {area-grid: 1/1/2/4; }
```



Ini menggunakan nomor baris yang Anda pelajari sebelumnya untuk menentukan di mana area untuk item ini nantinya. Angka-angka dalam contoh di atas mewakili nilai-nilai ini:



```css
grid-area: horizontal line to start at / vertical line to start at / horizontal line to end at 
/ vertical line to end at;
```

Jadi item dalam contoh akan mengkonsumsi baris antara baris 1 dan 2, dan kolom antara garis 1 dan 4.

