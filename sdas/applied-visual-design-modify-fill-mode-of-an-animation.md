## Desain Visual Terapan: Modifikasi Mode Isi dari Animasi

Perhatikan bagaimana animasi me-reset setelah 500ms berlalu, menyebabkan tombol untuk kembali ke warna asli. Anda ingin tombol tetap berwarna \(highlighted\).

Ini dapat dilakukan dengan menyetel properti **animation-fill-mode** ke **forwards**. **animation-fill-mode** menentukan gaya yang diterapkan ke elemen ketika animasi telah selesai. Anda dapat mengaturnya seperti ini:

```css
animation-fill-mode: forwards;
```

#### cosol:

```
Set the animation-fill-mode property of button:hover to forwards so the button stays highlighted 
when a user hovers over it.

button:hover should have a animation-fill-mode property with a value of forwards.
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
    /* add your code below this line */

    /* add your code above this line */
  }
  @keyframes background-color {
    100% {
      background-color: #4791d0;
    }
  }
</style>
<button>Register</button>
```

![](/assets/reg.jpg) : tombol ini kalo di hover akan berganti warna selama 5detik \( karna di setting 500ms. 500ms = 5 detik\)

#### jasol:

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
    /* add your code below this line */
                          animation-fill-mode: forwards;
    /* add your code above this line */
  }
  @keyframes background-color {
    100% {
      background-color: #4791d0;
    }
  }
</style>
<button>Register</button>
```

![](/assets/reg.jpg): nah kalo tombol ini di hover, maka warna akan berubah selama tidak pindah hover MUAHAHAHAHAHAHAHA~

