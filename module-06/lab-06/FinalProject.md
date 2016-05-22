The target user of this map is someone interested in the water quality of surface and groundwater sources. <br> 
In particular, the user will be concerned with the effects of oil and gas well drilling on water quality. <br>

<b>Map Topic</b><br>
Quality of water sources surrounding oil and gas wells drilled in the Berea Sandstone in northeastern Kentucky. <br>

<b>Objectives and user needs</b><br>	
Display results of several water quality analysis conducted by volunteers in the Kentucky Watershed Watch project(surface) https://sites.google.com/site/watershedwatch/ and the Kentucky Geological Survey(groundwater) and the Kentucky Divison of Water.<br>
Display oil and gas wells drilled into the Brea Sandstone. <br>
There will be a pop-up for the wells and water sources/test sites (on.click), and an info window with the analysis results. (on.hover) <br>
Since all of the data is based in a region of Kentucky. the map will open zoomed into that area, and will not be pannable. <br>

<b>Data source</b><br>
Kentucky Geological Survey data tables. A sample of the the oil and gas well data is made available as an excel sheet. <br>

<b>Technology used</b><br>
After my data queires are built in SQL accessing various databases within the KGS system I will export the data into several excel sheets for more fine tuning. These excel workbooks will then be saved as CSV files for use with Mapbox and Leaflet APIs. I would like to include some graph and query functionality, so I will also be using jQuery and Highcharts to instantiate those functions. My final product will be hosted using GitHub Pages.