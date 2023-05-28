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
* A: <br /> `way to select html element to change style` <br />
`Selector { property: value }  — this is called a “rule”` <br />
`Property is what you want to change, value is how you want to change it`

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
* A: <br /> `Native - Media Queries, Flexbox, Grid` <br /> `Not Native - Bootstrap`

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
* A: <br /> class=“`Col-md-8` or `col-xs-4`"

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
* A: <br /> `how specific the selector is an what will override what` <br />
`tag/element (1pt), class (10pt), id (100pt), inline (1000pt)`

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
* A: <br /> `GET`
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
* A: <br />`GET`
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

```
Q: difference between var and let/const?
```
* A: <br /> `var is function scoped` <br />
`let/const are block scoped` <br /> <br />
`const cannot be reassigned (but reference type can change values)`
```
function varFunc(){
    if(true){
        var varScope = "I can be accessed within this function but outside this block scope"
    }
    console.log(varScope) // can access the var variable anywhere within that function scope
}

varFunc()
```
```
function letFunc(){
    if(true){
        let letScope = "I cannot be accessed outside this block scope"
    }
    console.log(letScope) // can only access the let variable within its block scope (within its code block {})
}

letFunc()
```
<br />

`const cannot be reassigned` <br />
`const variable = 5` <br /><br />
`variable = 6 // cannot do this!!!`<br />
`variable++ // cannot do this!!!` <br /><br />
```
const variable = [1,2,3]

variable.push(4) //can do this! Not reassigning (important distinction)

console.log(variable)
```
<br />

```
Q: What are Template Literals and how do I write them?
```
* A: <br /> `way to write a string that can take/inject a dynamic value from a JS expression` <br />
Ex:
    `hello my name is ${name}`

<br />

```
Q: What is .map?
```
* A: <br /> `iterates through array and runs callback function on each item`<br />
```
Returns each item into a new array (does not mutate original)

    Array.map(item => { do this code…})

    const newArr = numArray.map(num => {
        return num * 2
    })
```
<br />

```
Q: What is .filter?
```
* A: <br /> `iterates through array and runs callback function on each item`<br />
```
Returns each item that passes the condition into a new array (does not mutate original)
    Array.filter(item => { do this code…})

    const filteredArr = strArray.filter(name => {
        return name.startsWith('b')
    })
    console.log(filteredArr)
```
```
Chaining Methods
    let filteredNames = strArray.map(name => name.toUpperCase()).filter(name => name.length > 5)
    console.log(strArray)
```

<br />

```
Q: What is the Spread operator? (used for arrays/objects)
```
* A: <br /> `Used to make a shallow copy of an object/array without mutating original`
```
    Simply spreads out the VALUES of one object/array into another

    Object:
        const originalObject = {name: 'Sean', age: 34}
        const copyObject = { ...originalObject}
        const updatedObject = { ...originalObject, role: 'teacher'}

    Array:
    const animals = ['cat', 'dog', 'rat']
    const names = ['felix', 'fido', 'fred']

    const copyAnimals = [...animals]
    const updatedAnimals = [...animals, 'pig', 'monkey']
    const concatArrays = [...animals, ...names]
```    

<br />
<br />






### Medium

<br />

```
Q: What reads and interprets our Javascript code?
```
* A: <br /> `the browser`

<br />

```
Q: What is the global object in the browser?
```
* A: <br /> `window`

<br />

```
Q: Why is it important to always initialize a variable with var/let/const?
```
* A: <br /> `Hoisting occurs, will attach to the global object and pollute scope`

<br />

```
Q: What is concatenation and how can I do it?
```
* A: <br /> `Combining two things together` <br />
options: <br /> `“” + “”`  <br /> `str1.concat('  ', str2)` <br /> `template literals`

<br />

```
Q: What is a javascript expression?
```
* A: <br /> `something that evaluates to a value (variable, function, comparison, etc.)`

<br />

```
Q: How can I tell what data type something is?
```
* A: <br /> `Typeof operator`
Ex: <br />
    `let variable = "hello"` <br />
    `typeof variable //return "string"`

<br />

```
Q: What is a callback function and why would we use them?
```
* A: <br /> `function you pass into another function` <br />
`it is asynchronous (it only runs when the function it is inside is invoked)`

<br />

```
Q: What is a higher order function? Examples?
```
* A: <br /> `function that accepts another function as an argument (or returns a function)` <br />
` any function with a callback function is a higher order function` <br />
Ex: <br /> `map` <br /> `filter` <br /> `reduce` <br /> `forEach` <br /> `setTimeout`

<br />

```
Q: what does the indexOf() method do? what will it return if the item is not in the array?
```
* A: <br /> `search array for a value and return its index position in the array, or return -1`

<br />

```
Q: What method can we use to check if an object has a specific property?
```
* A: <br /> `Obj.hasOwnProperty(‘property’) —returns boolean`

<br />

```
Q: What do I mean by truthy/falsey? 
What are the falsey values?
```
* A: `simply means when this value is type coerced into a boolean (for comparison purposes), what would it evaluate to?`<br />
    `if it would evaluate to false it is considered falsey, if it would evaluate to true it is considered truthy` <br />
`falsey - False, 0, “”, null, undefined, NaN (all other values are truthy)`

<br />

```
Q: What is an API?
```
* A: <br /> `Application programming interface.` <br /> `An API is a server meant to be used/consumed by other applications by hitting their specified endpoints to get/post data.`

<br />

```
Q: What are some parts of a URL?
```
* A: <br /> `base` <br /> `endpoint` <br /> `query parameters` <br />
EX: <br /> `www.base.com/endpoint?queryparameters=value`

<br />

```
Q: What is an endpoint?
```
* A: <br /> `the part of the URL specified by the API to get/post a specific resource` <br />
`the API determines which endpoints can be reached and what resources they will return`

<br />

```
Q: What is a query parameter? What is the syntax?
```
* A: <br /> `Additional data to send via the URL (placed at end of URL)` <br />
`Syntax: ?key=value&key=value`

<br />

```
Q: what is JSON?
```
* A: <br /> `most popular data format on the web` <br />
`a string (plain text) formatted like a javascript object` <br />
`must be converted into actual JS object to be used`

<br />

```
Q: What are the methods we use for converting JSON?
```
* A: <br /> `JSON.parse() — parses JSON string into a JS object` <br />
`JSON.stringify() — parses something into a JSON string`<br />
`res.json() — takes the response and parses the JSON into a JS object`

<br />
```
Q: What is an arrow function?
```
* A: <br /> `shorter syntax for anonymous/callback functions` <br />
    ```
    const myArrowFunction = () => {...}
    ```

<br />

```
Q: What are default parameters?
```
* A: <br /> `Value to be given to the parameter if no argument is passed in`
    ```
    function makePerson(name='Sean', age=34)
    ```

<br />

```
Q: What is object destructuring?
```
* A: <br /> `easier way to references properties of an object`<br /> 
`Get all the properties in any object with one variable declaration`<br />
Ex:
```
    const personObject = {name: 'Sean', age: 34, role: 'teacher'}
    const {name, age, role} = personObject
```

<br />

```
Q: What is a higher order function?
```
/* A: <br /> `A function that takes a callback function as an argument`

<br />

```
Q: What is .forEach?
```
* A: <br /> `iterates through array and runs callback function on each item` <br />
`Doesn't return anything (undefined), simply uses values or mutates original array` <br />
```
    Array.forEach((item) => { do this code…})

    numArray.forEach((num, i) => {
        numArray[i] = num * 2
    })
    console.log(numArray)
```  

<br />
<br />








### Hard

<br />

```
Q: Difference between reference and primitive types?
```
* A: <br /> `Passed by reference (place in memory)` vs. `passed by value (copy)`

<br />

```
Q: Which are the reference and primitive types?
```
* A: <br /> `Reference (objects, arrays, functions)` <br /> `primitives (strings, numbers, booleans, undefined, null)`

<br />

```
Q: Which data types are mutable or immutable?
```
* A: <br /> `References types are mutable (values change and update everything that points to it)` <br />
    EX: <br /> `array can change from [1,2,3] to [1,2,3,4] and still refer to the same array` <br />
`Primitive types are immutible` <br />
    EX: <br /> `a number cannot change from 3 to 4 and still refer to the same number (it is now refering to a different number)`

<br />

```
Q: Will this evaluate to true or false and why?
[1, 2, 3] == [1, 2, 3]
```
* A: <br /> `False. Because arrays and objects are reference types` <br />
`so even if another array/object is exactly alike it is considered a different array/object and thus not equal`

<br />

```
Q: What is the difference between shallow and deep copies?
```
* A: <br />`Shallow copy goes one level deep while copying, doesn't copy any references (just the values)` <br />
`Deep copy not only copies all nested levels however deep, but it also copies any references`

<br />

```
Q: How can I make a shallow copy of an array?
```
* A: <br />`slice()`<br /> `map()`<br /> `filter()`<br /> `reduce()`<br /> `spread operator`

<br />

```
Q: how can I make a shallow copy of an object?
```
* A: <br /> `Object.create({} obj)`<br /> `object.assign({}, obj)` <br /> `spread operator`

<br />

```
Q: what does Object.keys() do?
```
* A: <br />`returns an array of a given object's own property names, in the same order as we get with a normal loop.`

<br />

```
Q: What is the ternary operator?
```
* A: `another way to write a condition (more concise)` <br />
Ex: `Condition ? True : false`
```
    conditional
    if(person.name === 'Sean'){
        person.role = 'instructor' 
    } else { 
        person.role = 'student' 
    }
```
```
    //ternary
    person.role = person.name === 'Sean' ? 'instructor' : 'student'
    //read: if person.name equals Sean is true, then person.role is instructor, else if it is false, then person.role is student
```

<br />

```
Q: What is event bubbling?
```
* A: <br /> `When an event is fired, it then bubbles up and is fired also by its parent, grandparent, and so on up the entire DOM tree.` <br />
`thus you can put your event listener anywhere that you want the event to be handled`

<br />

```
Q: How can we prevent event bubbling?
```
* A: <br /> `e.stopPropagation()`

<br />

```
Q: What is traversing the DOM? 
What methods can we use?
```
* A: <br />`How to move from one part of the DOM to another and select elements based on their relation to each other in the DOM`<br />
Ex: `element  +  parentNode()`<br />
`.children()`<br />
`.firstChild()` <br />
`.lastChild()`<br />
`.previousSibling()`<br />
`.nextSibling()`<br />

<br />

```
Q: What is promise.all()
```
* A: <br />`takes an array of promises, returns a single promise that resolves and runs all the promises at once when they are all ready (all the promises have been resolved)`<br />
`if any are rejected, none will be run`

<br />

```
Q: What is callback hell and how do we avoid it?
```
* A: <br />`before promises (or async/await), callback functions were used to handle asynchronous code, but then there would often have to be MANY nested callbacks which made the code very ugly and less easy to read/maintain. This is referred to as “callback hell”.`
```
    function asyncFunc((cb1) => {
        (cb2) => {
            (cb3) => {
                (cb4) => {
                    (cb5) => {
                        (cb6) => {
                            (cb7) => {
                                (cb8) => {
                                   
                                }
                            }
                        }
                    }
                }
            }
        }
    })
```
`We can avoid callback hell by using promises and stringing/chaining .then() methods to handle the asynchronous code (much more readable!)`
```
    Axios.get(url)
        .then(() => {})
        .then(() => {})
        .then(() => {})
        .then(() => {})
        .then(() => {})
```

<br />

```
Q: What is async/await?
```
* A: <br />`way to handle asynchronous code`<br />
`Async is keyword to specify a function is asynchronous `<br />
`Await is keyword to pause execution of function until the async code is resolved, then will continue `

<br />

```
Q: What is a switch statement?
```
* A: <br /> `Another way to write a condition, used when you know the specific set of possible options`<br />
    Syntax: <br />
    ```
    switch(expression){
        case value1: 
            statement; 
            break; 
        case value1: 
            statement; 
            break; 
        default: 
            statement;
    }
    ```
    Expression <br />
        `name for type of value to be expected (can be any word)`
    Case Values <br />
	    `Value tested to see if equal to the expression` <br />
	    `Case values are tested with strict equality (===)` <br />
	    `Can have as many case values as desired` <br />
	Statements <br />
	    `Statement is code executed if the expression matches the value`<br />
	    `If not it breaks off and moves on the next case value`<br />
	Break <br />
	    `The break tells JavaScript to stop executing statements. ` <br />
	    `If the break is omitted, the next statement will be executed (not good!)` <br />
	Default <br />
	    `Will be executed if no matching case statements are found. `<br />
	    `Think of it like the final else statement in an if/else chain.`<br />

    Example: 
```
    switch(season){
        case 'spring':
            return "Spring is in the air";
            break;
        case 'summer':
            return "Don't worry it's a dry heat";
            break;
        case 'fall':
            return "The beautiful leaves of autumn";
            break;
        case 'winter':
            return "Walking in a winter wonderland";
            break;
        default:
            return "You did not type in a valid season name";
    }
```

<br />

```
Q: How does "this" work in Javascript?
```
* A: <br />`“this” is a variable that refers to the object where the function is invoked (its execution context)`<br />
`“this” is usually used inside a function/method and ALWAYS refers to an object` <br />
`used to access specific objects on a context specific basis` <br />
` General: Can usually determine the context of this by looking at what is to the left when function is called (does not matter where it is defined but where called!!!)`<br />
`4 WAYS “this” takes a value (based on how/where function is called)`

```
    1) Within a function call (outside a declared object)
    refers to the global object context
    2) Within methods call (inside a declared object)
    refers to the parent object context
    3) Within a constructor function
    refers to the new instance of the object/class
    4) call(), apply(), bind() methods
    can be used to choose the context of “this”
```
/
    `Arrow Functions` <br />
    `Binds the context of “this” to the enclosing context where the arrow function is defined (its context never changes)` <br />
    `an arrow function does not create its own execution context, but uses the execution context from the outer function (context for “this”)` <br />
    `Arrow function “inherits” its context from the function it is defined inside` <br />
```
    //"this" context #1 (function)
    function thisFunction(){
        console.log(this)
    }
```
```
    //"this" context #2 (method)
    myObject = {
      name: "sean",
      age: 34,
      getOlder: function(){ 
        this.age++
        console.log(this)
      }
    }
```
```
    //"this" context #3 (constructor)
    class Human {
      constructor(name, age){
          this.name = name
          this.age = age
      }
    }
```

<br />

```
Q: What is reduce and how is it used?
```
* A: `Reduce` <br />
`iterates through array and runs callback function on each item` <br />
`results in one output (returns value of whatever type the accumulator is)`<br />
Callback parameters:
```
        //acc: the accumulator
                //this is the value that is returned
                //Accumulates the callbacks return value
                //it is remembered and may be updated across iterations
        //val: the current value
        //Index (optional)
        //Array (optional)
//Second parameter: the initial value (optional)
        //The value the accumulator starts at
        //If value supplied, the acc starts with that value and the current value will start at the first value in the array (index 0)
        //if no value supplied, value will default to first element in the array and the current value will be equal to the second (index 1)

    Array.reduce((acc, val) => { do this code…})
```
```
    //Example #1
    numArray.reduce((sum, num) => {
      return sum + num
    }, 0)
```
```
    //Example #2
    let newArr = [98, 47, 23, -6, 106, 73, 102, 44]

    newArr.reduce((max, cur) => cur > max ? cur : max)
```
```
    //Example #3
    let names = ['Alice', 'Bob', 'Tiff', 'Bruce', 'Alice', 'Bob', 'Bob'];

    names.reduce((nameMap, name) => { 
      nameMap[name] ? nameMap[name]++ : nameMap[name] = 1
      return nameMap
    }, {});
```
```
    //Example #4
    let letterArray = ['a', 'b', 'a', 'b', 'c', 'e', 'e', 'c', 'd', 'd', 'd', 'd', 'a', 'c', 'c'];

    letterArray.reduce((acc, letter) => {
      acc.indexOf(letter) === -1 ? acc.push(letter) : acc
      return acc
    }, [])
```

<br />

```
Q: What is the rest operator? (used as a parameter)
```
* A: <br /> `LAST parameter of a function can be prefixed with (…) which will place all remaining arguments in an array` <br />
    `function sum(...args){ }` <br />  OR   <br /> `function sum(name, age, ...argsCanBeNamedAnything){ }` <br />
    ```
    //can then use array methods

    function multiplyEach(multiplier, ...numbers){
      return numbers.map(num => num * multiplier)
    }

    multiplyEach(5,3,4,5,6,6,7,7,5,3,2)
    ```

<br />

```
Q: What are Classes in javascript?
```
* A: `A simpler way to use prototype inheritance and make instances of objects` <br />
`Classes are like blueprints for objects` <br />
`should be general to be reusable/modular` <br />
	```
    //Constructor (used to setup the details of the class/instance)
        // used to describe how an object should be created and with which properties (fills in the details of the class/instance)
        // The function that is called when a new class instance is created
	```
	```
    //Super (used to extend the details of one class into a new class)
        // Calls the constructor on prototype class to extend its properties to the current class/instance
	```
	```
    // New (used to create a new instance of a class)
        // creates a new empty object
        // sets the value of “this” to be the new object
        // Calls the constructor method (and passes in “this”)
        // adds the “__proto__” property (to access the prototype methods)
	```
	```
    //Prototype Inheritance:
        //one object gets access to the properties and methods of another object
	```
	```
    //Prototype/proto
        // Every class has a “prototype” property
        // where methods are stored
        // can use to write methods to the prototype (Array.prototype.myMethod = () => {})
        // All instances have a “__proto__” property 
        // Links to the prototype and has access to its methods
        // Its looks down until the “prototype chain” to find the method
	```
	```
    //Syntax: 
            class Person {
                constructor(name, age, greeting) {
                    this.name = name;
                    this.age = age; 
                    this.greeting = greeting;
                }
                greet() {
                    console.log(this.greeting)
                }
            }

            let sam = new Person('Sam', 22, 'Whattup Brah') 
    
    
            class Teacher extends Person {
                constructor() {
                    super()
                    this.role = 'teacher'
                }
                teach() {
                    studentKnowledge += 100;
                }
                motivate() {
                    studentMorale += 100;
                }
            }

            let sean = new Teacher('Sean', 34, 'Hey there Buckaroo') 
	```
	
## Javascript Librarys

### Easy

<br />

```
Q: Why use React? 
What are the benefits?
```
* A: <br /> `Very fast/performant, separation of concerns/modularity`

<br />

```
Q: What is JSX? 
What are the benefits?
```
* A: <br /> `templating language, html-like syntax with dynamic javascript capability`

<br />

```
Q: How do you do conditional rendering in React?
```
* A: <br /> `Setup some condition (often in state), then use a conditional (often a ternary) to render one thing or another (or null)`
```
{ isLoggedIn ? <div>Render Me</div> : <div>Not Logged In</div> }
```

<br />

```
Q: Explain the data flow in React?
```
* A: <br /> `data flows down (via props), events flow up (via callback functions)` <br />
`technically it is the event that triggers the reference to the function (passed from the parent) and then the function is executed in the parent component with any data passed to it` <br />

<br />

```
Q: What do all components return?
```
* A: <br /> `JSX`

<br />

```
Q: What causes a component to re-render?
```
* A: <br /> `update to state`

<br />

```
Q: How do I loop over an array and create multiple instances of a component?
```
* A: <br /> `use a map and return an instance of the component for each item in the array`
```
const listOfComponents = components.map(component => {
    return (
        <ChildComponent component={component} />
    )
})
```

<br />

```
Q: What are the differences between state and functional components?
```
* A: `State components: use a class construction, need to use "this" keyword, can use state and lifecycle methods (functional can do this with hooks), use the render method to return JSX` <br />
* A: `Functional components: write with a function, only presentational/dumb components, just return JSX only. `

<br />

```
Q: What is state (local)?
```
* A: <br /> `State is an object that contains the relevant data for the component`

<br />

```
Q: How do you update the state of a component?
```
* A: <br /> `using the setState() method. `
//NEVER say this.state.whatever = newValue

<br />

```
Q: What are the steps to update an input in React?
```
* A: <br /> `1) input has an onChange event listener` <br /> `2) it calls an event handler (handleChange)` <br /> `3) the handler updates the state for that input field` <br /> `4) the input sets its value to be bound to that piece of state` <br />

```
state = {
    search: ""
}

const handleSearch = (e) => {
    const { value, name } = e.target
    this.setState({ [name]: value })
}

return (
    <input value={this.state.search} onChange={this.handleSearch}>
        Search...
    </input>
)
```

<br />

```
Q: What is props?
```
* A: `Props is an object that contains data passed from parent to child component`

<br />

```
Q: How do you declare a prop and how do you access it in the child component?
```
* A: <br /> `1) declare an instance of a component inside some JSX` <br /> `2) pass the prop inside a property of the component` <br /> `3) access by this.props.propName (or no 'this' in a functional component)` <br />

```
<Component data={myPropData} />

inside 'Component': this.props.data
```

<br />

```
Q: What are the two ways to get props in a component? (React + Redux)
```
* A: <br /> `React - pass from parent to child.` <br /> `React-Redux - get from the store using mapStateToProps`

<br />

```
Q: What are the 3 main lifecycle stages?
```
* A: <br /> `Mounting` <br /> `Updating` <br /> `Unmounting`

<br />

```
Q: Which lifecycle method should be used to make an API call and why?
```
* A: <br /> `componentDidMount.` <br /> `Dont want to get data before component mounts because often the component relies on the data or the data needs to be put in state which doesn't exist until the component is mounted`

<br />

```
Q: What is Redux? 
What are the benefits of Redux?
```
* A: <br /> `Redux is a state management library. Allows all application to be handled by one single source of truth and access data anywhere needed. `

<br />

```
Q: Explain the data flow in Redux
```
* A: <br /> `SHORT: Component => Action Creator => Reducer => Store => Component rerenders`
* A: LONG: <br /> `1) Inside component call an action creator. Action creator is a function that returns an action. An action is an object that contains a type and an optional payload. The type tells the reducer which case to run, the payload is the data the reducer will use to update that piece of store state. The action (object) is then dispatched to the reducer. A reducer is a function that takes an action and the previous state and returns the new store state. After the store is updated this then forces the component to rerender and the cycle is complete. `

<br />

```
Q: What is the store in Redux and what 2 things can we access from it?
```
* A: <br /> `Store contains all the relevant application state. We can access the state as well as the dispatch method. `

<br />

```
Q: What is dispatch used for?
```
* A: <br /> `dispatch is used to send the action (object) to the reducer` <br />
* clarification: `it is often said the action creator is dispatched, this is technically incorrect. the action creator is CALLED which then returns an action object which is then dispatched. So it is the result of the action creator (the action) that is dispatched. `

```
dispatchEvent(getAllUsers()) //notice order of operations: action creator is called, it returns an action, then that action is dispatched
```

<br />

```
Q: Explain mapStateToProps
```
* A: <br /> `this is a function (declared outside the component) that allows a component to have access to the store state by mapping the store state to the component. So the component has access to that piece of state through its own props (this.props.users). It takes state as a required parameter (this is the store state) and props as an optional second parameter (this is the props of the component)`

```
const mapStateToProps = state => {
    return {
        users: state.users.all
    }
}
```

<br />

```
Q: Explain mapDispatchToProps
```
* A: <br /> `this is a function (declared outside the component) that allows a component to have access to the dispatch method and for that method to be bound to any action creator, so that any action creator can be called and the action that is returned will automatically be dispatched. This can be written separately as a function or can simply pass an object with any action creators as the second argument to the connect function (easier)`

```
//option #1
const mapDispatchToProps = dispatch => {
    return bindActionCreators({ getAllUsers, loginUser, otherActionCreator }, dispatch)
}
```
```
//option #2
export default connect(mapStateToProps, { getAllUsers, loginUser, otherActionCreator })(Component)
```

<br />

```
Q: What is an action creator?
```
* A: <br /> `Action creator is a function that returns an action.`

<br />

```
Q: What is an action? What properties does it have?
```
* A: <br /> `An action is an object that contains a type and an optional payload. The type tells the reducer which case to run, the payload is the data the reducer will use to update that piece of store state. The action (object) is then dispatched to the reducer.`

<br />

```
Q: What is the role of a reducer?
```
* A: <br /> `A reducer is a function that takes an action and the previous state and returns the new store state.`

<br />

```
Q: What do we need to do in a component to call an action creator and get it to the reducer?
```
* A: <br /> `1) import the action creator into the component` <br /> `2) call the action creator inside the dispatch method to disptach the action to the reducer`

<br />

```
Q: What is react router and why is it useful?
```
* A: <br /> `Way to dynamically render specific components based on the URL`

<br />

```
Q: What is a Link tag used for and what attribute does it use?
```
* A: <br /> `The way to navigate to a particular URL, then the router decides what to render based on that URL. Like a <a> tag but does not cause a rerender, it used the to="url" attribute instead of href`

<br />

```
Q: What is a Route and what 2 attributes does it use?
```
* A: <br /> `Its function is to decide what component to render based on a URL. The two attributes are the URL path and the Component`
```
<Route path="/about" component={About} /> 
```

<br />
<br />


### Medium

<br />

```
Q: How do we bind a method to its component?
```
* A: <br />`we can bind it inside the constructor method (old way) or simply by writing our helper functions as an arrow function (automatically binds the method to the context it was declared)`

<br />

```
Q: What are the similarities between state and props?
```
* A: <br /> `Both are objects, both store data`

<br />

```
Q: What are the differences between state and props?
```
* A: <br /> `props is data meant to be passed/accessed in the child`

<br />

```
Q: What are the arguments that setState takes? (1st is required/2nd is optional)
```
* A: <br /> `1st argument is an object with the piece(s) of state to be updated, second is a callback function that is executed AFTER the state has been set`

<br />

```
Q: What is the "key" used for when looping/creating components?
```
* A: <br /> `key is used to make sure there are no duplicates and to make the process faster`

<br />

```
Q: What are propTypes used for?
```
* A: <br /> `To declare and enforce the expected types for each component prop`

<br />

```
Q: What do we mean by 'Component Lifecycle'?
```
* A: <br /> `The various stages a component goes through. Includes mounting, updating, and unmounting. Can have various things occur at these different stages in the components lifecycle through use of component lifecycle methods. `

<br />

```
Q: What is the difference between mounting and rendering?
```
* A: <br /> `Mounting only occurs once at the beggining of the component lifecycle, render occurs many times anytime there is a change/update to state`

<br />

```
Q: What are the main Lifecycle methods used (name at least 1) in each of the 3 lifecycle stages?
```
* A: <br /> `mounting phase - componentDidMount` <br /> `updating phase - componentDidUpdate` <br /> `unmounting phase - componentWillUnmount`

<br />

```
Q: What do we mean by 'single source of truth'?
```
* A: <br /> `The store (the single source of truth) is the one place all application state is stored, updated, and accessed`

<br />

Q: What is Redux Thunk? How does it work?
//A: Redux Thunk is a middleware to handle asynchronous action creators. When using redux thunk the action creator can return either an object or a function. If the action creator is synchronous it will return an action object like normal. If the action creator is asynchronous it will return a function instead (this is the new part). The function will wait for the asyncronous operation to complete and then the action is manually dispatched inside the function. 

//Q: What does the Provider do in React-Redux?
//A: The provider allows any/all components to have access to the store state

//Q: What does Connect do in React-Redux?
//A: the Connect method allows a specific component to actually access the store state that the provider provides

//Q: What two arguments do we pass connect?
//A: mapStateToProps, mapDispatchToProps

//Q: decribe how to write a reducer. What are its parameters and syntax?
//A: write a function, declare state and action as parameters, state can optionally be set to some initial state, make switch statement with action.type as the value to check, add cases for eah type and return the new state using the payload if necessary

const initialState = {
    all: [],
    one: {}
  }

export default function(state = initialState, action) {
    switch (action.type) {
      case ADD_TODO:
        return [ ...state.all, action.payload ]
      default:
        return state
    }
    

//Q: decribe how to write an Action Creator. 

export const fetchUsers = () => {
  return async dispatch => {
    let response = await axios.get(`http://localhost:8000/users`)
        dispatch({
            type: FETCH_USERS,
            payload: response.data
        })
    }
}
    
export const addListing = (newListing) => {
  return async (dispatch) => {
    let listing = await axios.post(`http://localhost:8000/addbucket/${newListing.id}`, newListing)
    dispatch({
      type: ADD_LISTING,
      payload: listing.data[0]
    })
  }
}

//Q: What is Switch tag used for in React-Router?
//A: Renders the first child <Route> or <Redirect> that matches the location. It only renders the first match (unlike just using route tags which will render all matches)


### Hard



