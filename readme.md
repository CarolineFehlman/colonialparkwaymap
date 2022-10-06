<h3 >
Colonial Parkway route of the Historic Triangle
</h3>

<h5 >
by Caroline Fehlman
</h5>




Introduction
---
In this web map the route of the Colonial Parkway from Jamestown Beach  to Yorktown Beach, VA can be viewed. Additionally, the map provides information on the background of the Colonial Parkway, Historic Triangle, and each of the location spots indicated on the map, all of which are home to Williamsburg, Jamestown, and Yorktown Virginia.

Major Functions
---

The major functions used in the html document to create the web map used the Leaflet library. The functions had the purpose of styling for the route feature, such as the color and size. Additionally, a function was created to add a popup for the location points. The functions start off with if statements to determine the type of feature the function should focus on, from there functions were made for styling and popups.


Libraries
---

The libraries that were used in the formation of the web map include Leaflet, Jquery, and ajax. The Leaflet library was used for the purpose of creating and adding map elements to the html document. The Jquery library was used to simplfy coding in a html document when pertaining to styling and functions. Additionally, the ajax library is a part of the Jquery library and is used for updating a webpage and obtaining data from a server. 


Data Sources
---
The data sources for this map was initially obtained from [Google Maps](https://www.google.com/maps/dir/Jamestown+Beach,+Virginia+23185/Yorktown+Beach,+Virginia/@37.2649347,-76.6842488,12.73z/data=!4m24!4m23!1m15!1m1!1s0x89b0602fcd41d013:0x5de0ac448b1f5fa0!2m2!1d-76.7887446!2d37.2254826!3m4!1m2!1d-76.7617315!2d37.2184804!3s0x89b061c396db9571:0x7b1a35025380af0b!3m4!1m2!1d-76.6987925!2d37.2761644!3s0x89b0890543d6bf3d:0x74a0b1ac6331c121!1m5!1m1!1s0x89b080f9b69e9f95:0x13d7752d4ab5067c!2m2!1d-76.5052845!2d37.2361326!3e0). This is where the desired locations and route were chosen. The link was then copied and pasted into the Maps to GPX website tool. From there, additional points were added to the map and then the data was exported as a GeoJSON file.
