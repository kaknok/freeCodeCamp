## Desain Visual Terapan: Buat Arah Visual dengan Memudar Elemen dari Kiri ke Kanan

di sini Anda akan mengubah **opacity** dari elemen animasi sehingga secara bertahap memudar saat mencapai sisi kanan layar.



Dalam animasi yang ditampilkan, elemen bulat dengan latar belakang gradien bergerak ke kanan oleh tanda 50% dari animasi per aturan **@keyframes**.

#### cosol:

```
Target the element with the id of ball and add the opacity property set to 0.1 at 50%, 
so the element fades as it moves to the right.

The keyframes rule for fade should set the opacity property to 0.1 at 50%.
```

```css
<style>

  #ball {
    width: 70px;
    height: 70px;
    margin: 50px auto;
    position: fixed;
    left: 20%;
    border-radius: 50%;
    background: linear-gradient(
      35deg,
      #ccffff,
      #ffcccc
    );
    animation-name: fade;
    animation-duration: 50s;
  }
  @keyframes fade {
    50% {
      left: 60%;
      
    }
  }

</style>

<div id="ball"></div>
```

###### ![](/assets/bundar.jpg): bulatan ni ntar ke kanan dan ke kiri



#### jasol:





