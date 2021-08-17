## Readings: Chart.js, Canvas
***
### [Chart.js API.](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/) - Written by Sara Vieira
- > Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create. - Sara V.
- Chart.js is a Javascript plugin that uses HTML5's canvas element to draw the graph onto the pages:
  * Setting Up:
    * You start by first downloading [Chart.js](https://github.com/nnnick/Chart.js)
    * Copy the Chart.min.js of the unzipped folder and paste it into the directory you'll be working in.
    * Import the script into your HTML page: `<script src='Chart.min.js'></script>`
  * Drawing a line chart:
    * Add this to your HTML page: `<canvas id="buyers" width="600" height="400"></canvas>`
    * Next, we write our script that retreives the context of the canvas. We then this into the foot of our body element: `<script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
</script>`
    * In our script we need to create data in an object like so: `var buyerData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "rgba(172,194,132,0.4)",
			strokeColor : "#ACC26D",
			pointColor : "#fff",
			pointStrokeColor : "#9DB86D",
			data : [203,156,99,251,305,247]
		}
	]
}`
### Chapter 19: “Practical Information” (476-492) - From the Duckett HTML book
- 
***
## End of Notes
