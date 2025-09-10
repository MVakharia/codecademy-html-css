# Codecademy HTML/CSS

Testing grounds for learning HTML and CSS. 

### Study topics list:

#### The ```role``` attribute
- Used to improve accessibility for people using screen readers.

#### Tab index
- An item with a negative tab index can never be reached with a tab press.
- Tab index starts at 1, not 0.
- Items with a tab index that is a positive integer take priority over items without a tab index. 
- Items without a tab index take priority over items with a tab index of 0. 

```<video>```

*   Find a video that you can display using the  ```<video>``` tag.
*   [Make use of the optional attributes, including 'controls'.](https://www.w3schools.com/tags/tag_video.asp)

```<audio>```

*   Find some audio that you can display using the HTML 'audio' tag.

```<embed>```

*   Deprecated, but still part of the HTML specification.

```<em>``` (emphasis)

```<alt>``` (alt attribute)

```<span>```

```<strong>```

```<a>``` (anchor)

```<target>```

```<figure>```

```<figcaption>```

```<section>```

```<article>```

```<aside>```

```<meta>```

```<meta name="viewport">```

```<meta content="width=device-width, initial-scale=1">```

![Part of a cheat sheet.](https://i.ibb.co/wh3qgm78/hash-link-to-part-of-page.png)

By default, HTML is parsed and thus the content of ```<script>``` tags is executed **in the order that the HTML appears.**

We can use the '```<defer>```' and '```<async>```' attributes to modify this order.

The '```<defer>```' attribute.

*   Placed inside the opening ```<script>``` tag.
*   Specifies that all the HTML in a webpage should be parsed **before** executing the script.
*   Gives the HTML a level of load order priority that is higher than the deferred script.

The '```<async>```' attribute.

*   Placed inside the opening ```<script>``` tag.
*   It specifies that all the HTML in a webpage should be parsed **while** executing the script.
*   Gives the HTML the same level of load order priority as the deferred script.

```target = "\_blank"``` in an ```<a>``` tag opens a new tab.

An empty ```alt``` attribute in an ```img``` tag indicates that the image is not a key part of the content.

The ```input``` element

*   Used to create interactive controls for web-based forms in order to accept data from the user.
*   Will be covered in more detail in the HTML Forms section of the Full Stack Developer course.

### The ```<<datalist>>``` element

*   Specifies a list of pre-defined options that can be created by the user.

### HTML Forms

#### ```<form>``` tag attributes

The ```action``` attribute

*   Determines where the information is sent after being entered into the form.

The ```method``` attribute

*   Assigned an HTTP verb, like 'POST', that is included in the HTTP request.
*   HTTP verbs are conventionally written in UPPERCASE.

### Web Accessibility

*   ARIA roles
*   ```role="complementary">```
*   ```role="note">```
*   ```role="presentation">```

#### The ```alt``` attribute

*   In general, the value of ```alt``` should concisely describe the image.
*   For images that are also ```<a>``` elements, the ```alt``` attribute should describe the source that the link targets.
*   If an image conveys no information (such as a decorative border), the ```alt``` attribute should be empty, but should never be omitted.
*   If an image is described by text near the image, do not duplicate the description in the ```alt``` attribute. Use an empty ```alt``` attribute instead.
*   The value of an ```alt``` attribute should be no more than 150 characters.

#### Semantic and non-semantic HTML elements

```<header>``` is a semantic element, while ```<div id="header">``` is not.



You can only use one ```h1``` element per web page.

The ```<main>``` tag

*   Specifies the main content of the document.
*   The content inside the ```main``` tag should be unique to the document.

Title

[Return to study topics page.](studytopics.html)

CSS
---

![The CSS3 logo.](https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg)

@media (media query)

priority: low

*   N/A

Any element with margin: auto will be centred inside a grid container (setting 'display:grid').

priority: low

*   N/A

gap

priority: low

*   N/A

line-height

priority: low

*   N/A

word-spacing

priority: low

*   N/A

letter-spacing

priority: low

*   N/A

@font-face (?)

priority: low

*   N/A

Breadcrumbs

priority: low

*   N/A

inline-flex

priority: low

*   N/A

flex-grow

priority: low

*   N/A

flex-shrink

priority: low

*   N/A

flex-basis

priority: low

*   N/A

flex-wrap

priority: low

*   N/A

flex-direction

priority: low

*   N/A

flex-flow

priority: low

*   N/A

Chaining selectors

priority: low

*   N/A

![Part of a cheat sheet.](https://i.ibb.co/Vp3bPXv3/chaining-selectors.png)

HTML attributes with multiple values

![Part of a cheat sheet.](https://i.ibb.co/KxKqHfMT/attributes-multiple-values.png)

CSS !important rule

![Part of a cheat sheet.](https://i.ibb.co/Kz2SLLn5/css-important-rule.png)

box-sizing: content-box

priority: low

*   N/A

box-sizing: border-box

priority: low

*   N/A

overflow

priority: low

*   N/A

min-width

priority: low

*   N/A

min-height

priority: low

*   N/A

max-width

priority: low

*   N/A

max-height

priority: low

*   N/A

visibility

priority: low

*   N/A

z-index

priority: low

*   N/A

float

priority: low

*   N/A

clear

priority: low

*   N/A

@font-face

priority: low

*   N/A

line-height

priority: low

*   N/A

normal, hover, active, visited

priority: low

*   N/A

cursor

priority: low

*   N/A

skeumorphic buttons

priority: low

*   N/A

### CSS grid stuff

grid-template-columns

priority: low

*   N/A

grid-template-rows

priority: low

*   N/A

grid-template

priority: low

*   N/A

grid-template-area

priority: low

*   N/A

row-gap / column-gap / gap

priority: low

*   N/A

grid-row-start / grid-row-end

priority: low

*   N/A

grid-column-start / grid-column-end

priority: low

*   N/A

grid-area

priority: low

*   N/A

grid-template-areas

priority: low

*   N/A

justify-items

priority: low

*   N/A

justify-content

priority: low

*   N/A

justify-self

priority: low

*   N/A

align-items

priority: low

*   N/A

align-content

priority: low

*   N/A

align-self

priority: low

*   N/A

grid-auto-rows

priority: low

*   The default size for rows in a grid.

grid-auto-columns

*   The default size for columns in a grid.

grid-auto-flow

By default, grids are set to 'grid-auto-flow: row', which means they're filled from left to right, THEN top to bottom.

In a grid with two rows and two columns, the grid will be filled 1, 2, new row for 3, 4 to the right, new row for 5, 6 to the right, new row for 7, 8 to the right, and so on.

Changing the auto-flow to 'column' means that they're filed from top to bottom, THEN left to right.

There are only 5 properties for grid-auto-flow: row|column|dense|row dense|column dense;

justify-content:center;

*   Aligns the item (NOT the text) horizontally (moves it along the x-axis) so that the item is halfway between the left and right.

align-items:center;

*   Aligns the item (NOT the text) vertically (moves it along the y-axis) so that the item is halfway between the top and bottom.

text-align:center

*   Aligns the text (NOT the item) centrally (moves it along the text field's x-axis)

### ALIGN

*   column axis.
*   y-axis.
*   aligning top-to-bottom.
*   'align-items: center' aligns items centrally, top to bottom.

### JUSTIFY

*   row axis.
*   x-axis.
*   aligning left-to-right.
*   'justify-content: center' aligns items centrally, left to right.

If you set 'grid-auto-rows' up with a single value, all rows will default to that value.

If you set 'grid-auto-rows' up with two values (for example, 200px 150px, the rows will alternate between those values.

The first row will be 200px, 2nd row 150px, third row 200px, fourth row 150px, and so on.

justify-content: space-evenly puts a full space at either end: it means that every space in the row is the same,\*even\*, width. This value is space-focused, rather than item-focused, and focuses on all the space in the row, including the end space.

justify-content: space-between is focused only the space between individual items, and disregards any space between an item and the end of its box.

justify-content: space-around puts a half-space at either end. This value is item-focused, rather than space-focused: it puts space \*around\* the items.

@media only screen and (max-width: 480px)

[Simulate mobile devices with device mode](https://developer.chrome.com/docs/devtools/device-mode)

In a media query, the 'or' operator is the comma, and the 'and' operator is the word 'and'.

CSS Tags

*   'link', 'visited', 'hover' and 'active' are all valid states for tags.

Points (pt) and pixels (px)

*   1pt (point) is equal to 1.33px (pixels).

The ':default' selector

*   Selects the default element from a group of associated elements.