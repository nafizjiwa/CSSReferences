# CSS Reference<br>
1. VERTICAL TEXT<br>
     element/class_Name {<br>
        writing-mode: vertical-lr;<br>
     }<br>
2. GAP<br>
    element/class_Name {<br>
      gap: 10px 40px; /* puts a gap between rows and columns. A single value would have rows and columns the same */<br>
     }<br>
3. FLIP AN IMAGE<br>
    element/class_Name {<br>
      transform: scaleX(-1); /* flips image horizontally items on left are now on right in picture*/<br>
     }                        /* scaleY(-1) would flip an image from right facing to left facing.*/<br>
4. SMOOTH SCROLLING<br>
    html {<br>
      scroll-behaviour: smooth;<br>
     }<br>
5. SCROLL SNAPPING<br>
     main_Container_Name {<br>
       display: flex;<br>
       overflow-x: hidden; /* keeps the div within the main container from over flowing from the main container*/<br>
       scroll-snap-type: x manditory;<br>
     }<br>
     div_in_Container_Name {<br>
       scroll-snap-align: center;<br>
     }<br>
6. RESIZE EVERYTHING<br>
     element_Name/class {<br>
       overflow: auto;    /* this will allow a container and it elements to resize together */<br>
       resize: both;      /* if both not used can use vertically or horizontally */<br>
     }<br>
7. TRUNCATE<br>
&nbsp; `p { `<br>
&nbsp; &nbsp; &nbsp; `display: -webkit-box;` /* to allow just a preview of text and add ... after the previewed text */ <br>
&nbsp; &nbsp; &nbsp; `-webkit-line-clamp: 1; ` /* states how many lines will show in the preview */ <br>
&nbsp; &nbsp; &nbsp; `-webkit-box-orient: vertical;` <br>
&nbsp; &nbsp; &nbsp; `overflow: hidden;`<br>
&nbsp; &nbsp; &nbsp; `} `<br>
8. TEXT GRADIENT<br>
&nbsp; `element_Name/class {`<br>
&nbsp; &nbsp; &nbsp; &nbsp; `background: linear-gradient(to right, rgb, rgb);` /* set preferred gradient */<br>
&nbsp; &nbsp; &nbsp; &nbsp; `-webkit-background-clip: text;` <br>
&nbsp; &nbsp; &nbsp; &nbsp; `-webkit-text-fill-color: transparent;` <br>
&nbsp; &nbsp; &nbsp; &nbsp; `opacity: 0;` <br>
&nbsp; &nbsp; &nbsp;  ` }` <br>
&nbsp;&nbsp; &nbsp;
9. OBJECT FIT<br>
     An image within a container
     
           
16. ladfslasjl
17. asdfljaslfj
18. 
