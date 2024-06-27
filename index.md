## Présentation

Située sur la Commune de Narbonne,
à proximité du Canal du Midi,
10 min du centre-ville de Narbonne et 25 minutes des plages,
cette grande maison de famille est idéale pour un séjour en famille ou entre amis.

### Le logement

La propriété peut accueillir 8 personnes, et dispose :

* D’une salle à manger,
* D’une cuisine,
* D’un salon,
* De quatre chambres
* De deux salle de bains,
* De deux toilettes.

A l’extérieur, vous pourrez profiter de la piscine et du parc verdoyant.  
Vous pourrez également stationner vos véhicules sur la propriété.

Du matériel de puériculture peut être mis à votre disposition sur demande :

* Lit parapluie et son matelas
* Chaise haute
* Petite baignoire

{% include carousel.html height="200" unit="px" duration="7" %}

## Emplacement

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.3.1/dist/leaflet.css" integrity="sha512-Rksm5RenBEKSKFjgI3a41vrjkw4EVPlJ3+OiI65vTjIdo9brlAacEuKOiQ5OFh7cOI1bkDwLqdLw3Zg0cRJAAQ==" crossorigin="" />
<style lang="css">
#map{height:400px;}
</style>
<div id="map"></div>

<script src="https://unpkg.com/leaflet@1.3.1/dist/leaflet.js" integrity="sha512-/Nsx9X4HebavoBvEBuyp3I7od5tA0UzAxs+j83KgC8PU0kgB4XiK4Lfe4y4cgBtaRJQEIFCW+oC506aPT2L1zw==" crossorigin=""></script>
<script lang="js">
const lat = 43.21997;
const lon = 3.01554;

const initMap = () => {
    const map = L.map('map').setView([lat, lon], 13);
    L.tileLayer('https://{s}.tile.openstreetmap.fr/osmfr/{z}/{x}/{y}.png', {
        attribution: 'données © <a href="//osm.org/copyright">OpenStreetMap</a>/ODbL - rendu <a href="//openstreetmap.fr">OSM France</a>',
        minZoom: 1,
        maxZoom: 20
    }).addTo(map);
    L.marker([lat, lon]).addTo(map);
};
window.onload = initMap
</script>

## [Nous contacter](mailto:courneau-location@gmail.com)

