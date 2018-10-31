## [Gunakan Properti align-items di Tweet Embed](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/use-the-align-items-property-in-the-tweet-embed)

Tantangan terakhir memperkenalkan properti **align-items** dan memberi contoh. Properti ini dapat diterapkan ke beberapa elemen embed tweet untuk menyelaraskan item flex di dalamnya.

#### cosol:

```
Add the CSS property align-items to the header's .follow-btn element. Set the value to center.

The .follow-btn element should have the align-items property set to a value of center.
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
    flex-direction: column;
    justify-content: center;
    margin-left: 10px;
  }
  header .follow-btn {
    display: flex;
    
    margin: 0 0 0 auto;
  }
```

![](/assets/folo.jpg)

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
    justify-content: center;
    margin-left: 10px;
  }
  header .follow-btn {
    display: flex;
    align-items: center;
    margin: 0 0 0 auto;
  }
```

![](/assets/folor.jpg)



