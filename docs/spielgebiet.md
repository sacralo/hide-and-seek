# 🗺️ Spielgebiet

## Das Spielfeld

<div id="karte" style="height: 500px; width: 100%; border-radius: 8px;"></div>

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>

<script>
  var map = L.map('karte').setView([51.45, 7.05], 9); // Zentrum: Ruhrgebiet

  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '&copy; OpenStreetMap-Mitwirkende'
  }).addTo(map);

  // Spielgebiet als Polygon markieren
  var spielgebiet = L.polygon([
    [51.55, 6.85],
    [51.55, 7.55],
    [51.30, 7.55],
    [51.30, 6.85]
  ], {color: 'red', fillOpacity: 0.1}).addTo(map);

  // Marker für wichtige Orte
  L.marker([51.4556, 7.0116]).addTo(map)
    .bindPopup('Startpunkt Essen');
</script>
<br>
Hier wird das offizielle Spielgebiet beschrieben.

### Grenzen

**Nördliche Grenze:** Wird noch festgelegt
**Südliche Grenze:** Wird noch festgelegt
**Östliche Grenze:** Wird noch festgelegt
**Westliche Grenze:** Wird noch festgelegt

---

## 🚫 Nicht betretbare Bereiche

Folgende Bereiche gehören nicht zum Spielfeld:

* Privatgrundstücke
* gefährliche Bereiche
* gesperrte Bereiche
* Bereiche, die ausdrücklich von der Spielleitung ausgeschlossen wurden

---

## 📍 Karte

*Hier wird später eine Karte des Spielgebiets eingefügt.*

---

## ⚠️ Wichtig

Das Spielgebiet kann während der Vorbereitung noch geändert werden.

Die auf dieser Seite veröffentlichte Version gilt als aktuell.
