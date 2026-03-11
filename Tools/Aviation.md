# ✈️ Aviation OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

### Flight Tracking & ADS-B

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| FlightRadar24 | Real-time ADS-B flight tracking — most widely used commercial tracker | Suivi ADS-B des vols en temps réel — tracker commercial le plus utilisé | FlightAware, RadarBox | Freemium | 🇸🇪 Sweden | [flightradar24.com](https://www.flightradar24.com) |
| ADS-B Exchange | Unfiltered global ADS-B tracking — does NOT honor opt-out requests, critical for sensitive targets | Suivi ADS-B mondial non filtré — ne prend PAS en compte les demandes de suppression, essentiel pour les cibles sensibles | FlightRadar24 | Freemium | 🇺🇸 USA | [adsbexchange.com](https://www.adsbexchange.com) |
| FlightAware | Flight tracking with extended history and departure/arrival data | Suivi de vols avec historique étendu et données de départ/arrivée | FlightRadar24, RadarBox | Freemium | 🇺🇸 USA | [flightaware.com](https://www.flightaware.com) |
| OpenSky Network | Open-source ADS-B data with academic API access — good for bulk historical queries | Données ADS-B open source avec API académique — utile pour les requêtes historiques en masse | ADS-B Exchange | Free | 🇨🇭 Switzerland | [opensky-network.org](https://opensky-network.org) |
| RadarBox | Flight tracking with real-time alerts and airport data | Suivi de vols avec alertes temps réel et données aéroportuaires | FlightRadar24 | Freemium | 🇵🇹 Portugal | [radarbox.com](https://www.radarbox.com) |

### Aircraft Ownership & Registries

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| FAA Aircraft Registry | US aircraft ownership and registration database — searchable by tail number or owner name | Base de données américaine des propriétaires et immatriculations d'aéronefs | EASA, national registries | Free | 🇺🇸 USA | [registry.faa.gov](https://registry.faa.gov) |
| EASA | European Union Aviation Safety Agency — aircraft type certificates and safety data | Agence Européenne de la Sécurité Aérienne — certificats de type et données de sécurité | FAA, national registries | Free | 🇪🇺 Europe | [easa.europa.eu](https://www.easa.europa.eu) |
| Rzjets | Aircraft ownership history and transaction records — strong on business aviation | Historique de propriété et transactions pour les aéronefs — fort en aviation d'affaires | JetPhotos, FAA Registry | Freemium | 🌐 International | [rzjets.net](https://rzjets.net) |
| JetPhotos | Aircraft photo database — identify aircraft type, livery and physical characteristics | Base de données de photos d'aéronefs — identifier le type, la livrée et les caractéristiques physiques | Airliners.net | Free | 🌐 International | [jetphotos.com](https://www.jetphotos.com) |
| OpenSanctions | Sanctions lists including aircraft and aviation companies | Listes de sanctions incluant les aéronefs et compagnies d'aviation | OFAC SDN | Free | 🇩🇪 Germany | [opensanctions.org](https://www.opensanctions.org) |
| OpenCorporates | Identify shell companies owning aircraft — follow the corporate ownership chain | Identifier les sociétés écrans propriétaires d'aéronefs — suivre la chaîne de propriété | Orbis, national registries | Free | 🇬🇧 UK | [opencorporates.com](https://opencorporates.com) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Identify the aircraft — tail number (registration), ICAO hex code or flight number
2. Track real-time and historical positions (FlightRadar24, ADS-B Exchange)
3. For sensitive targets, always use ADS-B Exchange — it does not honor opt-out requests
4. Identify the registered owner via national aviation registries (FAA, EASA)
5. Cross-reference ownership with corporate registries — shell companies are common
6. Analyze flight patterns — unusual routes, private airstrips, border crossings, diversion airports
7. Cross-reference owner, operator and all linked entities with sanctions lists
8. For gaps in ADS-B data, cross-check with satellite imagery and airport logs if accessible
9. Document all findings with screenshots and timestamps

**FR**
1. Identifier l'aéronef — immatriculation, code hex ICAO ou numéro de vol
2. Suivre les positions en temps réel et historiques (FlightRadar24, ADS-B Exchange)
3. Pour les cibles sensibles, toujours utiliser ADS-B Exchange — il ne prend pas en compte les demandes de suppression
4. Identifier le propriétaire enregistré via les registres nationaux (FAA, EASA)
5. Recouper la propriété avec les registres d'entreprises — les sociétés écrans sont courantes
6. Analyser les patterns de vol — routes inhabituelles, aérodromes privés, franchissements de frontières, aéroports de déroutement
7. Recouper propriétaire, opérateur et entités liées avec les listes de sanctions
8. En cas de lacunes ADS-B, recouper avec l'imagerie satellite et les logs aéroportuaires si accessibles
9. Documenter tous les résultats avec captures d'écran et horodatage

---

## 🚩 Key Red Flags / Signaux d'alerte

| Red Flag | Possible Implication |
|----------|---------------------|
| Aircraft removed from commercial trackers | Deliberate concealment attempt — use ADS-B Exchange |
| Ownership through multiple shell companies | Obscured beneficial owner |
| Frequent flights to secrecy jurisdictions | Sanctions evasion, illicit finance or capital flight |
| Transponder disabled mid-flight | Active concealment of route or destination |
| Aircraft or owner appears on sanctions lists | Direct sanctions exposure |
| Frequent use of private airstrips not in databases | Off-grid operations |
| Tail number recently changed | Identity obfuscation — cross-reference ICAO hex code |

---

## 💡 Tips & Good Practices / Conseils

- ADS-B Exchange is critical for sensitive investigations — it does not honor opt-out requests unlike FlightRadar24
- Private jets are frequently registered under shell companies — always dig into the ownership layers
- The ICAO hex code is permanent and unique — use it as a stable identifier when tail numbers change
- Flight history gaps can be as revealing as the flights themselves — note when and where coverage disappears
- Private airstrips don't appear on commercial trackers — check satellite imagery for runway activity
- Sanctioned individuals frequently use private aviation to bypass commercial border controls
- Cross-reference aviation investigations with maritime tracking — same evasion networks often use both

---

## 🔗 Useful Resources / Ressources utiles

- [ADS-B Exchange](https://www.adsbexchange.com)
- [FAA Aircraft Registry](https://registry.faa.gov)
- [Bellingcat — Aviation OSINT](https://www.bellingcat.com)
- [OCCRP — Private Jet Tracking](https://www.occrp.org)
- [OpenSanctions](https://www.opensanctions.org)
