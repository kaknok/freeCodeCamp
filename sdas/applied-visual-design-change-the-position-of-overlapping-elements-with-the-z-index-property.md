## Desain Visual Terapan: Ubah Posisi Elemen yang Tumpang Tindih dengan Properti z-index

Ketika elemen diposisikan overlap / tumpang tindih, elemen yang datang kemudian / terkahir di markup HTML akan, secara default, muncul di bagian atas elemen lainnya. Namun, properti z-index dapat menentukan urutan bagaimana elemen stacked / ditumpuk di atas satu sama lain. Ini harus berupa bilangan bulat \(yaitu bilangan bulat dan bukan desimal\), dan nilai yang lebih tinggi untuk properti z-indeks dari suatu elemen memindahkannya lebih tinggi dalam tumpukan daripada yang memiliki nilai lebih rendah.



#### cosol:

```
Add a z-index property to the element with the class name of first (the red rectangle) 
and set it to a value of 2 so it covers the other element (blue rectangle).

The element with class first should have a z-index value of 2.
```



