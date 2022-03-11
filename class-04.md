# HTML Links, JS Functions, and Intro to CSS Layout

## HTML

## CHapter 4: Links

- Links use `<a>` with a `href` attribute to point towards the URL
- The content between the tags is what the user clicks on to go to the link
- Same site links can be linked with just the name of the file
- `mailto:` attribute wil open the users email program and insert the email associated with the link
- `target` will open the link in a new window
- linking to different sections of the same page can be done by assigning an id to the element then linking the id in th `href` starting with a `#` symbol
- The same can be done to link to a specific part of someone elses page by attaching the `#` and id to the end of the URL

**Directory Structures** - pages can be organized into folders and can be thought of a tree

- The **root** folder is the top level and contains all other folders inside
- files contained in another file are the children and the container is considered the parent

## Chapter 15: Layout

- Block level elements will always start on a new line
- Inline Elements will flow with the surrounding text
- Block level elements inside another block level element follow the same parents child relation
- There are a multitude of screen sizes and screen resolutions so it is best to by as dynamic as possible when designing layout

**Positioning of Elements** - is important for proper page layout

- Relative - Shifts it from its original position and does not affect the flow of other elements
- Absolute - Positions element in relation to its containing element and is ignored by other elements
- Fixed - Positions element in relation to the browser window
- Float - Takes the element out of the normal flow and other elements work around it
- When dealing with float `clear` will help to prevent unpredicted float structures
- `width`, `float`, and `margin` can be used to create a column structure layout  

## JavaScript

## Chapter 3: Functions, Methods, and Objects

**Functions** - A group of statements used to perform a task

- A function will always first be introduced with the `function` keyword
- It is then followed by the function name
- Following the name are a set of curly braces with the code block contained inside
- A function is called by using its name followed by parenthesis `functionName();`
- Functions can be made to require certain **parameters**
- These parameters are filled with **arguments**
- Functions will use `return` in order to return the code blocks results
- Local variables can only be used within the function where they are declared
- Global variables are created outside functions and are hard stored as long as the web page is loaded
- Global variables take more memory than local and are hard set which may lead to naming collisions so they should be used carefully

[Return to Code 201 Table of Contents](https://rogermreyes.github.io/Reading-Notes/Code-201-Reading-Notes)
