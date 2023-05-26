# Interview-Questions
A list of interview questions to study up on!
<br />
<br />
If you have more too add feel free to make a pull request, the more knowledge the better!


https://aws.amazon.com/what-is/sdlc/#:~:text=The%20software%20development%20lifecycle%20(SDLC,expectations%20during%20production%20and%20beyond.

https://github.com/seantayler/Q1-Review

https://github.com/seantayler/Q2-Review

https://github.com/seantayler

https://www.w3schools.blog/javascript-interview-questions-and-answers-freshers-experienced-faq

W3 schools good resource

Learn about AGILE and SCRUM

"How to reverse a string"

"If you come across an issue how do you go about problem solving"



Be prepared on how you would describe your project(s)

What kind of a job/company/team are you looking for

What does CSS/json/html stand for
Box mole in css????
Difference between margin & padding & border
Change the color

What is a variable
Method to use to sort an array (push?)
What is an object & why would we use it over an array
Can u directly use an object instead of an array
Conditional statement
Difference between undefined & null
Main 2 methods for accessing an element
Main http methods (post, get, put...)
Diff between get & post requests
Diff between soap & rest api's
Why use soap vs rest api's

Joins with sql
What is a primary key
How would you reverse a string

What did you do with regards to documentation (how did you document processes, architecture diagrams, etc)

Where do you see yourself in the next 5 years

How do you relate xxx to writing code

How do you stay up-to-date with your programming skills - What resources do you use (Google, stack overflow...)

If you come across a problem, what resources do you use (same as above)

What is SDLC
What is Agile

Have 2-3 questions for them
- what are the challenges you see for this position?
- what do you enjoy most about your team








## CSS

### Easy

<br />

```
Q: how do I connect my css file with in my html file?
```
* A: <br /> `<link rel=“stylesheet” href=“path” />`

<br />

```
Q: What is a selector and what is its syntax?
```
* A: <br /> `way to select html element to change style
Selector { property: value }  — this is called a “rule”
Property is what you want to change, value is how you want to change it`

<br />

```
Q: How would I write a element/class/id/attribute selector?
```
* A: <br />
`element{}, ` <br />
`.class{}, `<br />
`#id{}, `<br />
`element[attribute/value]{} `

<br />

```
Q: What is the box model?
```
* A: <br /> `every element is a rectangle that takes up a certain amount of space and has margin, padding, and border`

<br />

```
Q: What is the difference between margin, padding, and border?
```
* A: <br /> `margin (between elements)` <br />`padding (between element content and border)` <br />`border (outer edge of the element)`

<br />

```
Q: What are the different ways to make a site responsive? Which are native?
```
* A: <br /> `Native - Media Queries, Flexbox, Grid` <br />
`Not Native - Bootstrap`

<br />

```
Q: What is a useful tool to align elements horizontally and create your layout? 
How do we declare something a flex element? 
```
* A: <br /> `Flexbox` <br /> `display: flex`

<br />

```
Q: What are the two categories of flex properties?
```
* A: <br /> `flex container` <br /> `flex child`

<br />

```
Q: How many columns are there in the bootstrap grid system? 
What are the 5 built in breakpoint sizes?
```
* A: <br /> `12` <br /> `xs/sm/md/lg/xl`

<br />

```
Q: How do we write the class name for an element to 
use a specific amount of columns at a specific breakpoint?
```
* A: <br /> class=“`Col-md-8`<br /> `col-xs-4`"

<br />
<br />


### Medium

<br />

```
Q: How do you select multiple elements? all descendants? direct descendants?
```
* A: <br />
`multiple selector: Tag1, tag2, tag3 {}, ` <br />
`descendant selector: tag1 tag2 {}, ` <br />
`direct descendant selector: tag1 > tag2 {} ` <br />

<br />

```
Q: What is specificity? What is the order of specificity?
```
* A: <br /> `how specific the selector is an what will override what
tag/element (1pt), class (10pt), id (100pt), inline (1000pt)`

<br />

```
Q: What are the different ways to change a color?
```
* A: <br />
`by name - color: red` <br />
`by hex - color: #111111` <br />
`by RGBA - color(255, 255, 255, 0.5)` 

<br />

```
Q: What unit is used to specify the length of something? How can you do it in relative units?
```
* A: <br /> `fixed - px
relative - %, vh/vw
relative - em (relative to parents length, 1em same as parent, compounds), rem(always relative to root html element (16 by default)`

<br />
<br />


### Hard

<br />


```
Q: How do select specific children in relation to
the parent without knowing how to access that element?
```
* A: <br />
`element:first-child{}` <br />
`element:last-child{}` <br />
`element:nth-child(3){} `

<br />

```
Q: What is a psuedo-selector? Examples?
```
* A: <br /> `only targets an element when it is in a certain state` <br />
`element:hover {}`

<br />

```
Q: What are the 5 main values for the position property? What do they do?
```
* A: <br /> `static` <br /> `relative (relative to self)` <br /> `absolute (relative to parent)` <br /> `fixed (relative to viewport—not affected by scroll)` <br /> `sticky`

<br />

```
Q: What is the z-index property used for?
```
* A: <br /> `Stack one element on top of the other`

<br />
<br />
<br />




## HTML

### Easy

<br />

```
Q: How do you link to a JS document? Where should this be done and why?
```
* A: <br /> `<script src=“script.js”></script>` <br />
`just before the closing body tag, allows HTML/CSS to load first`

<br />

```
Q: What are the main tags used in every html page? What do they do?
```
* A: <br /> `html` <br /> `head` <br /> `body`

<br />

```
Q: What tag do you use to link to another place? What attribute?
```
* A: <br /> `<a href=''>`

<br />

```
Q: What are the ways we identify/access an element? When would we use one over the other?
```
* A: <br /> `Id (for one specific element)` <br /> `class (for many elements that share same characteristics)` <br /> `attribute (specific cases)`

<br />

```
Q: What are the main display types and what are the differences?
```
* A: <br /> `Block: create new line/box, can have margin/padding` <br />
 `Inline: stay on same line, cannot use margin/padding` <br />
 `Inline-block: stay on same line, can use margin/padding (img/btn)`

<br />

```
Q: What do we use a select element for? What are its children elements?
```
* A: <br /> `Multiple options to select from`

<br />

```
Q: What is the difference between radio and checkbox input types?
```
* A: <br /> `Select one (radio)` <br /> `select many (checkbox)`

<br />
<br />

### Medium

<br />

```
Q: What are some attributes of an input tag?
```
* A: <br /> `Type (type of input)` <br /> `name (id for the input)` <br /> `value (the value in the input)`

<br />

```
Q: What is semantic HTML? What are some examples?
```
* A: <br /> `A semantic element clearly describes its meaning to both the browser and the developer`
<br />
`<form>` <br /> `<table>` <br /> `<article>` <br /> `<nav>` <br /> `<header>` <br /> `Clearly defines its content.`

<br />
<br />

### Hard

Work in progress :)



## JavaScript

### Easy


### Medium


### Hard
