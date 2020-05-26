# Google Map Javascript Api integration
integration example of Maps JavaScript API and google Places API

The idea of this code is to obtain the coordinates of an address and be able to save them to consult the map later without having to permanently consult google due to the new rates of use of maps.

The maps javascript api is used to show the map and the places api to consult the address by name.

# get_data.html
This file queries the address entered in the html form through the api, in case of obtaining the coordinates it sends them via ajax to the endpoint engine / maps to save them.

* To use the api, you must obtain a key and enter it in the call to the google script

# map.html
This file contains two javascript functions createMarker and loadMap.
loadMap receives an object that contains the coordinates and the address in text format provided by google, this function calls createMarker and centers the map at the point where it places the marker.
createMarker places the marker image at the coordinates and displays the name passed by parameters.

To show several points, you would only have to place a call to loadMap within a recursive cycle with the data of the query to the database

Thanks
