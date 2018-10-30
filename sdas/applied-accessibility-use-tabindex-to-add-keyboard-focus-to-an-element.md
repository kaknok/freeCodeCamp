## [Aksesibilitas yang Diterapkan: Gunakan tabindex untuk Menambahkan Fokus Keyboard ke Elemen](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility/use-tabindex-to-add-keyboard-focus-to-an-element)

The HTML tabindex attribute has three distinct functions relating to an element's keyboard focus. When it's on a tag, it indicates that element can be focused on. The value \(an integer that's positive, negative, or zero\) determines the behavior.



Certain elements, such as links and form controls, automatically receive keyboard focus when a user tabs through a page. It's in the same order as the elements come in the HTML source markup. This same functionality can be given to other elements, such as div, span, and p, by placing a tabindex="0" attribute on them. Here's an example:

```php
<div tabindex="0">I need keyboard focus!</div>
```

Note

_A negative tabindex value \(typically -1\) indicates that an element is focusable, but is not reachable by the keyboard. This method is generally used to bring focus to content programmatically \(like when a div used for a pop-up window is activated\), and is beyond the scope of these challenges._

