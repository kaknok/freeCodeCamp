## [Aksesibilitas yang Diterapkan: Bungkus Tombol Radio dalam Elemen Fieldset untuk Aksesibilitas yang Lebih Baik](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility/wrap-radio-buttons-in-a-fieldset-element-for-better-accessibility)

Topik formulir selanjutnya mencakup aksesibilitas tombol radio. Setiap pilihan diberi **label** dengan atribut **for** yang mengikat **id** dari item yang sesuai sebagaimana tercakup dalam tantangan terakhir. Karena tombol radio sering datang dalam kelompok di mana pengguna harus memilih satu, ada cara untuk secara semantis menunjukkan pilihan adalah bagian dari satu set.

Tag **fieldset** mengelilingi seluruh pengelompokan tombol radio untuk mencapai ini. Sering menggunakan tag **legend** untuk memberikan deskripsi untuk pengelompokan, yang dibaca oleh pembaca layar untuk setiap pilihan dalam elemen **fieldset**.

Pembungkus **fieldset** dan tag **legend** tidak diperlukan ketika pilihannya sudah jelas, seperti pemilihan jenis kelamin. Menggunakan **label** dengan atribut **for** untuk setiap tombol radio sudah cukup.

Inilah contohnya:

```php
<form>
  <fieldset>
    <legend>Choose one of these three items:</legend>
    <input id="one" type="radio" name="items" value="one">
    <label for="one">Choice One</label><br>
    <input id="two" type="radio" name="items" value="two">
    <label for="two">Choice Two</label><br>
    <input id="three" type="radio" name="items" value="three">
    <label for="three">Choice Three</label>
  </fieldset>
</form>
```



#### cosol:

```
Camper Cat wants information about the ninja level of his users when they sign up for his email list. 
He's added a set of radio buttons, 
and learned from our last lesson to use label tags with for attributes for each choice. 
Go Camper Cat! However, his code still needs some help. 
Change the div tag surrounding the radio buttons to a fieldset tag, 
and change the p tag inside it to a legend.

Your code should have a fieldset tag around the radio button set.
Make sure your fieldset element has a closing tag.
Your code should have a legend tag around the text asking what level ninja a user is.
Your code should not have any div tags.
Your code should no longer have a p tag around the text asking what level ninja a user is.
```

```php
<!-- Add your code below this line -->
      <div>
        <p>What level ninja are you?</p>
        <input id="newbie" type="radio" name="levels" value="newbie">
        <label for="newbie">Newbie Kitten</label><br>
        <input id="intermediate" type="radio" name="levels" value="intermediate">
        <label for="intermediate">Developing Student</label><br>
        <input id="master" type="radio" name="levels" value="master">
        <label for="master">Master</label>
      </div>
<!-- Add your code above this line -->
```







```php
<!-- Add your code below this line -->
      <fieldset>
        <legend>What level ninja are you?</legend>
        <input id="newbie" type="radio" name="levels" value="newbie">
        <label for="newbie">Newbie Kitten</label><br>
        <input id="intermediate" type="radio" name="levels" value="intermediate">
        <label for="intermediate">Developing Student</label><br>
        <input id="master" type="radio" name="levels" value="master">
        <label for="master">Master</label>
      </fieldset>
      <!-- Add your code above this line -->
```



