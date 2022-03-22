# Chart.js and Canvas

## Chart.js

- Charts help display data better visually
- The first step is downloading chart.js and importing it into your document
- Next a canvas for the chart should be made
- A script is then made to retreive the context of the canvas/element
- An object is then created containing the properties and data of the chart

## Canvas API

- `<canvas>` is an HTML element
- its default size is 300px by 150px
- Fallback content can be input in case older browsers are unable to render the element
- canvas requires a closing tag
- canvas can also render text

### Drawing shapes

- grid starts with the origin at the top left
- canvas only supports two primitive shapes rectangles and paths
- `beginPath()`, `closePath()`, `stroke()`, `fill()` are all functions used to create your desired shape
- moveTo(x,y) will readjust where you want the start point of a path to be
- Arcs are created with `arc()` and `arcTo()`
- there are multiple different functions to change the color weight and appearance of paths


[Return to Code 201 Table of Contents](https://rogermreyes.github.io/Reading-Notes/Code-201-Reading-Notes)
