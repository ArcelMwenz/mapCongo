# mapCongo
<!DOCTYPE html>
<html lang="fr">
<head>
		<meta name="viewport" content="initial-scale=1.0, user-scalable=no"/>
		<meta charset="UTF-8" />
		<title>MapCongo</title>
		<style>
		#mymap {
				width:100%;
				height:700%;
			
		}
		
		</style>
		<script  type="text/javascript" src="http://maps.google.com/maps/api/js?sensor=false"></script>
		<script  type="text/javascript" >
		function init(){
				var latlng = new google.maps.LatLng(-10.876389000000000000, 26.596944000000007000);
				var mapDiv= document.getElementById("mymap");
				var mapOptions = {
						center : new google.maps.MapTypeId.ROADMAP
						center: latlng,
						zoom: 19,
				};
				var map = new google.maps.Map(mapDiv, mapOptions);
				
		}
		window.onload = init;
		</script>
</head>
<body>
			<h2>Kambove</h2>
			<div id = "mymap"></div>
			
</body>
</html>
