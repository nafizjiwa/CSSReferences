# CSS Reference<br>
1. VERTICAL TEXT <br>
&nbsp; &nbsp; `element/class_Name { `<br>
&nbsp; &nbsp; &nbsp; `writing-mode: vertical-lr;`<br>
&nbsp; &nbsp;` } ` <br>

2. GAP <br>
&nbsp; &nbsp; `element/class_Name {` <br>
&nbsp; &nbsp; &nbsp; `gap: 10px 40px;` <br>
/* puts a gap between rows and columns. A single value would have rows and columns the same */ <br>
&nbsp; &nbsp; `}` <br>
<br>
4. FLIP AN IMAGE <br>
&nbsp; &nbsp;` element/class_Name {` <br>
&nbsp; &nbsp; &nbsp; `transform: scaleX(-1);`
     /* flips image horizontally items on left are now on right in picture*/ <br>
&nbsp; &nbsp;    ` } `
             /* scaleY(-1) would flip an image from right facing to left facing.*/ <br>
<br>
6. SMOOTH SCROLLING<br>
&nbsp; &nbsp; `html {`<br>
&nbsp; &nbsp; &nbsp; `scroll-behaviour: smooth;`<br>
&nbsp; &nbsp; `}`<br>
<br>
7. SCROLL SNAPPING<br>
&nbsp; &nbsp; `main_Container_Name {`<br>
&nbsp; &nbsp; &nbsp; `display: flex;`<br>
&nbsp; &nbsp; &nbsp; `overflow-x: hidden;` /* keeps the div from over flowing from the main container*/<br>
&nbsp; &nbsp; &nbsp;  `scroll-snap-type: x manditory;`<br>
&nbsp; &nbsp; `}` <br>
&nbsp; &nbsp; ` div_in_Container_Name {`<br>
&nbsp; &nbsp; &nbsp;  `scroll-snap-align: center;`<br>
&nbsp; &nbsp; `}`<br>
<br>
8. RESIZE EVERYTHING<br>
&nbsp; `element_Name/class {`<br>
&nbsp; &nbsp; &nbsp; `overflow: auto;`    /* this will allow a container and it elements to resize together */<br>
&nbsp; &nbsp; &nbsp; `resize: both;`      /* if both not used can use vertically or horizontally */<br>
&nbsp; &nbsp; `}`<br>
<br>
9. TRUNCATE<br>
&nbsp; `p { `<br>
&nbsp; &nbsp; &nbsp; `display: -webkit-box;` /* to allow just a preview of text and add ... after the previewed text */ <br>
&nbsp; &nbsp; &nbsp; `-webkit-line-clamp: 1; ` /* states how many lines will show in the preview */ <br>
&nbsp; &nbsp; &nbsp; `-webkit-box-orient: vertical;` <br>
&nbsp; &nbsp; &nbsp; `overflow: hidden;`<br>
&nbsp; &nbsp; &nbsp; `} `<br>
<br>
10. TEXT GRADIENT<br>
&nbsp; `element_Name/class {`<br>
&nbsp; &nbsp; &nbsp; &nbsp; `background: linear-gradient(to right, rgb, rgb);` /* set preferred gradient */<br>
&nbsp; &nbsp; &nbsp; &nbsp; `-webkit-background-clip: text;` <br>
&nbsp; &nbsp; &nbsp; &nbsp; `-webkit-text-fill-color: transparent;` <br>
&nbsp; &nbsp; &nbsp; &nbsp; `opacity: 0;` <br>
&nbsp; &nbsp; &nbsp;  ` }` <br>
&nbsp; &nbsp; &nbsp;
11. OBJECT FIT <br>
An image within a container <br>
&nbsp; &nbsp; &nbsp;
     

