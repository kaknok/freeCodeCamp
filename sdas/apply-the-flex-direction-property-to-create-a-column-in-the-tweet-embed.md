## [Terapkan Properti flex-direction untuk Membuat Kolom di Tweet Embed](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/apply-the-flex-direction-property-to-create-a-column-in-the-tweet-embed)

tweet embed **header** dan **footer** menggunakan properti **flex-direction** sebelumnya dengan value row. Demikian pula, item di dalam elemen **.profile-name** akan berfungsi dengan baik sebagai kolom.

#### cosol:

```
Add the CSS property flex-direction to the header's .profile-name element and set the value to column.

The .profile-name element should have a flex-direction property set to column.
```

```css
<style>
  body {
    font-family: Arial, sans-serif;
  }
  header, footer {
    display: flex;
    flex-direction: row;
  }
  header .profile-thumbnail {
    width: 50px;
    height: 50px;
    border-radius: 4px;
  }
  header .profile-name {
    display: flex;
    
    margin-left: 10px;
  }
```

![](/assets/twer.jpg)

#### jasol:

```css
<style>
  body {
    font-family: Arial, sans-serif;
  }
  header, footer {
    display: flex;
    flex-direction: row;
  }
  header .profile-thumbnail {
    width: 50px;
    height: 50px;
    border-radius: 4px;
  }
  header .profile-name {
    display: flex;
    flex-direction: column;
    margin-left: 10px;
  }
```

###### ![](/assets/syg.jpg) prifil nama nya berubah



