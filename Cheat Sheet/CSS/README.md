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
font-size: /* Size in pixels */;
font-weight: /* bold, bolder*/;
text-decoration: underline;
```
Changes to the font used.

## Colour
```CSS
color: /* Foreground colour*/;
background-color: /* Background colour in colour code, RGB, HSL*/;
opacity: /* 0-1 */;
```

## !important
```css
.class {
    name: value !important;
}
```
Used on declarations to override any other declarations for a property and ignore selector specificity.

## Text alignment
```css
text-align: /* left, right, center, justify*/;
```
Used to set the text alignment of inline contents.

## Background image
```css
background-image: url('');
```
<ul>
    <li>url: Resource URL</li>
</ul>
Used to set background image.

## Box sizing
```css
box-sizing: border-box;
```
Default value is content-box, which renders the actual size of the element including the content box; but not the paddings and borders. Border-box, on the other hand, rendres the actual size of an element including the content box, paddings, and borders.

## Margin and Padding
```css
margin: /* top right down left */;
margin-top: ;
margin-left: ;
margin-right: ;
margin-bottom: ;

padding: /* top right down left */;
padding-top: ;
padding-left: ;
padding-right: ;
padding-bottom: ;
```
<img src='https://media.geeksforgeeks.org/wp-content/uploads/box-model-1.png'>
The image above shows the CSS Box-Model that is used. Margin and paddings are set using the above syntax. '<strong style='color: skyblue;'>auto</strong>'  keyword can be used with the property margin to horizontally center an element within its container.<span style='color: red'> * </span>width must be specified beforehand

## Overflow
```css
overflow: /* scroll, hidden, visible */;
```
If content is too large for its container, the CSS overflow property will determine how the browser handles the problem.

## Height and Width
```css
width: ;
min-width: ;
height: ;
max-height: ;
```
Sets element boxes height and width.

## Visibility
```css
visibility: hidden;
```
Used to render <span style='color: skyblue'>hidden</span> objects invisible to the user, without removing them from the page.

## z-index
```css
z-index: /* Positive or negative integer */
```
Specifies how far back or how far forward an element will appear on a webpage when it overlaps other elements.
<span style='color: red;'>*</span>Highest value in foreground

## Positioning
```css
position: /* static, fixed, relative, absolute */;
```
<ul>
    <li>static: Default</li>
    <li>fixed: Pins to a specific spot on a page</li>
    <li>relative: Positions relative to a position where it would have originally been</li>
    <li>absolute: Enables an element to ignore sibling elements and instead be positioned relative to its closest parent element that is positioned with relative or absolute</li>
</ul>

## Float
```css
float: /* left,right */;
```
Determines how far left or right an element should float within its parent element.

## Clear
```css
clear: /* left, right, both, none */;
```
Specifies how an element should behave when it bumps into another element within the same containing element.

## Cursor
```css
a {
    cursor: pointer;
    /* Must be added to all elements instead of event*/
}

```
Cursor is usually set to pointer when hovered above links.

## Link, Visited, Hover, Active (Pseudo-class)
```css
a:link {
}
a:visited {
    /* Changes when link is visited */
}
a:hover {
    /* Changes when pointer is hovered above link */
}
a:active {
    /* Changes when link's site is active */
}
```
Pseudo-classes used to stylize anchor link behaviours.

## Box shadows
```css
box-shadow: 0px 0px/* offset-x  offset-y */;
```
Adds shadows to boxes.

## Variables
```css
--name-of-variable: value;
color: var(--name-of-variable);
```
Variables can be set using double dash (--) followed by the name of the variable. Called inline with the function var().

## Adjacent Sibling Combinator + Pseudo-element
```css
.class li+li::before {
    content: ">";
}
```
Adjacent sibling combinator "+" selects two elements when they are immediately next to each other <strong style="color: red;">*The element that is selected is usually the latter of the pair</strong>. ::before creates a pseudo-element which is used with content, to display content before just before the selected element.

## Transition
```css
transition: color .1s ease-in; /* name duration ease-in*/
```
Used to specify the effects on transition. Can be used multiple times with the aid of a comma in between.
