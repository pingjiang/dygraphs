**NOTE: This project have been fully moved to github: [http://github.com/danvk/dygraphs](http://github.com/danvk/dygraphs)**

New issue tracker [HERE](https://github.com/danvk/dygraphs/issues)


Older material below.


---


For more documentation, see [http://danvk.org/dygraphs/](http://danvk.org/dygraphs/)


The dygraphs JavaScript library produces produces interactive, zoomable charts of time series. It is designed to display dense data sets and enable users to explore and interpret them.

### Features ###
  * Plots time series without using an external server or Flash
  * Works in Internet Explorer (using excanvas)
  * Lightweight (45kb) and responsive
  * Displays values on mouseover (this makes it easily discoverable)
  * Supports error bands around data series
  * Interactive zoom
  * Adjustable averaging period
  * Can intelligently chart fractions
  * Customizable click-through actions
  * Compatible with the Google Visualization API
  * Intelligent defaults make it easy to use

### Demo ###
For a gallery and documentation, see [http://danvk.org/dygraphs/](http://danvk.org/dygraphs/)

### Short Example ###
```
<html>
<head>
  <script type="text/javascript" src="dygraph-combined.js"></script>
</head>
<body>
<div id="graphdiv"></div>
<script type="text/javascript">
  g = new Dygraph(
        // containing div
        document.getElementById("graphdiv"),
        // CSV or path to a CSV file.
        "Date,Temperature\n" +
        "2008-05-07,75\n" +
        "2008-05-08,70\n" +
        "2008-05-09,80\n"
      );
</script>
</body>
</html>
```

### License ###
dygraphs uses:
  * MochiKit (MIT License)
  * PlotKit (BSD License)
  * excanvas.js (Apache License)

The dygraphs library is available under the MIT license (see LICENSE.txt).