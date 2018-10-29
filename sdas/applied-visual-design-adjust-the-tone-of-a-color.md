## Desain Visual Terapan: Menyesuaikan Nada Warna

Opsi **hsl \(\)** dalam CSS juga mempermudah pengaturan nada warna. Mencampur putih dengan rona murni menciptakan warna warna itu, dan menambahkan warna hitam akan membuat bayangan. Atau, nada diproduksi dengan menambahkan abu-abu atau dengan baik pewarna dan bayangan. Ingat bahwa 's' dan 'l' **hsl \(\)** berdiri untuk saturasi dan lightness, masing-masing. Persenasi persen mengubah jumlah abu-abu dan persen terang menentukan berapa banyak putih atau hitam dalam warna. Ini berguna ketika Anda memiliki warna dasar yang Anda suka, tetapi perlu variasi berbeda.

#### casol:

```
The navigation bar on this site currently inherits its background-color from the header element. 
Starting with that color as a base, add a background-color to the nav element so it uses the same cyan hue, 
but has 80% saturation and 25% lightness values to change its tone and shade.

The nav element should have a background-color of the adjusted cyan tone using the hsl() property.
```

```css
<style>
  header {
    background-color: hsl(180, 90%, 35%);
    color: #FFFFFF;
  }

  nav {

  }

  h1 {
    text-indent: 10px;
    padding-top: 10px;
  }

  nav ul {
    margin: 0px;
    padding: 5px 0px 5px 30px;
  }

  nav li {
    display: inline;
    margin-right: 20px;
  }

  a {
    text-decoration: none;
    color: inherit;
  }
</style>
<header>
  <h1>Cooking with FCC!</h1>
  <nav>
    <ul>
      <li><a href="">Home</a></li>
      <li><a href="">Classes</a></li>
      <li><a href="">Contact</a></li>
    </ul>
  </nav>
</header>
```

![](/assets/gili.jpg)

#### jasol:

```
<style>
  header {
    background-color: hsl(180, 90%, 35%);
    color: #FFFFFF;
  }
  
  nav {
  background-color: hsl(180, 80%, 25%)
  }
  
  h1 {
    text-indent: 10px;
    padding-top: 10px;
  }
  
  nav ul {
    margin: 0px;
    padding: 5px 0px 5px 30px;
  }
  nav li {
    display: inline;
    margin-right: 20px;
  }
  
  a {
    text-decoration: none;
    color: inherit;
  }
</style>

<header>
  <h1>Cooking with FCC!</h1>
  <nav>
    <ul>
      <li><a href="">Home</a></li>
      <li><a href="">Classes</a></li>
      <li><a href="">Contact</a></li>
    </ul>
  </nav>
</header>
```

![](/assets/ea.jpg)



