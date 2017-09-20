# Front End Developer Quiz - Questions


## HTML

1. What does HTML stand for. (1 point)

2. Write out the HTML5 DOCTYPE. (1 point)

3. How do you write an image tag in HTML5. (1 point)

4. How would you write a comment in HTML. (1 point)

5. Write out a description list with a title and a description. (1 point)

6. Out of the following:

```html
<img> <a> <table> <p> <td> <h1> <b> <ul>
```


Write out the Block elements, (1 point)

and the inline elements. (1 point)


7. What's the entity name for a non-breaking space. (1 point)

8. What's the URL-encoding for the ASCII character !. (1 point)

9. Name the 3 supported video formats for the video tag. (1 point)

10. Which of the following is not a HTML5 Semantic Element: (1 point)

```html
<header>
<nav>
<section>
<article>
<aside>
<figcaption>
<figure>
<footer>
```


## CSS

1. In CSS write out the colour red 3 different ways. (1 point)

2. What's the shortest way to write: (1 point)

```css
margin-top: 50px;
margin-right: 0px;
margin-bottom: 50px;
margin-left: 0px;
```


3. How would you make the following text all uppercase 'This Is Some Text Here'. (1 point)

4. By default the box model will subtract padding away from a width, how can you prevent this. (1 point)

5. Which selector would be best to use. (1 point)

```css
1 {
	color: red;
}

.1 {
	color: red;
}

one {
	color: red;
}

.one {
	color: red;
}
```


6. Out of the following which are CSS Preprocessors. (1 point)
Less, Sass, Turbine, Switch, Cacheer, Stylus, Preprocessor, DtCSS, CSS PP.

7. How would you write a filename for a partial file. (1 point)

8. Using the following mixin:

```sass
@mixin image-2x($image, $width, $height) {
  @media (min--moz-device-pixel-ratio: 1.3),
         (-o-min-device-pixel-ratio: 2.6/2),
         (-webkit-min-device-pixel-ratio: 1.3),
         (min-device-pixel-ratio: 1.3),
         (min-resolution: 1.3dppx) {
    /* on retina, use image that's scaled by 2 */
    background-image: url($image);
    background-size: $width $height;
  }
}
```


Fill in the blanks here: (1 point for each correct line)

```sass
div.logo {
             :    ("        ")          ;
   @include        ("          ",      ,     );
}
```


So it outputs:

```css
div.logo {
  background: url("logo.png") no-repeat;
}
@media (min--moz-device-pixel-ratio: 1.3), (-o-min-device-pixel-ratio: 2.6 / 2), (-webkit-min-device-pixel-ratio: 1.3), (min-device-pixel-ratio: 1.3), (min-resolution: 1.3dppx) {
  div.logo {
    /* on retina, use image that's scaled by 2 */
    background-image: url("logo2x.png");
    background-size: 100px 25px;
  }
}
```


9. When expanded using Emmet what would the following be: (1/2 point for each)

```css
fl
m10-a
p20
w100
h50
bg
```


10. Fill in the missing 2 lines from the following image replacement technique: (1 point for each)

```css
.ir {
    background-color: transparent;
    border: 0;
    
}

.ir:before {
    
    display: block;
    width: 0;
    height: 150%;
}
```


## JavaScript

1. What would the following output: (1/2 point for each)

```javascript
'' == '0'
0 == ''
0 == '0'
false == 'false'
false == '0'
false == undefined
false == null
null == undefined
```


2.  What do the following evaluate to? (1/2 point for each)

```javascript
"1" + 2 + 4
5 + 4 + "3"
```


3. What would the following evaluate to: (1 point)

```javascript
console.log (foo());
var foo = function () { return "zz";};
```


4. What are the 5 data types that are supported in JavaScript? (1 point)

5. What's the Unicode value for a Backspace. (1 point)

6. Which of the following are true. (1 point)
a. JavaScript is Object-oriented.
b. JavaScript is Class-based.
c. JavaScript variable data types must be declared (static typing).
d. JavaScript variable data types are not declared (dynamic typing).
e. JavaScript cannot automatically write to hard disk.
f. JavaScript can automatically write to hard disk.

7. What does NaN stand for. (1 point)

8. What will the following evaluate to: (1/2 point for each)

```javascript
"bob".replace("b", "x");
"bob".replace(/b/, "x");
"bob".replace(/b/g, "x");
"bob".replace(new RegExp("b", "g"), "x");
```


9. What did JavaScript used to be called. (1 point)

10. When was it renamed to JavaScript (DD/MM/YYYY). (1 point for each)


## Browser

1. What's the best thing about IE? (1 point)

2. Put the following in order of release (1 point for the correct order, 1/2 point for each correct year):
IE, Firefox, Chrome, Mosaic, Safari, Netscape, Opera.

3. What's the shortcut to open Chrome Developer Tools. (1 point)

4. What's the shortcut to bring up the Settings in Chrome Dev Tools. (1 point)

5. Is it possible to style the Chrome Dev Tools theme? (1 point)


## Who's Who?!

1. Who is also known as “The Godfather of Web Standards”. (1 point)

2. Who invented jQuery. (1 point)

3. When considering optimising web performance, who would "WWSSD" relate to. (1 point)

4. Who is the inventor of the World Wide Web. (1 point)

5. Who are the 2 founders of WordPress. (1 point for each)


## One More For The Road

1. <http://www.w3schools.com/> or <http://www.w3fools.com/> (1 point)
