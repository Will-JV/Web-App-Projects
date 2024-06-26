# HTML Standard Structure

```html
<!DOCTYPE html>
<html>
    <head>
        <title> </title>
    </head>

    <body>
        
    </body>
</html>
```
# Element Tags
## Head
```html
 <head> </head>
 ```
Contains the necessary metadatas.
## Body
```html
<body> </body>
```
Contains main content that is visible on webpage.
## Heading
```html
<h1> </h1>
```
h1-h6 determines the header size from large to small.
## List
```html
<ol> 
    <li> list_1 </li>
    <li> list_2 </li>
</ol>

<ul> 
    <li> list_1 </li>
    <li> list_2 </li>
</ul>
```
<ul>
<li>ol : Ordered List</li>
<li>ul: Unordered List</li>
</ul>

## Video

```html
<video src='video.mp4' controls>
    Video not supported
</video>
```
<ul>
<li>src: Source</li>
<li> controls: Displays control panel</li>
<li> autoplay: Autoplays video when webpage is opened</li>
</ul>
'Video not supported' custom error message will be displayed when video cannot be used.

## Image

```html
<img src='image.jpg' alt='description'>
```
<ul>
<li>src: source</li>
<li>alt: alternative text will be displayed if an image fails to render. Screen reading software will read this aloud too.
</ul>



## Emphasis 
```html
<em> </em>
```
Words will be italicized.

## Division
```html
<div id='ID_name' class='Class_name'>

</div>
```
Division element used as a container that divides an HTML document into sections. Usually used with 'id' or 'class'

## Line Break
```html
<br>
```
Creates a line break in text. Must not have a closing tag.

## Paragraph
```html
<p> </p>
```
Contains a displayed block of text.

## Span
```html
<span> </span>
```
Inline container for text and can be used to group text for styling purposes.

## Strong(bold)
```html
<strong> </strong>
```
Highlights important, serious, or urgent text and browsers will normally render this highlighted text in <strong>bold</strong> by default

## Anchor
```html
<a href='' target='_blank'> </a>
```
<ul>
<li>href: hyperlink reference</li>
<li>target: Hyperlink opens in a new tab if value is set to '_blank'
</ul>

Used to create hyperlinks in an HTML document.

## \#
Used to create hyperlinks to different parts of the same page.

## Comments
```html
<!-- Comments -->
```
Comments are written as above.

## Title
```html
<title> </title>
```
Contains a text that defines the title of an HTML document which is displayed in the browser's title bar or tab.

## Table
```html
<table>
    <thead>
        <tr>
            <th rowspan='2'>heading_1</th>
            <th>heading_2</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td colspan='2'>col_1</td>
            <td>col_2</td>
        </tr>
    </tbody>

    <tfoot>
        <tr>
            <td>summary of col_1</td>
            <td>summary of col_2</td>
        </tr>
    </tfoot>
</table>
```

<ul>
    <li>thead: Table header</li>
    <li>tbody: Table content other than header and footer</li>
    <li>th: Table heading</li>
    <li>tr: Table row</li>
    <li>td: Table data</li>
    <li>rowspan/colspan: Sets the row/column span</li>
</ul>

Format for creating a table.

## Audio
```html
<audio src=''> </audio>
```
Displays audio files.

## Figure and Figcaption
```html
<figure>
    <img>
    <figcaption>Error Message</figcaption>
</figure>
```
Used to encapsulate media such as an image, diagram, or code snippet. The \<figcaption> element is used to describe the media encapsulated within the figure element.

## Section, Article, Aside
```html
<section>
    <article>
        <!-- Main Content -->
    </article>

    <aside>
        <!--Additional information -->
    </aside>
</section>
```
Section defines elements in a document, such as chapters, headings and so on. Article holds content that makes sense on its own such as articles, blogs, and comments.

