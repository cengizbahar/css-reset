## Css  Webkit My Reset

```
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600&display=swap');

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, img, ins, kbd, q, s, samp,
small, strike, sub, sup, tt, var,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend, input, select, textarea, button,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
	font-family: 'Montserrat', sans-serif;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
a {
    text-decoration: none;
}
img {
    border: 0;
}
:focus {
    outline: 0;
}
.clear {
    clear: both;
}


/* Site General Flex Class Items */

.display-flex {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex; 
}

.justify-content-center {
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
}

.justify-content-start {
  -webkit-box-pack: start;
  -ms-flex-pack: start;
  justify-content: flex-start; 
}

.justify-content-end {
  -webkit-box-pack: end;
  -ms-flex-pack: end;
  justify-content: flex-end; 
}

.justify-content-between{
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between; 
}

.justify-content-around {
  -ms-flex-pack: distribute;
  justify-content: space-around; 
}

.align-items-center {

-webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center; 
}

.align-items-start {
  -webkit-box-align: start;
  -ms-flex-align: start;
  align-items: flex-start;
}

.align-items-end {
  -webkit-box-align: end;
  -ms-flex-align: end;
  align-items: flex-end; 
}


/*Css flex icin s??ralama class listesi*/

.order-1 {
  -webkit-box-ordinal-group: 2;
  -ms-flex-order: 1;
  order: 1; }

.order-2 {
  -webkit-box-ordinal-group: 3;
  -ms-flex-order: 2;
  order: 2; }

.order-3 {
  -webkit-box-ordinal-group: 4;
  -ms-flex-order: 3;
  order: 3; }

.order-4 {
  -webkit-box-ordinal-group: 5;
  -ms-flex-order: 4;
  order: 4; }

.order-5 {
  -webkit-box-ordinal-group: 6;
  -ms-flex-order: 5;
  order: 5; }

.display-grid-mobile {
  display: -ms-grid;
  display: grid; }

.sticky {
  position: -webkit-sticky;
  position: sticky; }

.transition {
transition: all 0.2s ease;
  -webkit-transition: all 0.2s ease;
  -o-transition: all 0.2s ease; 
}
 
/* Font Weight */
.regular {
  font-family: "regular"; }

.medium {
  font-family: "medium"; }

.bold {
  font-family: "bold"; }
  
/* container */
.container-fluid {
	width: 100%;
}
.container {
	max-width: 1440px;
	margin: 0 auto;
}
.row {
	display: flex;
	flex-wrap: wrap;
}

/* column */
.col {
  flex: 1 0 0%;
}
.col-1 {
  flex: 0 0 auto;
  width: 8.3333333333%;
}
.col-2 {
  flex: 0 0 auto;
  width: 16.6666666667%;
}
.col-3 {
  flex: 0 0 auto;
  width: 25%;
}
.col-4 {
  flex: 0 0 auto;
  width: 33.3333333333%;
}
.col-5 {
  flex: 0 0 auto;
  width: 41.6666666667%;
}
.col-6 {
  flex: 0 0 auto;
  width: 50%;
}
.col-7 {
  flex: 0 0 auto;
  width: 58.3333333333%;
}
.col-8 {
  flex: 0 0 auto;
  width: 66.6666666667%;
}
.col-9 {
  flex: 0 0 auto;
  width: 75%;
}
.col-10 {
  flex: 0 0 auto;
  width: 83.3333333333%;
}
.col-11 {
  flex: 0 0 auto;
  width: 91.6666666667%;
}
.col-12 {
  flex: 0 0 auto;
  width: 100%;
}
/* media col */
@media only screen and (max-width: 800px) { 

.col-m-1 {
  flex: 0 0 auto;
  width: 8.3333333333%;
}
.col-m-2 {
  flex: 0 0 auto;
  width: 16.6666666667%;
}
.col-m-3 {
  flex: 0 0 auto;
  width: 25%;
}
.col-m-4 {
  flex: 0 0 auto;
  width: 33.3333333333%;
}
.col-m-5 {
  flex: 0 0 auto;
  width: 41.6666666667%;
}
.col-m-6 {
  flex: 0 0 auto;
  width: 50%;
}
.col-m-7 {
  flex: 0 0 auto;
  width: 58.3333333333%;
}
.col-m-8 {
  flex: 0 0 auto;
  width: 66.6666666667%;
}
.col-m-9 {
  flex: 0 0 auto;
  width: 75%;
}
.col-m-10 {
  flex: 0 0 auto;
  width: 83.3333333333%;
}
.col-m-11 {
  flex: 0 0 auto;
  width: 91.6666666667%;
}
.col-m-12 {
  flex: 0 0 auto;
  width: 100%;
}
}
```

