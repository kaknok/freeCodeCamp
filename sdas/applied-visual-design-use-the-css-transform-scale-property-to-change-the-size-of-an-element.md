## Desain Visual Terapan: Gunakan CSS Transform scale Property untuk Mengubah Ukuran Elemen

Untuk mengubah skala elemen, CSS memiliki properti **transform**, bersama dengan **scale \(\)** fungsinya. Contoh kode berikut menggandakan ukuran semua elemen paragraf di halaman:

```css
p {
  transform:scale(2);
}
```



#### casol:

```
Increase the size of the element with the id of ball2 to 1.5 times its original size.
Set the transform property for #ball2 to scale it 1.5 times its size.
```

```css
<style>
  .ball { 
    width: 40px;
    height: 40px;
    margin: 50 auto;
    position: fixed;
    background: linear-gradient(
      35deg,
      #ccffff,
      #ffcccc
    );
    border-radius: 50%;
  }
  #ball1 {
    left: 20%;
  }
  #ball2 {
    left: 65%;
    
  }
  <style>
  .ball { 
    width: 40px;
    height: 40px;
    margin: 50 auto;
    position: fixed;
    background: linear-gradient(
      35deg,
      #ccffff,
      #ffcccc
    );
    border-radius: 50%;
  }
  #ball1 {
    left: 20%;
  }
  #ball2 {
    left: 65%;
    
  }
```

![](/assets/was.jpg)



#### jasol:

```
<style>
  .ball { 
    width: 40px;
    height: 40px;
    margin: 50 auto;
    position: fixed;
    background: linear-gradient(
      35deg,
      #ccffff,
      #ffcccc
    );
    border-radius: 50%;
  }
  #ball1 {
    left: 20%;
  }
  #ball2 {
    left: 65%;
    transform: scale(1.5);
  }


</style>

<div class="ball" id= "ball1"></div>
<div class="ball" id= "ball2"></div>
```

![](/assets/wass.jpg)



