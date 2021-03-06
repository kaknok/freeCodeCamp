## Desain Visual Terapan: Gunakan Animasi CSS untuk Merubah Status Hover dari Sebuah Tombol

You can use CSS`@keyframes`to change the color of a button in its hover state.

Here's an example of changing the width of an image on hover:

Anda bisa menggunakan CSS **@keyframes **untuk mengganti warna sebuah **button **pada saat di hover.

berukut adalah contoh dari mengganti width gambar saat di hover:

```css
<style>
  img:hover {
    animation-name: width;
    animation-duration: 500ms;
  }

  @keyframes width {
    100% {
      width: 40px;
    }
  }
</style>

<img src="https://bit.ly/smallgooglelogo" alt="Google's Logo" />
```

#### cosol:

```
Note that ms stands for milliseconds, where 1000ms is equal to 1s.

Use CSS @keyframes to change the background-color of the button element 
so it becomes #4791d0 when a user hovers over it. 
The @keyframes rule should only have an entry for 100%.

The @keyframes rule should use the animation-name background-color.
There should be one rule under @keyframes that changes the background-color to #4791d0 at 100%.
```

```css
<style>
  button {
    border-radius: 5px;
    color: white;
    background-color: #0F5897;
    padding: 5px 10px 8px 10px;
  }

  button:hover {
    animation-name: background-color;
    animation-duration: 500ms;
  }


</style>

<button>Register</button>
```

![](/assets/reg.jpg)

#### jasol:

```
<style>
  button {
    border-radius: 5px;
    color: white;
    background-color: #0F5897;
    padding: 5px 10px 8px 10px;
  }

  button:hover {
    animation-name: background-color;
    animation-duration: 500ms;
  }
  @keyframes background-color {
    100% {
      background-color: #4791d0;
    }
  }

</style>

<button>Register</button>
```

![](/assets/reg.jpg)

tombol diatas apabila di hover akan berubah warna..AHAHAHAHAHAHAAHA!!

