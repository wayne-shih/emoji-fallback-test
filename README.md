# emoji fallback test

default font stack
```css
font-family: ... , "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
```

with twemoji font stack as fallback (only displaying when apple emoji is not available)
```css
font-family: ... , "Apple Color Emoji", twemoji, "Segoe UI Emoji", "Segoe UI Symbol";
```