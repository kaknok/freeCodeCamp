## [Gunakan Properti justify-content di Tweet Embed](https://learn.freecodecamp.org/responsive-web-design/css-flexbox/use-the-justify-content-property-in-the-tweet-embed)

pada sebelumnya adalah sebuah contih dari properti **justify-content. **untuk embed tweet, properti ini bisa di gunakan menyelaraskan item dalam elemen **.profile-name**.

#### cosol:

```
Add the CSS property justify-content to the header's .profile-name element 
and set the value to any of the options from the last challenge.

The .profile-name element should have the justify-content property 
set to any of these values: center, flex-start, flex-end, space-between, or space-around.
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

    margin-left: 10px;
  }
```

![](/assets/megane.jpg)

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
    justify-content: space-around;
    margin-left: 10px;
  }
```

###### ![](/assets/asdwwdwd.jpg) profile name dengan nickname ada jarak



