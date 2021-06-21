#  HTML Canvas :

### `The <canvas> element is only a container for graphics. You must use JavaScript to actually draw the graphics.`

### `Canvas has several methods for drawing paths, boxes, circles, text, and adding images.`

### `The HTML <canvas> element is used to draw graphics, on the fly, via JavaScript.`

Canvas Examples
A canvas is a rectangular area on an HTML page. By default, a canvas has no border and no content.

* ### The markup looks like this:

#### `<canvas id="myCanvas" width="200" height="100"></canvas>`
Note: Always specify an id attribute (to be referred to in a script), and a width and height attribute to define the size of the canvas. To add a border, use the style attribute.


### Instantiate a new Chart object by sending the ID of div element where the chart is to be rendered. You can also pass DOM element instead of ID
### Pass all the Chart related “options” to the constructor as the second parameter.
### Call chart.render() method to render the chart
### Chart “options” mainly contains 4 important items.

### title object with its text property set.
dataPoints – which is an array of all data items to be rendered
dataSeries – parent of dataPoints that also defines type of chart and other series wide options
data – array element which is collection of one or more dataSeries objects. Here we have only one dataSeries.