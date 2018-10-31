## [Align Elements Menggunakan Properti justify-content](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/align-elements-using-the-justify-content-property)

Kadang-kadang barang-barang flex dalam wadah fleksibel tidak mengisi semua ruang dalam wadah. Adalah umum untuk ingin memberi tahu CSS cara menyelaraskan dan melonggarkan item flex dengan cara tertentu. Untungnya, properti **justify-content** memiliki beberapa opsi untuk melakukan ini. Tetapi pertama, ada beberapa terminologi penting yang harus dipahami sebelum meninjau opsi-opsi itu.



[Di sini adalah gambar yang berguna menunjukkan deretan untuk menggambarkan konsep di bawah ini.](https://www.w3.org/TR/css-flexbox-1/images/flex-direction-terms.svg)



Ingat bahwa pengaturan wadah fleksibel sebagai baris menempatkan item fleksibel bersebelahan dari kiri ke kanan. Wadah fleksibel yang disetel sebagai kolom menempatkan item lentur dalam tumpukan vertikal dari atas ke bawah. Untuk masing-masing, arah item flex diatur disebut sumbu utama. Untuk sebuah baris, ini adalah garis horizontal yang memotong setiap item. Dan untuk kolom, sumbu utama adalah garis vertikal melalui item.



Ada beberapa opsi untuk bagaimana meluruskan benda-benda flex di sepanjang garis yang merupakan poros utama. Salah satu yang paling umum digunakan adalah justify-content: center ;, yang meluruskan semua item flex ke pusat di dalam wadah fleksibel. Pilihan lain termasuk:



flex-start: meratakan item ke awal dari wadah fleksibel. Untuk berturut-turut, ini mendorong item ke sebelah kiri wadah. Untuk kolom, ini mendorong item ke bagian atas penampung.

flex-end: meluruskan item ke ujung wadah flex. Untuk berturut-turut, ini mendorong barang di sebelah kanan wadah. Untuk kolom, ini mendorong item ke bagian bawah penampung.

spasi-antara: menyelaraskan item ke pusat sumbu utama, dengan ruang ekstra ditempatkan di antara item. Item pertama dan terakhir didorong ke bagian paling ujung dari wadah fleksibel. Sebagai contoh, berturut-turut barang pertama berada di sisi kiri wadah, item terakhir berada di sisi kanan wadah, lalu item lain di antara keduanya diberi jarak secara merata.

ruang-sekitar: mirip dengan ruang-antara tetapi item pertama dan terakhir tidak terkunci ke tepi wadah, ruang didistribusikan di sekitar semua item

