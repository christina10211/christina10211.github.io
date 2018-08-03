

THEMES
You can have dark text on a light page or vice versa by choosing a theme. The CSS file has two classes named:

.light-theme
This has black text on a white page.

.dark-theme
This has light text on a dark page.

The class is applied to the body tag in html (around line 21). The light theme is the default.




TYPE
All of the text elements have two classes: one for the size and style and another to identify the font. It is organized this way so you can switch out different google fonts without using a CSS compiler such as SASS or LESS.

The .super-font class is used for headlines, subheads and labels. It is paired with these classes:
.headline
.kicker
.subhead
.label
.label-text
.credit

The .sub-font class is used for body copy, captions and notes. It is paired with these classes:
.date
.body-text
.note
.caption

Changing a font is a 2-step process:
FIRST, the link needs to be added to the HTML file so the browser knows where to go get the font. (about line 13/html file)
SECOND, the font family attributes of .super-font and/or .sub-font need to be changed in the CSS file. (about line 49/CSS file)



Some suggested pairings:


*****************
Roboto Condensed(super-font) and Lora(sub-font)

html:
    <link href="https://fonts.googleapis.com/css?family=Roboto+Condensed:300,400,700" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Lora:400,400i,700" rel="stylesheet"> 
    
CSS:
.super-font {
    font-family: 'Roboto Condensed', sans-serif;
}
.sub-font {
    font-family: 'Lora', serif;
}

*****************


*****************
Oxygen (super-font) and Muli (sub-font)

html:
<link href="https://fonts.googleapis.com/css?family=Oxygen:300,400,700" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Muli:400,400i,700" rel="stylesheet">


CSS:
.super-font {
	font-family: ‘Oxygen’, sans-serif;
}
.sub-font {
	font-family: 'Muli', serif;
}
*****************



*****************
PT Sans (super-font) and PT Serif (sub-font)

HTML:
<link href="https://fonts.googleapis.com/css?family=PT+Sans:400,700" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=PT+Serif:400,400i,700" rel="stylesheet">

CSS:

.super-font {
    font-family: 'PT Sans', sans-serif;
}
.sub-font {
	font-family: 'PT Serif', serif;
}
*****************





















