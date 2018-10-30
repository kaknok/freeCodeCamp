## [Jadikan Tipografi Responsif](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-principles/make-typography-responsive)

Alih-alih menggunakan **em** atau **px** untuk ukuran teks, Anda dapat menggunakan unit viewport untuk tipografi responsif. Unit viewport, seperti persentase, adalah unit relatif, tetapi mereka didasarkan pada item yang berbeda. Unit viewport relatif terhadap dimensi viewport \(lebar atau tinggi\) dari suatu perangkat, dan persentase relatif terhadap ukuran elemen kontainer induk.

Empat unit viewport yang berbeda adalah:

* **vw: 10vw** akan menjadi 10% dari lebar viewport.
* **vh: 3vh** akan menjadi 3% dari tinggi viewport.
* **vmin: 70vmin** akan menjadi 70% dari dimensi yang lebih kecil dari viewport \(tinggi vs lebar\).
* **vmax: 100vmax** akan menjadi 100% dari dimensi yang lebih besar dari viewport \(tinggi vs lebar\).



#### cosol:

```
Set the width of the h2 tag to 80% of the viewport's width and the width of the paragraph as 75% 
of the viewport's smaller dimension.

Your h2 tag should have a width of 80vw.
Your p tag should have a width of 75vmin.
```

```css
<style>
  
</style>

<h2>Importantus Ipsum</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus quis tempus massa. 
Aenean erat nisl, gravida vel vestibulum cursus, interdum sit amet lectus. Sed sit amet quam nibh. 
Suspendisse quis tincidunt nulla. In hac habitasse platea dictumst. Ut sit amet pretium nisl. 
Vivamus vel mi sem. Aenean sit amet consectetur sem. Suspendisse pretium, purus et gravida consequat, 
nunc ligula ultricies diam, at aliquet velit libero a dui.</p>
```

![](/assets/ip.jpg)

#### jasol:

```css
<style>
  h2 {
      width: 80vw;
  }

  p {
      width: 75vmin;
  }
</style>

<h2>Importantus Ipsum</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus quis tempus massa. 
Aenean erat nisl, gravida vel vestibulum cursus, interdum sit amet lectus. Sed sit amet quam nibh. 
Suspendisse quis tincidunt nulla. In hac habitasse platea dictumst. Ut sit amet pretium nisl. 
Vivamus vel mi sem. Aenean sit amet consectetur sem. Suspendisse pretium, purus et gravida consequat, 
nunc ligula ultricies diam, at aliquet velit libero a dui.</p>
```

###### ![](/assets/iip.jpg) paragraf jadi keliatan lebih rapat ke kiri 



