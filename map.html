<html lang="en">
	<head>
    	<meta charset="utf-8">
	</head>
	<body>
		
		<div id="map"></div>


		<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&libraries=places&callback=initMap" async defer></script>
		
		<script>
			// <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&libraries=places">

			var map;
			var infowindow;


			function createMarker(place,title) {
				var myLatLng = {lat: parseFloat(place.lat), lng: parseFloat(place.long)};
				var marker = new google.maps.Marker({
					map: map,
					position: myLatLng,
					icon:'images/markers/marker.png',
				});

				google.maps.event.addListener(marker, 'click', function() {
					infowindow.setContent(title+' ('+place.formatted+')');
					infowindow.open(map, this);
				});
			}


			function loadMap(item) { //receive a object 'item'
				infowindow = new google.maps.InfoWindow();
				
				//hidden map shops
				var styles = [
					{
					"elementType": "labels.icon",
					"stylers": [
						{
						"visibility": "off"
						}
					]
					},
				];

				var styledMap = new google.maps.StyledMapType(styles, {name: "Styled Map"});  
				
				map = new google.maps.Map(document.getElementById('map'), {zoom: 15});

				
				//hidden map shops apply
				map.mapTypes.set('map_style', styledMap);
				map.setMapTypeId('map_style');	  


				if(item){
					createMarker(item,'item on the map');
					map.setCenter({
						lat: parseFloat(item.lat),
						lng: parseFloat(item.long)
					});
				}else{
					console.log("no position data");
				}

			}
		</script>

	</body>
</html>



	