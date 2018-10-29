## Desain Visual Terapan: Elemen Animate Terus Menggunakan Jumlah Animasi Tak Terbatas

Tantangan sebelumnya meliputi cara menggunakan beberapa properti animasi dan aturan @keyframes. Properti animasi lain adalah animation-iteration-count, yang memungkinkan Anda untuk mengontrol berapa kali Anda ingin mengulang melalui animasi. Inilah contohnya:

```css
animation-iteration-count: 3;
```

Dalam hal ini animasi akan berhenti setelah menjalankan 3 kali, tetapi mungkin untuk membuat animasi berjalan terus menerus dengan menyetel nilai tersebut menjadi tak terbatas.

#### cosol:

```
To keep the ball bouncing on the right on a continuous loop, 
change the animation-iteration-count property to infinite.

The animation-iteration-count property should have a value of infinite.
```

```css
<style>

  #ball {
    width: 100px;
    height: 100px;
    margin: 50px auto;
    position: relative;
    border-radius: 50%;
    background: linear-gradient(
      35deg,
      #ccffff,
      #ffcccc
    );
    animation-name: bounce;
    animation-duration: 1s;
    animation-iteration-count: 8;
  }
    @keyframes bounce{
    0% {
      top: 0px;
    }
    50% {
      top: 249px;
      width: 130px;
      height: 70px;
    }
    100% {
      top: 0px;
    }
  }
</style>
<div id="ball"></div>
```

###### ![](/assets/bundar.jpg) : bulatan ini akan mantul2 3x, tergantung dari animation-iteration-count nya di set berapa valuenya

#### jasol:

```css
<style>

  #ball {
    width: 100px;
    height: 100px;
    margin: 50px auto;
    position: relative;
    border-radius: 50%;
    background: linear-gradient(
      35deg,
      #ccffff,
      #ffcccc
    );
    animation-name: bounce;
    animation-duration: 1s;
    animation-iteration-count: infinite;
  }
    @keyframes bounce{
    0% {
      top: 0px;
    }
    50% {
      top: 249px;
      width: 130px;
      height: 70px;
    }
    100% {
      top: 0px;
    }
  }
</style>
<div id="ball"></div>
```

###### ![](/assets/bundar.jpg): nah kalo animation-iteration-count nya di set ke infinite / tidak terbatas, maka bola akan mantul2 trus



