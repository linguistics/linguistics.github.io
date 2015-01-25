---
layout: default
---
# New Students

The following resources are intended to get you acquainted with your new department, university, city, state, country, etc.

## Housing

* Map of Austin neighborhoods. Some of the highlighted regions have a short description, which you can click to view.

<div id="map" style="width: 100%; height: 400px"></div>
<a href="./new-students-map.kml" id="kml">KML</a>

<script src="//maps.google.com/maps/api/js?sensor=false"></script>
<script>
function init() {
  var map_element = document.getElementById('map');
  var map = new google.maps.Map(map_element, {
    zoom: 9,
    center: new google.maps.LatLng(30.284431, -97.740312), // Calhoun
    mapTypeId: google.maps.MapTypeId.ROADMAP,
  });

  var kml_element = document.getElementById('kml');
  var layer = new google.maps.KmlLayer(kml_element.href); // doesn't work when viewing locally
  // var layer = new google.maps.KmlLayer('http://linguistics.github.io/new-students-map.kml');
  layer.setMap(map);
}
google.maps.event.addDomListener(window, 'load', init);
</script>

* TODO: List of renters, though craigslist.org is probably your best bet if you're not in the market for buying.
* TODO: Utilities, etc., links


## Food and Drinks

* Austin Pizza: location of the annual Open House Happy Hour
* Cactus Cafe: the only place on campus that I know of to get liquor ... er, not that I take shots before class...
* Dog and Duck: the traditional Linguistics Happy Hour pub
* Hole in the Wall: the non-traditional, unofficial Happy Hour dive
* Medici: what are the odds of running into Jason Baldridge, Colin Bannard, David Beaver, John Beavers, and Steve Wechsler off-campus? Pretty high, if you're caffeinating at Medici.
* Veggie Heaven: friendly to both vegetarians and the homeless population (you'll see)
* NASSLLI 2012's [food links](http://nasslli2012.com/food)
