# CSS Cheat Sheet
## Class
```CSS
.name {
    /* Selects all elements with class="name" */
}
```
Class can be reused.

## ID
```CSS
#name {
    /* Selects element with id="name" */
}
```
ID can only be used once.

## Groups of CSS Selectors
```CSS
h1, h2 {
    /* Selected elements are separated with commas */
}
```

## Font
```CSS 
font-family: /* Font type */;
font-size: /* Size in pixels */
font-weight: /* bold, bolder*/;
```
Changes to the font used.

## Colour
```CSS
color: /* Foreground colour*/;
background-color: /* Background colour in colour code, RGB, HSL*/;
opacity: /* 0-1 */;
```

# !important
```css
.class {
    name: value !important;
}
```
Used on declarations to override any other declarations for a property and ignore selector specificity.

