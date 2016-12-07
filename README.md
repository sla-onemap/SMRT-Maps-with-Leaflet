# Using Leaflet to Display (SG Network Train Maps - SMRT)
Using leaflet.js to pan and zoom a big image

# dependencies

* leaflet

# Application Workflow
This application retrieves the huge image that's on SMRT webpage. It's not big enough to need segmentation, but it's too big to show on a page at full scale. I need to be able to read the train station text. By using Leaflet I can zoom out to get an overview of the layout, and zoom in and pan to read the text. Leaflet takes care of all the user interaction details for me.

# commands
	1) git clone https://github.com/sla-onemap/SMRT-Maps-with-Leaflet.git
	2) cd SMRT-Maps-with-Leaflet/
	3) http-server (got to your browser @ http://127.0.0.1:8080)