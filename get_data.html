<html lang="en">
	<head>
    	<meta charset="utf-8">
	</head>
	<body>
		<form method="post">
			<label for="address"></label>
			<input type="text" name="address">
			<a href="javascript:map()">Buscar</a>
		</form>
		<div id="map"></div>

		<script src="https://code.jquery.com/jquery-3.5.1.js" integrity="sha256-QWo7LDvxbWT2tbbQ97B53yJnYU3WhH/C8ycbRAkjPDc=" crossorigin="anonymous"></script>
		<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&libraries=places&callback=initMap" async defer></script>
		
		<script>
			var map;
			var service;

			function map(){
				var address = $("#address").val();

				map = new google.maps.Map(document.getElementById('map'), {zoom: 15});
				service = new google.maps.places.PlacesService(map);
				service.findPlaceFromQuery(address, (results, status) => {
					if (status === google.maps.places.PlacesServiceStatus.OK) {
							var lat = results[0].geometry.location.lat();
							var long = results[0].geometry.location.lng();
							var formatted = results[0].formatted_address;
							
							$.ajax({
								url: 'engine/maps',
								type: "POST",
								data: {
									"lat":lat,
									"long":long,
									"formatted":formatted
									},
								success: function(data){
									console.log('address coordinates obtained correctly');
									console.log(data);
								}
							}).fail( function() {
								console.log('Error while save data');
							});
		
					}else{
						console.log('the coordinates of the entered address could not be obtained');
					}
				});
			}
		</script>
		

	</body>
</html>
