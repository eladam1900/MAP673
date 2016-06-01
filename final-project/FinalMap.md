<b>User Persona</b>

The target user of this map is someone interested in the water quality of water wells in a high frack, high drilling area at shallow depths. Through using this map a user will gain access to active water wells with water analysis reports, and oil and gas wells currently producing from the Berea Sandstone. Through interacting with the map, and the wells’ pop-ups users will gain access to a specific well's reports and well documents. This can include drilling information such as tests run, casing structure, and for oil and gas wells fracking information. 

<b>Map Topic</b>

Water quality of water wells surrounding oil and gas wells drilled in the Berea Sandstone in northeastern Kentucky. 

<b>User Interaction</b>

Users will be able to click on an oil and gas well which will prompt a 2.5 mile radius around that well thus displaying only the water wells within that radius. Then a user can click on one of those wells to access its pop-up with tabular data and a URL link to access more detailed information including the water analysis reports and well documents. 

<b>Data Representation Format</b>

I will display the oil and gas and water wells as circles which will be color coded in a choropleth format based on their total depth. Oil and gas wells will be displayed using shades of purple, and water wells will be displayed using shades of blue. They will be displayed over a topographic base map. 

<b>Objectives</b> 

            •	Display currently producing Kentucky oil and gas wells drilled into the Brea Sandstone in Johnson, Greenup, and Lawrence counties, and display them according to their depth.

            •	Display active Kentucky water wells drilled in the same area as the above mentioned oil and gas wells in Johnson, Greenup, and Lawrence counties. These will also be displayed according to their depth using the same breaks as the oil and gas wells. 

            •	Provide available data and well documents for both the oil and gas and water wells in the form of a pop-up per well.

            •	Since all of the data is based in a region of Kentucky the map will open zoomed into that area, and will not be pannable. 

<b>Data source</b>

Kentucky Geological Survey data tables. http://kgs.uky.edu/kgsweb/main.asp#tabs-2
Data parameters – water wells had to have a complete location, be active, TD entered, available analysis data, and are in the three selected counties (296 – out of 560) , O/G wells – had to have a complete location, be active (not plugged or result of D&A), TD entered,  and are in the three selected counties (297 – out of 932)

<b>Technology used</b>

After my data queries are built in SQL accessing various databases within the KGS system I will export the data into several excel sheets for more fine tuning. These excel workbooks will then be saved as CSV files for use with Mapbox, and Leaflet APIs. I will use simple statistics to create the breaks for the choropleth aspect of the legend and well representation by querying the total depth field of the well data sets. My final product will be hosted using GitHub Pages.

<b>Side Notes</b>

Changes from the original idea are due to the complexity of the available analytes. It would be too misleading and presumptuous to try and make a correlation between which analytes are present at a particular water well, and tying it to a result of drilling. Several other factors would need to be taken into account before a correlation like that could be determined. These would include but are not limited to: the possibility of multiple sources contributing the amount of any particular analyte tested, the date the analysis was run compared to when the oil and gas wells in question were drilled, and the condition of the casing of both the water and oil and gas wells in question. This new map design allows users to investigate the data available without the map creator pushing them in one direction or another based on their biases. 
