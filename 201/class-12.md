# Reading Notes Class 12

  ## Class 12 Chart.js API & Canvas API

Charts are far better for displaying Data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.

A great tool to use to get started with charts is to use chart.js which is a JavaScript plugin that uses HTML5's **canvas** element to draw a graph onto a page. ex:

``<meta chairset="utf-8"/>``
``<title>Chart.js demo</title>``
``<script src=Chart.min.js></script>``

To draw a line chart the first thing you need to do is create an element in HTML so chart.js can draw the chart ex - 

  ``<canvas id="buyers" width="600" height="400"></canvas>``

Next you will want to go to your JavaScript and add your js. ex - 

  ``var buyers = document.getElementById('buyers').getContext('2d');``
    ``new Chart(buyers).Line(buyerData);``

Then inside the same script your going to want to place data that contains the object dataset ex -

  ``var buyerData = {``
      ``labels: ["jan, feb, mar, apr"];``
      ``datasets: [``
        ``{``
          ``fillColor: "rgba(172,194,132,0.4)";``
          ``strokeColor:"#ACC26D";``
          ``pointStrokeColor: "#9db86d";``
          ``data: [203, 156, 99, 251];``
        ``}``
      ``]``
  ``}``

Building pie charts you would follow the same pratices except in your js you would use formating like bellow.

  ``var pieData = ["``
  ``{``
    ``value: 20;``
    ``color: "#878bb6";``
  ``}]``

  - And you will supply a value for each color for each section. 

For building a bar chart the js is a little different ex - 

  ``var pieOptions= {``
      ``segmentShowStroke: false;``
      ``animateScale: true;``
  ``}``

  - Then the canvas element format is the same and its added next. Then the element to create the graph. Then finally the bar chart data is put into the js.

  [*Click here to return to the table of Contents*](README.md)

