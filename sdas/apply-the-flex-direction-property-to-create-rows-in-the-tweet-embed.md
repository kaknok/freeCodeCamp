## [Menerapkan Properti arah-fleksibel untuk Membuat Baris di Tweet Embed](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/apply-the-flex-direction-property-to-create-rows-in-the-tweet-embed)

Header dan footer di contoh embed tweet memiliki item anak yang dapat diatur sebagai baris menggunakan properti arah-fleksibel. Ini memberitahu CSS untuk menyelaraskan anak-anak secara horizontal.

#### cosol:

```
Add the CSS property flex-direction to both the header and footer and set the value to row.

The header should have a flex-direction property set to row.
The footer should have a flex-direction property set to row.
```

```css
<style>
  body {
    font-family: Arial, sans-serif;
  }
  header {
    display: flex;

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
  header .follow-btn {
    display: flex;
    margin: 0 0 0 auto;
  }
  header .follow-btn button {
    border: 0;
    border-radius: 3px;
    padding: 5px;
  }
  header h3, header h4 {
    display: flex;
    margin: 0;
  }
  #inner p {
    margin-bottom: 10px;
    font-size: 20px;
  }
  #inner hr {
    margin: 20px 0;
    border-style: solid;
    opacity: 0.1;
  }
  footer {
    display: flex;

  }
```

![](/assets/ssss.jpg)



#### jasol:

```css
<style>
  body {
    font-family: Arial, sans-serif;
  }
  header {
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
  header .follow-btn {
    display: flex;
    margin: 0 0 0 auto;
  }
  header .follow-btn button {
    border: 0;
    border-radius: 3px;
    padding: 5px;
  }
  header h3, header h4 {
    display: flex;
    margin: 0;
  }
  #inner p {
    margin-bottom: 10px;
    font-size: 20px;
  }
  #inner hr {
    margin: 20px 0;
    border-style: solid;
    opacity: 0.1;
  }
  footer {
    display: flex;
    flex-direction: row;
  }
```



