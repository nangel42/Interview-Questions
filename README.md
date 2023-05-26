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
* A: <br /> `A semantic element clearly describes its meaning to both the browser and the developer` <br /> `ex:` <br />
` <form> ` <br /> 
`<table>` <br /> 
`<article>` <br /> 
`<nav>` <br /> 
`<header>` <br /> 
`Clearly defines its content.`

<br />
<br />

### Hard

Work in progress :)



## JavaScript

### Easy

<br />

```
Q: What is a variable and how do I declare one?
```
* A: <br /> `stores a value` <br />
`var variableName = whatever` <br />
`let variableName = whatever` <br />
`const variableName = whatever`

<br />

```
Q: What is the difference between var/let/const?
```
* A: `Var is function scoped`
```
    function myFunc(){
        if(true){
            var varScope = "I can be accessed within this function but outside this block scope"
        }
        console.log(varScope) // can access the var variable anywhere within that function scope
    }
```
<br />
` let & const are block scoped`
```
    function myFunc(){
        if(true){
            let letScope = "I cannot be accessed outside this block scope"
        }
        console.log(letScope) // can only access the let variable within its block scope (within its code block {})
    }
```
<br />
`const cannot be reassigned`
```
const variable = 5
variable = 6 // cannot do this!!!
const variable = [1,2,3]
variable.push(4) //can do this! Not reassigning (important distinction)
```

<br />

```
Q: What are the main data types in Javascript?
```
* A: <br /> `Number` <br /> `string` <br /> `boolean` <br /> `null` <br /> `undefined` <br /> `object`

<br />

```
Q: What is a function and why do we use them?
```
* A: <br /> `set of instructions to execute, allow for reusable code`

<br />

```
Q: What are some different ways to write a loop in Javascript? 
Why would you use them?
```
* A: <br /> `For` <br /> `While` <br /> `ForEach` <br /> `ForIn` <br /> `ForOf` <br />
```
for(let i = 0; i < str.length; i++){}
                                //for: most versatile loop, best for when need to setup specific conditions for the loop such as different starting points, ways to increment, etc. 
                                //let i = 0         --> initialize your counter variable
                                //i < str.length    --> setup condition for running loop (executing code)
                                //i++               --> increment your counter variable
```
```
while(x){}                      //as long as condition is true, will keep running code
```
```
array.forEach(item => {})       //takes array and performs callback function on each item in the array
                                //in this case each element in the array will be access by the parameter "item"
```
```
for(let key in object){         //forIn: used to loop through an object
    console.log(object)         //access the object (need to put the name of the actual object)
    console.log(key)            //access the property (can be any word or use generic "key")
    console.log(object[key])    //access the value (of the property)
}
```
```
for(let item of array)          //forOf: used to loop through an array
                                //each index is accessed by the variable "item" (could be any word)
```

<br />

```
Q: What is an array/why would we use it? 
How do we declare it?
```
* A: <br /> `think of like a variable that holds multiple values, using []`

<br />

```
Q: How do you access an item in an array? 
```
* A: <br /> `by index value`

<br />

```
Q: What do we mean when we say an array is index-based? 
How does this work? 
What else is index-based?
```
* A: <br /> `each value has an associated index` <br /> `indexes start at zero (zero-based)` <br />
`strings are also index based (they are "iterable" - can iterate through each element by index)`

<br />

```
Q: what methods are used to add/remove items from an array?
```
* A: <br /> `push` <br /> `pop` <br /> `shift` <br /> `unshift`

<br />

```
Q: What is an object and why would we use it over an array? 
How do we declare it?
```
* A: <br /> `Structure to hold key/value pairs, when we want to access a value by specific name, using {}` <br />
`objects are "enumerable" not "iterable" (can loop though named properties, rather than index number)`

<br />

```
Q: What are the two things any object can contain? 
What is the difference?
```
A: <br /> `properties and methods (same but method is property that stores a function)`
```
    object = {
        property: 'my property',
        method: () => {}
    }
```

<br />

```
Q: What are the two ways we can access the properties/values of an object?
```
* A: <br /> `dot notation` <br /> `bracket notation`

<br />

```
Q: how do we add/change properties from an object? 
How do we delete a property?
```
* A: <br /> `Simply declare it (person.name = ‘Sean’)  --> will either add the property/value or overwrite value if property already exists` <br />
`delete person.name (not used much)`

<br />

```
Q: How do you write a conditional in Javascript?
```
* A: <br /> `if(condition){code…}` <br /> `else if(condition){code…}` <br /> `else{code…}`

<br />

```
Q: What is a template literal? 
Why would I use it and what is the syntax?
```
* A: <br /> `Way to write a string that can take/inject a dynamic value from a Javascript expression` <br />
`${expression}`

<br />

```
Q: What is the difference between null/undefined?
```
* A: <br />`Undefined (variable not declared or declared and has no value)` <br />
`null (variable is declared, and value is explicitly set to null (nothing/empty)`

<br />

```
Q: What is type coercion?
```
* A: <br /> `when javascript converts from one data type to another`

<br />

```
Q: What are some different ways to write a function in Javascript?
```
* A: <br /> `function declaration`
```
    function myFunc(){}
```
<br />
`function expression (stored in a variable)`
```
    let myFunc = function(){} //this is an anonymous function (takes name from variable)
```
<br />
`arrow function`
```
    let myFunc = () => {} //arrow function is a type of anonymous function
```

<br />

```
Q: What is the use of return in a function? 
Where does the return statement need to be and why?
```
* A: <br /> `have access to the value the function produces` <br />
`needs to be at the end of any code block/execution context after the code you want to run` <br />
`the function with stop execution whenever it hits a return statement`

<br />

```
Q: What is the difference between an argument and parameter? 
When/where do we use each?
```
* A: <br /> `Parameter ("variable" name given when declaring the function)` <br />
`argument (value given when calling the function)`
```
    function runThisFunction(parameter){
        *code*
    }

    runThisFunction(argument)
```

<br />

```
Q: What is the difference between =, ==, ===?
```
* A: <br /> `= is the assignment operator, used to assign a value to a variable` <br /><br />
`== is a comparison operator, used to compare if two things are equal (checks values only)`<br />
    `will perform implicit type coercion if needed to compare values`<br /><br />
`=== is a comparison operator, used to compare if two things are equal (checks values and type)`<br />
    `no type coercion`<br />
    `best to use this by default unless have specific reason to use ==`

<br />

```
Q: What is the DOM?
```
* A: <br /> `Document Object Model. The “document” is an object supplied by the browser (it is inside the global “window” object) that creates a model of all the HTML elements as Javascript objects.`<br />
`This object allows us to access and manipulate our HTML using Javascript`<br />
`The javascript code we write does not alter the HTML it only alters the DOM`

<br />

```
Q: What are the three main steps when using the DOM?
```
* A: <br /> `Step 1: Access the HTML element` <br />
`Step 2: Alter the HTML element` <br />
`Step 3: Append the HTML element`

<br />

```
Q: What are the two main methods for accessing an element?
```
* A: <br /> `document.getElementBy…`<br />
`Document.querySelector`

<br />

```
Q: What are all the parts of an event listener?
```
* A: <br /> `Element.addEventListener(“click”, (e) => {…})` <br />
`attach addEventListener to element` <br />
`First parameter is type of event` <br />
`second parameter is a callback function to execute code when event occurs (called the “event handler”)` <br />
`first parameter of the callback function is always the event (e)`

<br />

```
Q: What are two ways to create an element and append it to the DOM?
```
* A: <br /> `appendChild method`
```
    let newDiv = Document.createElement(‘div’)
    element.appendChild(newDiv)
```
`innerHTML method`
```
element.innerHTML = `<div>${content}</div>`
```

<br />

```
Q: What is asynchronous Code and why do we need it?
```
* A: <br /> `Code that does not run in the normal order of execution but waits to run at a further time or after receiving a response` <br />
`Does not interrupt the normal flow of the program (is non-blocking), so is necessary to allow the program to continue to run`

<br />

```
Q: What are the main HTTP methods/verbs?
```
* A: <br /> `Get` <br /> `Post` <br /> `Put` <br /> `Patch` <br /> `Delete`

<br />

```
Q: What is the difference between a GET and POST request?
```
* A: <br /> `GET “gets” a resource/data from the server`<br />
    `sends all its data to the server within the URL (don’t ever use with sensitive information!)`<br />
    `Can add extra data with the request using query parameters`<br /><br />
`POST “posts” a resource/data to the server`<br />
    `Post sends a body (object) with the data to be posted`<br />
    `Setup header for the request to tell server what to expect`

<br />

```
Q: What is a promise?
```
* A: <br /> `promise is an object that waits for the eventual completion/failure of the asynchronous code`

<br />

```
Q: What are the three states of a promise?
```
* A: <br /> `Resolved` <br /> `rejected` <br /> `pending`

<br />

```
Q: What is .then() and .catch()?
```
* A: <br /> `methods on all promise objects, take callback functions to handle the resolved/rejected cases` <br />
`When a promise is resolved it will then run the .then() method (code you want to run after the original asynchronous code is complete)`<br />
    `.then() will return another promise (can string several .then() methods)`<br /><br />
`When a promise is rejected it will then run the .catch() method (code you want to run if the original asynchronous code fails)`

<br />

```
Q: How do you write a GET/POST fetch request? 
```
* A: `GET`
```
    fetch(url)
        .then(response => response.json())
        .then(data => {})
```
`POST`
```
    fetch(url, {
        method: 'POST', 
        headers: {}, 
        body: {}
    })
        .then(response => response.json())
        .then(data => {})
```

<br />

```
Q: How do you write a GET/POST axios request?
``` 
* A: `GET`
```
    Axios.get(url)
        .then(response => {})
```
`POST`
```
    Axios.post(url, body)
        .then(response => {})
```

<br />
<br />

### Medium


### Hard
