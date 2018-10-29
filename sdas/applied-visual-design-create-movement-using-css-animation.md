## Desain Visual Terapan: Buat Gerakan Menggunakan Animasi CSS

Ketika elemen memiliki posisi tertentu, seperti **fixed** atau **relative**, properti CSS offset **right**, **left**, **up**, dan **down** dapat digunakan dalam aturan animasi untuk membuat gerakan.

Seperti yang ditunjukkan pada contoh di bawah ini, Anda dapat mendorong item ke bawah kemudian ke atas dengan mengatur properti **top** keyframe 50% menjadi 50px, tetapi setelah itu diatur ke 0px untuk bingkai kunci pertama \(0%\) dan yang terakhir \(100%\).

```css
@keyframes rainbow {
  0% {
    background-color: blue;
    top: 0px;
  }
  50% {
    background-color: green;
    top: 50px;
  }
  100% {
    background-color: yellow;
    top: 0px;
  }
}
```

#### cosol:

```
Add a horizontal motion to the div animation. 
Using the left offset property, add to the @keyframes rule so rainbow starts at 0 pixels at 0%, 
moves to 25 pixels at 50%, and ends at -25 pixels at 100%. 
Don't replace the top property in the editor - the animation should have both vertical and horizontal motion.

The @keyframes rule for 0% should use the left offset of 0px.
The @keyframes rule for 50% should use the left offset of 25px.
The @keyframes rule for 100% should use the left offset of -25px.
```

```css
<style>
  div {
    height: 40px;
    width: 70%;
    background: black;
    margin: 50px auto;
    border-radius: 5px;
    position: relative;
  }

#rect {
  animation-name: rainbow;
  animation-duration: 4s;
}

@keyframes rainbow {
  0% {
    background-color: blue;
    top: 0px;

  }
  50% {
    background-color: green;
    top: 50px;

  }
  100% {
    background-color: yellow;
    top: 0px;

  }
}
</style>

<div id="rect"></div>
```

![](/assets/ab.jpg)

#### jasol:

```css
<style>
  div {
    height: 40px;
    width: 70%;
    background: black;
    margin: 50px auto;
    border-radius: 5px;
    position: relative;
  }

#rect {
  animation-name: rainbow;
  animation-duration: 4s;
}

@keyframes rainbow {
  0% {
    background-color: blue;
    top: 0px;
    left: 0px;
  }
  50% {
    background-color: green;
    top: 50px;
    left: 25px;
  }
  100% {
    background-color: yellow;
    top: 0px;
    left: -25px;
  }
}
</style>

<div id="rect"></div>
```

![](/assets/ab.jpg)  **: kotak itam tu ntar naik turun dan berubah warna**

