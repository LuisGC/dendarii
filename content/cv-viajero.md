---
author: yamila
slug: cv-viajero
title: Currículum viajero
comments:       false
showMeta:       false
showActions:    false
---

<style type="text/css">
    @import "//cdnjs.cloudflare.com/ajax/libs/jqueryui/1.12.1/jquery-ui.css"
    @import "//cdnjs.cloudflare.com/ajax/libs/leaflet/1.2.0/leaflet.js"
</style>


<!--
<link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/jqueryui/1.12.1/jquery-ui.css" />
<link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/leaflet/1.2.0/leaflet.js" />
-->

<div id="map" style="height: 100px"></div>

<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js" ></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/jqueryui/1.12.1/jquery-ui.js" ></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/leaflet/1.2.0/leaflet.js" ></script>
<script>
var mymap = L.map('map').setView([51.505, -0.09], 13);
L.tileLayer('//api.tiles.mapbox.com/v4/{id}/{z}/{x}/{y}.png?access_token={accessToken}', {
    attribution: 'Map data &copy; <a href="http://openstreetmap.org">OpenStreetMap</a> contributors, <a href="http://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="http://mapbox.com">Mapbox</a>',
    maxZoom: 18,
    id: 'mapbox.streets',
    accessToken: 'pk.eyJ1IjoieWFtaWxhIiwiYSI6IjUzNDE5ZDRkZjBiZjBiZDY0YTBhZjBmNmUyZGYzYTZiIn0.okLJEzGsBQ6IOgn1mhToIQ'
}).addTo(mymap);
</script>



