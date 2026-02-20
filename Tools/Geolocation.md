# 🌍 Geolocation / IMINT OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

| Tool | Usage | Link |
|------|-------|------|
| Google Earth Pro | Geospatial analysis and terrain comparison | [earth.google.com](https://earth.google.com) |
| GeoSpy | AI-based image geolocation | [geospy.ai](https://geospy.ai) |
| SunCalc | Shadow analysis to date and locate images | [suncalc.org](https://www.suncalc.org) |
| Overpass Turbo | Advanced OpenStreetMap queries | [overpass-turbo.eu](https://overpass-turbo.eu) |
| Google Maps Street View | Ground-level visual verification | [maps.google.com](https://maps.google.com) |
| Yandex Images | Reverse image search (often better than Google) | [yandex.com/images](https://yandex.com/images) |
| Google Lens | Reverse image search and object recognition | [lens.google.com](https://lens.google.com) |
| ExifTool | Extract GPS metadata from images | [exiftool.org](https://exiftool.org) |
| PeakFinder | Mountain and landscape identification | [peakfinder.org](https://www.peakfinder.org) |
| Mapillary | Street-level crowdsourced imagery | [mapillary.com](https://www.mapillary.com) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Extract metadata from the image (ExifTool) — GPS coordinates may already be embedded
2. Analyze visual clues — vegetation, architecture, signage, vehicles, sun position
3. Run reverse image search (Google Lens, Yandex) to find the original source
4. Use SunCalc to estimate time and date based on shadows
5. Cross-reference with satellite imagery (Google Earth, Mapillary)
6. Confirm location with Street View or Overpass Turbo queries

**FR**
1. Extraire les métadonnées de l'image (ExifTool) — les coordonnées GPS peuvent déjà y figurer
2. Analyser les indices visuels — végétation, architecture, panneaux, véhicules, position du soleil
3. Lancer une recherche inversée (Google Lens, Yandex) pour trouver la source originale
4. Utiliser SunCalc pour estimer l'heure et la date via les ombres
5. Recouper avec l'imagerie satellite (Google Earth, Mapillary)
6. Confirmer la localisation via Street View ou des requêtes Overpass Turbo

---

## 💡 Tips & Good Practices / Conseils

- Always check image metadata before anything else — it saves a lot of time
- Yandex reverse image search often outperforms Google for non-Western locations
- Look for unique identifiers : license plates, shop names, road markings, utility poles
- Sun position and shadow length can pinpoint both location and time
- Document every step with annotated screenshots

---

## 🔗 Useful Resources / Ressources utiles

- [Bellingcat Geolocation Guide](https://www.bellingcat.com/resources/how-tos/2014/07/09/behind-the-lines-geolocation-guide/)
- [GeoGuessr Tips for OSINT](https://somerandomstuff1.wordpress.com/2019/02/08/geoguessr-the-top-tips-tricks-and-techniques/)
- [SunCalc Documentation](https://www.suncalc.org)
