# HTML Lists, Control FLow with JS, and the CSS Box Model

## HTML

### Chapter 3 - Lists

- `<ol>` is the indication for an ordered list
- `<ul>` indicates an unordered list
- `<li>` will encase each item on the list regardless if ordered or unordered
- `<dl>` represent definition lists and contain a term tag followed by a definition tag
- `<dt>` represents the term in the definition list
- `<dd>` represents the definition of the term
- Inserting a second list within another list is called a nested list

### Chapter 13 - Boxes

**Box Dimensions** - The box around your content defaults to being just big enough to contain it

- Ways that boxes can be adjusted are by **pixels**, **percentages**, or **ems**
- pixels are easier to accurately control but percentages scale of the size of the webpage
- ems is scaled by the size of the text contained inside
- `min-width` and `max-width` can help regulate the width of boxes if a screen is to small or too big
- `min-height` and `max-height` do the same but for the height of the boxes
- if text doesn't properly fit within a box then it can be controlled with **overflow** to either hide it or allow a scroll to see everything within the box
- **Border** is the separation from one box to another
- **Margin** is the space outside the border
- **Padding** is the space between the inside of the border and the content inside
- Border width and style can be changed to fit the users needs
- Border shorthand goes by width, style, then color
- **Display** is used to turn inline elements into block elements and vice versa or to even hide text from displaying
- **Visibility** lets you choose whether or not content is visible but will still leave the spot open where that content is supposed to be
- **Border Image** cuts the image into nine pieces and applies it to the border
- border image can be further changed using **stretch**, **repeat**, or round**
- **Box Shadow** allows you to put a box shadow around the border
- **Border Radius** can be used to round off box corners
- further altering of the different parts can create different shapes like ellipses

## JavaScript

### Chapter 4 - Decisions and Loops

- `if` statements will check the condition given to them and if true will execute the code block inside
- if unresolved then follow up if statements indicated as `else if` can be used to check other conditions
- **switch** will contain a switch value which will execute the following case that matches the switch value
- if no cases match on a switch statement the default option will run
- JavaScript will attempt to convert data behind the scenes in order to make things make sense. This is called **type coercion**
- Type Coercion allows every value to be treated as either truthy or falsey in JavaScript
- Because of Type Coercion strict equality operators should be used to lessen unexpected values
- When a logical operator short cicuits(stops) it return the last value processed
- Loops will check a condition and run as long as that condition is true
- `for` loops consist of an initial variable, a condition to reach, and an update every time the loop runs
- `break` is used in loops in order to terminate the loop and continue on to the next statement outside the loop
- `continue` will stop the current loop and recheck the condition
- Be careful of infinite loops as a script will run infinitely until its condition is met which may slow or stop your browser
- `while` loops will run until the condition in its parenthesis are met
- `do while` loops will run the code block at least once before checking the while loop condition


[Return to Code 201 Table of Contents](https://rogermreyes.github.io/Reading-Notes/Code-201-Reading-Notes)