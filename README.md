<div style="position: relative; text-align: center;">
  <p align="center">
  <img src="./ReadMeContent/head.jpg" width="600">
</p>
<h1>CodeShutter</h1>
<p>a simple script that make some images from code like code snap (vscode exstention)</p>

</div>

---

> _An interesting and creative project that generates output directly from your code, similar to the CodeSnap extension in VS Code.
> You can easily integrate and use it within your own scripts and projects._

> _Developer: [HolySnow](https://t.me/Holy_SNow)_

---

# How to use?

> 1. save _image.py_ in your project folder.

> 2. Code:

```python
from image import image_generate

code = '''
print("hello wolrd")'''
name = 'code'
theme = "gruvbox-dark"
a = image_generate(code=code,moddle=theme,name=name)
print(a)

# if a == "Done" image saved else there is an error
```

---

# Theme name list

1. monokai
2. gruvbox-dark
3. gruvbox-light
4. solarized-dark
5. solarized-light
6. dracula
7. xcode
8. vs
9. github
10. native
11. friendly
12. murphy
13. 0pastie
14. tango
15. trac
16. vim
17. autumn
18. bw
19. emacs
20. lovelace
21. manni
22. fruity
23. igor
24. paraiso-dark
25. paraiso-light
26. colorful
27. abap
28. algol
29. algol-nu
30. arduino
31. borland
32. rainbow_dash

> List of all themes:
>
> ```python
> from pygments.styles import get_all_styles
>
> print(list(get_all_styles()))
> ```
>
> .

---

<div style="text-align: center; line-height: 0;">
  <p style="margin:0; padding:0; display:inline;">Bye Bye</p>
  <br/>
  <img src="./ReadMeContent/end.png" width="1000" style="margin:0; padding:0; display:inline;"/>
</div>
