## Desain Visual Terapan: Sesuaikan Warna Berbagai Elemen dengan Warna Komplementer

Tantangan Complementary Colors menunjukkan bahwa warna yang berseberangan pada roda warna dapat membuat satu sama lain tampak lebih hidup saat diletakkan berdampingan. Namun, kontras visual yang kuat dapat menggetarkan jika digunakan secara berlebihan di situs web, dan terkadang dapat membuat teks lebih sulit dibaca jika ditempatkan pada latar belakang berwarna komplementer. Dalam prakteknya, salah satu warna biasanya dominan dan pelengkap digunakan untuk membawa perhatian visual ke konten tertentu pada halaman.

#### cosol:

```
Halaman ini akan menggunakan warna biru (# 09A7A1) sebagai warna dominan, dan jingga (# FF790E) 
pelengkap untuk secara visual menyorot tombol-tombol pendaftaran. 
Ubah warna latar belakang dari header dan footer dari hitam ke warna teal. 
Kemudian ubah warna teks h2 menjadi teal juga. Akhirnya, ubah warna latar belakang tombol ke warna oranye.

This page will use a shade of teal (#09A7A1) as the dominant color, and its orange (#FF790E) 
complement to visually highlight the sign-up buttons. 
Change the background-color of both the header and footer from black to the teal color. 
Then change the h2 text color to teal as well. Finally, 
change the background-color of the button to the orange color.


The header element should have a background-color of #09A7A1.
The footer element should have a background-color of #09A7A1.
The h2 element should have a color of #09A7A1.
The button element should have a background-color of #FF790E.
```

```css
<style>
  body {
    background-color: white;
  }
  header {
    background-color: black;
    color: white;
    padding: 0.25em;
  }
  h2 {
    color: black;
  }  
  button {
    background-color: white;
  }
  footer {
    background-color: black;
    color: white;
    padding: 0.5em;
  }
  </style>
<header>
  <h1>Cooking with FCC!</h1>
</header>
<main>
  <article>
    <h2>Machine Learning in the Kitchen</h2>
    <p>Join this two day workshop that walks through how to implement cutting-edge snack-getting 
    algorithms with a command line interface. Coding usually involves writing exact instructions, 
    but sometimes you need your computer to execute flexible commands, like <code>fetch Pringles</code>.
    </p>
    <button>Sign Up</button>
  </article>
  <article>
    <h2>Bisection Vegetable Chopping</h2>
    <p>This week-long retreat will level-up your coding ninja skills to actual ninja skills. No longer is the humble bisection search limited to sorted arrays or coding interview questions, applying its concepts in the kitchen will have you chopping carrots in O(log n) time before you know it.</p>
    <button>Sign Up</button>
  </article>
</main>
<br>
<footer>&copy; 2018 FCC Kitchen</footer>
```

![](/assets/cook1.jpg)

#### jasol:

```css
<style>
  body {
    background-color: white;
  }
  header {
    background-color: #09A7A1;
    color: white;
    padding: 0.25em;
  }
  h2 {
    color: #09A7A1;
  }  
  button {
    background-color: #FF790E;
  }
  footer {
    background-color: #09A7A1;
    color: white;
    padding: 0.5em;
  }
  </style>
  <header>
    <h1>Cooking with FCC!</h1>
  </header>
  <main>
    <article>
      <h2>Machine Learning in the Kitchen</h2>
      <p>Join this two day workshop that walks through how to implement cutting-edge snack-getting algorithms with a command line interface. Coding usually involves writing exact instructions, but sometimes you need your computer to execute flexible commands, like <code>fetch Pringles</code>.</p>
      <button>Sign Up</button>
    </article>
    <article>
    <h2>Bisection Vegetable Chopping</h2>
    <p>This week-long retreat will level-up your coding ninja skills to actual ninja skills. No longer is the humble bisection search limited to sorted arrays or coding interview questions, applying its concepts in the kitchen will have you chopping carrots in O(log n) time before you know it.</p>
    <button>Sign Up</button>
  </article>
</main>
<br>
<footer>&copy; 2018 FCC Kitchen</footer>
```



