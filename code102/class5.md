# Design Web Pages with CSS

[Back to home](../README.md)

## What is CSS?

CSS(Cascading Style Sheets) is used for describing how documents are presented visually - how they are arranged and styled.

## How To Include Stlyes?

There are 3 ways you can inclued CSS in your document:

Internal - Uses the style tag in HTML

Inline - Defined within the HTML element itself.

External - Basically write your styles in a .css file and then include it using a < link > in the < head > of your HTML document.

**EXAMPLE:**

< head >

< title > HELLO < /title >

< link rel=“stylesheets” href=“(file name.css)” >

< /head >

## Semi Colons and CSS

This is extremely important and **MUST** be used in CSS. It represents the end of a property declaration.

**EXAMPLE:**

h2 {

color: #5FFCFF;

}

## Color & Background Color Properties

### Color Property

Sets the foreground color value of an element’s text and accepts various types of values like the color name, hex color, RGB, etc.

**EXAMPLE:**

h1 {

color: blue;

}

p {

color: pink;

}

### Background Color Property

Sets the background color of an element.

**EXAMPLE:**

button {

background-color: yellow;

}

### RGB(Red, Green, Blue) Color System

Each channel of either red, green, or blue: ranges from 0-255.

**EXAMPLE:**

rgb(173, 20, 219)

173 - Red
20 - Green
219 - Blue

### Hexadecimal (HEX) Color System

This still uses rgb channels. Each channel ranges from 0-255 **BUT** is represented by a hexadecimal. A hexadecimal has 6 digits that consist of 2 pairs, each represent a channel of red, green, blue.

**EXAMPLE:**

ff  ff  00

red green blue

[Back to home](../README.md)
