# Courneau

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

## Emplacement
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.3.1/dist/leaflet.css" integrity="sha512-Rksm5RenBEKSKFjgI3a41vrjkw4EVPlJ3+OiI65vTjIdo9brlAacEuKOiQ5OFh7cOI1bkDwLqdLw3Zg0cRJAAQ==" crossorigin="" />
<style type="text/css">
#map{ /* la carte DOIT avoir une hauteur sinon elle n'apparaît pas */
    height:400px;
}
</style>
<div id="map"></div>

<!-- Fichiers Javascript -->
<script src="https://unpkg.com/leaflet@1.3.1/dist/leaflet.js" integrity="sha512-/Nsx9X4HebavoBvEBuyp3I7od5tA0UzAxs+j83KgC8PU0kgB4XiK4Lfe4y4cgBtaRJQEIFCW+oC506aPT2L1zw==" crossorigin=""></script>
<script type="text/javascript">
// On initialise la latitude et la longitude de Paris (centre de la carte)
const lat = 43.2172;
const lon = 3.0187;
// Fonction d'initialisation de la carte
const initMap = () => {
    // Créer l'objet "macarte" et l'insèrer dans l'élément HTML qui a l'ID "map"
    const map = L.map('map').setView([lat, lon], 13);
    // Leaflet ne récupère pas les cartes (tiles) sur un serveur par défaut. Nous devons lui préciser où nous souhaitons les récupérer. Ici, openstreetmap.fr
    L.tileLayer('https://{s}.tile.openstreetmap.fr/osmfr/{z}/{x}/{y}.png', {
        // Il est toujours bien de laisser le lien vers la source des données
        attribution: 'données © <a href="//osm.org/copyright">OpenStreetMap</a>/ODbL - rendu <a href="//openstreetmap.fr">OSM France</a>',
        minZoom: 1,
        maxZoom: 20
    }).addTo(map);
}
window.onload = initMap
</script>

## [Nous contacter](mailto:courneau-location@gmail.com)

