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
  * Drawing a pie or bar chart:
    * Very similar concept but your data structure will look different.
- Conclusion: 
  * > The great things about Chart.js are that it’s simple to use and really very flexible. Plus, once you’ve mastered the basics here, you’ll discover that there are tons of options listed in the [documentation](http://www.chartjs.org/docs/).
  
### Canvas API
- Basic Usage of Canvas - From [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
  * 
***
## End of Notes
