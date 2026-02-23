# ✈️ Aviation OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

| Tool | Usage | Link |
|------|-------|------|
| FlightRadar24 | Real-time ADS-B flight tracking | [flightradar24.com](https://www.flightradar24.com) |
| FlightAware | Flight tracking and history | [flightaware.com](https://www.flightaware.com) |
| ADS-B Exchange | Unfiltered global ADS-B tracking | [adsbexchange.com](https://www.adsbexchange.com) |
| OpenSky Network | Open ADS-B data and API | [opensky-network.org](https://opensky-network.org) |
| RadarBox | Flight tracking with history | [radarbox.com](https://www.radarbox.com) |
| FAA Aircraft Registry | US aircraft ownership database | [registry.faa.gov](https://registry.faa.gov) |
| EASA | European aviation authority database | [easa.europa.eu](https://www.easa.europa.eu) |
| Rzjets | Aircraft ownership and history | [rzjets.net](https://rzjets.net) |
| JetPhotos | Aircraft photo database | [jetphotos.com](https://www.jetphotos.com) |
| OpenCorporates | Identify shell companies owning aircraft | [opencorporates.com](https://opencorporates.com) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Identify the aircraft — tail number (registration), ICAO hex code or flight number
2. Track real-time and historical positions (FlightRadar24, ADS-B Exchange)
3. Identify the registered owner via national aviation registries (FAA, EASA)
4. Cross-reference ownership with corporate registries — shell companies are common
5. Analyze flight patterns — unusual routes, private airstrips, border crossings
6. Cross-reference with sanctions lists for owner and operator
7. Use ADS-B Exchange for unfiltered data — some operators request removal from commercial trackers
8. Document findings with screenshots and timestamps

**FR**
1. Identifier l'aéronef — immatriculation, code hex ICAO ou numéro de vol
2. Suivre les positions en temps réel et historiques (FlightRadar24, ADS-B Exchange)
3. Identifier le propriétaire enregistré via les registres nationaux (FAA, EASA)
4. Recouper la propriété avec les registres d'entreprises — les sociétés écrans sont courantes
5. Analyser les patterns de vol — routes inhabituelles, aérodromes privés, franchissements de frontières
6. Recouper avec les listes de sanctions pour le propriétaire et l'opérateur
7. Utiliser ADS-B Exchange pour des données non filtrées — certains opérateurs demandent leur retrait des trackers commerciaux
8. Documenter les résultats avec captures d'écran et horodatage

---

## 💡 Tips & Good Practices / Conseils

- ADS-B Exchange is critical — it doesn't honor opt-out requests unlike FlightRadar24
- Private jets are often registered under shell companies — dig into the ownership layers
- Tail numbers can be changed — cross-reference with ICAO hex code which is permanent
- Flight history gaps can be as revealing as the flights themselves
- Private airstrips don't always appear on commercial trackers — check satellite imagery
- Sanctioned individuals frequently use private aviation to bypass border controls

---

## 🚩 Key Red Flags / Signaux d'alerte

| Red Flag | Possible Implication |
|----------|---------------------|
| Aircraft removed from commercial trackers | Deliberate concealment attempt |
| Ownership via multiple shell companies | Obscured beneficial owner |
| Frequent flights to secrecy jurisdictions | Sanctions evasion or illicit finance |
| Transponder disabled mid-flight | Active concealment |
| Aircraft appears on sanctions lists | Direct sanctions exposure |

---

## 🔗 Useful Resources / Ressources utiles

- [ADS-B Exchange](https://www.adsbexchange.com)
- [FAA Aircraft Registry](https://registry.faa.gov)
- [Bellingcat — Aviation Investigations](https://www.bellingcat.com)
- [OCCRP — Private Jet Tracking](https://www.occrp.org)
