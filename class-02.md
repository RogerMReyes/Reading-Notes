# HTML, CSS, and JavaScript Basics

## HTML

### Chapter 2 - Text

**Structural Markup** - Are used to help structurally organize the page.  
The following tags are examples of structural markup

- \<h1 - h6> are used to structure **heading levels**. The main heading starting with 1 and subheadings following higher numbers
- \<p> creates **paragraphs** and will start each element on a new line
- \<b> and \<i> will bold or italicize respectively the elements within the tags
- \<sup> and \<sub> will change the element to superscript or subscript respectively
- If there is more than a singular white space or a line break the browser will automatically treat it as one space. This is called **White Space Collapsing**
- \<br /> will add a **break line** within a paragraph
- \<hr /> will create a **horizontal** line that can be used to separate information
- Tags that do not have an element contained inside are called **Empty Elements**

**Semantic Markup** - These do not alter the structure of the webpage but add more information contained within.  
Examples include

- \<strong> is used for words that should be considered with a **strong emphasis**
- \<em> is to put **emphasis** on certain words that may change the meaning of a sentence
- \<blockquote> is used to contain **long quotes**
- \<q> is used inline and will add **quotation**s** around the content depending on the browser
- \<abbr> used in the attribute of the element in order to define the full term for the **acronym** or **abbreviation**
- \<cite> used to **reference** material from somewhere else
- \<dfn> for indicating a **new** term for the first time
- \<address> contains content details for the author of the page
- \<ins> will **underline** content
- \<del> and \<s> will **cross-out** content with the latter referring to info that is no longer accurate

### Chapter 10 - Introducing CSS

- CSS takes a grouping of HTML elements and is able to manipulate the contents of that grouping
- It will associate rules with the elements that you choose to alter
- Rules are made of 2 parts which are the **selector** and the **declaration**
- Selector - indicates the elements the rule applies to
- Declaration - is the style the elements inside should follow
- A declaration is further broken down into **properties** and **values**
- Properties - are the aspects of the element that you want to be changed
- Values - are how the aspects should be altered

**External CSS** - is CSS contained linked to an external file from the HTML document

- \<link> can be used to direct the browser to an external css file for styling and is made up of `href`, `type`, and `rel`
  - `href` - defines the path to the file
  - `type` - defines the type of file being attributed
  - `rel` - defines the relationship which is "stylesheet" for CSS files

**Internal CSS** is CSS contained within the HTML document

- \<style> is used in order to internally add CSS to the HTML document
- Disadvantages of using Internal CSS is having to repeat the styling on different pages

**CSS Selectors** - used to target a specific group of elements  
Examples of selectors include 

- Class Selectors
- ID Selectors
- Type Selectors

**CSS Cascading** - CSS follows a set of cascading rules for overlapping rules

1. The latter of two identical selectors will take precedence
2. The more specific selector will take precedence
3. !important can be added to raise the priority over other precedences

**Inheritance** - the child elements contained within will also adopt the style of the parent element

## JavaScript

### Chapter 2 - Basic JavaScript Instructions

**Statements** - Each step a computer follows is called a statement
 
**Comments** - are defined by // and are used to help someone who may be reading your code understand the processes behind it  
Multiple lines of a comment can also be denoted by /* */ and will turn everything contained inside into a comment

**Variables** - store temporary bits of information that the script can utilize  
Variables are declared with a keyword such as `var` or `let` followed by a name for the variable  
To assign them a value the `=` sign is used to assign the named variable to whatever value follows the `=` operator  
Variables can always be reassigned values later in the script  
**Rules for Naming Variables**

1. beginning must start with a letter, dollar sign `$`, or underscore `_` and not a number
2. names cannot contain a dash `-` or period`.`
3. names cannot use keywords or reserved words such as var
4. variables names are case sensitive
5. the name should describe the content it is storing
6. Camel Case should be used for names with more than one word

**Data Types** - distinguish the type of information that is being stored  
There are **Numeric** (numbers), **String** (text), and **boolean** (true/false) data types

**Arrays** - Store a list of values  
The values of an array are organized by index  
The first index or the first value starts at index 0.  
values in an array can be changed by referencing the values index number  

**Expressions** - evaluates the result into a singular value  
You can either assign a value to a variable or use two or more values to return a single value  

**Operators** - Expressions use Operators to turn multiple values into a singular value  
Ex. Math +, -, *,

### Chapter 4 - Decisions and Loops

- Decisions within scripts help dictate what parts of code should be executed  
- When running through a decision a condition will be evaluated with an `if` statement and whether or not the condition is true or false determines if the code block is ran  
- These code blocks can be further broken into `else if` and `else` statements to put further conditions and the blocks of code to be ran
- Comparison Operators are used to determine true or false conditions
- A comparison is normally done with two **operands** and and a **comparison operator**  
Ex. if(totalPoints == maxPoints) if the variable totalPoints equals maxPoints then the expression would return true and execute the code block following the if statement
- Operands can also be an entire expression rather than just singular values
- **Logical Operators** Help to compare the results of multiple comparison operators  
Ex. && (and) will only return true of both expressions are true  
While | | (or) will return true if at least one expression is true

[Return to Code 201 Table of Contents](https://rogermreyes.github.io/Reading-Notes/Code-201-Reading-Notes)