# ⚓ Maritime OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

### Vessel Tracking & AIS

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| MarineTraffic | Real-time and historical AIS vessel tracking — largest publicly accessible maritime database | Suivi AIS des navires en temps réel et historique — plus grande base de données maritime accessible publiquement | VesselFinder, FleetMon | Freemium | 🇬🇷 Greece | [marinetraffic.com](https://www.marinetraffic.com) |
| VesselFinder | Ship tracking and voyage history — alternative source when MarineTraffic data is limited | Suivi des navires et historique de voyage — source alternative quand les données MarineTraffic sont limitées | MarineTraffic, FleetMon | Freemium | 🇧🇬 Bulgaria | [vesselfinder.com](https://www.vesselfinder.com) |
| FleetMon | Fleet monitoring and port activity — strong on commercial shipping intelligence | Surveillance de flottes et activité portuaire — fort en intelligence sur le transport commercial | MarineTraffic | Freemium | 🇩🇪 Germany | [fleetmon.com](https://www.fleetmon.com) |
| RadarBox (Maritime) | Additional AIS coverage and vessel tracking | Couverture AIS supplémentaire et suivi de navires | MarineTraffic | Freemium | 🇬🇧 UK | [radarbox.com](https://www.radarbox.com) |
| Global Fishing Watch | Fishing vessel monitoring and dark vessel detection using AIS and satellite data | Surveillance des navires de pêche et détection de navires fantômes via AIS et données satellite | MarineTraffic, SkyTruth | Free | 🌐 International | [globalfishingwatch.org](https://globalfishingwatch.org) |
| SkyTruth | Satellite-based vessel monitoring — detects vessels with AIS disabled using SAR imagery | Surveillance des navires par satellite — détecte les navires avec AIS désactivé via imagerie SAR | Global Fishing Watch, Windward | Freemium | 🇺🇸 USA | [skytruth.org](https://skytruth.org) |
| Windward | AI-powered maritime intelligence — behavioral profiling and anomaly detection | Intelligence maritime par IA — profilage comportemental et détection d'anomalies | SkyTruth | Paid | 🇮🇱 Israel | [windward.ai](https://windward.ai) |

### Ownership, Registries & Inspection

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| Equasis | Ship ownership, flag history, inspection records and detention history — official IMO partner | Propriété des navires, historique de pavillon, inspections et détentions — partenaire officiel de l'OMI | IMO GISIS | Free | 🇫🇷 France | [equasis.org](https://www.equasis.org) |
| IMO GISIS | Official IMO ship database — registered names, IMO numbers, flag states | Base de données officielle des navires de l'OMI — noms enregistrés, numéros IMO, États du pavillon | Equasis | Free | 🌐 International | [gisis.imo.org](https://gisis.imo.org) |
| OpenSanctions | Sanctions lists including vessels and shipping companies | Listes de sanctions incluant les navires et compagnies maritimes | OFAC SDN, EU Sanctions Map | Free | 🇩🇪 Germany | [opensanctions.org](https://www.opensanctions.org) |
| OpenCorporates | Identify shell companies that own vessels — follow the ownership chain | Identifier les sociétés écrans propriétaires de navires — suivre la chaîne de propriété | Orbis, national registries | Free | 🇬🇧 UK | [opencorporates.com](https://opencorporates.com) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Identify the vessel — name, IMO number (permanent), MMSI number (changeable)
2. Track real-time and historical AIS positions (MarineTraffic, VesselFinder)
3. Check ownership, flag history and inspection records via Equasis
4. Trace ownership structure — identify operating company, registered owner and beneficial owner
5. Cross-reference with sanctions lists (OpenSanctions, OFAC)
6. Identify port calls and route anomalies — unusual stops, restricted ports
7. Use satellite imagery to verify position when AIS is disabled or gaps appear
8. Document all findings with timestamps and screenshots

**FR**
1. Identifier le navire — nom, numéro IMO (permanent), numéro MMSI (modifiable)
2. Suivre les positions AIS en temps réel et historiques (MarineTraffic, VesselFinder)
3. Vérifier la propriété, l'historique du pavillon et les inspections via Equasis
4. Tracer la structure de propriété — identifier la société d'exploitation, le propriétaire enregistré et le bénéficiaire effectif
5. Recouper avec les listes de sanctions (OpenSanctions, OFAC)
6. Identifier les escales et anomalies de route — arrêts inhabituels, ports sous sanctions
7. Utiliser l'imagerie satellite pour vérifier la position quand l'AIS est désactivé ou présente des lacunes
8. Documenter tous les résultats avec horodatage et captures d'écran

---

## 🚩 Key Red Flags / Signaux d'alerte

| Red Flag | Possible Implication |
|----------|---------------------|
| AIS disabled in open sea | Active sanctions evasion or smuggling operation |
| Frequent flag changes | Deliberate attempt to obscure vessel identity |
| Ship-to-ship transfers at sea (STS) | Illicit cargo transfer — oil, weapons, controlled goods |
| Ownership through multiple offshore shell companies | Obscured beneficial owner — money laundering risk |
| Port calls at sanctioned ports | Direct sanctions violation |
| AIS position inconsistent with satellite imagery | Deliberate location spoofing |
| Vessel renamed multiple times | Identity obfuscation — cross-reference with IMO number |

---

## 💡 Tips & Good Practices / Conseils

- The IMO number is permanent and unique — it is your most reliable vessel identifier regardless of name or flag changes
- AIS can be disabled, manipulated or spoofed — always cross-reference with satellite imagery for high-stakes investigations
- Flag of convenience countries (Panama, Marshall Islands, Liberia) are frequently used to obscure true ownership
- Dark vessel activity (AIS off) is a major red flag — particularly in Persian Gulf, Red Sea and Black Sea regions
- Ownership layers commonly involve shell companies in Marshall Islands, Liberia and the BVI
- Port call history reveals trade routes, business relationships and behavioral patterns over time
- Global Fishing Watch detects dark vessels and IUU (Illegal, Unreported, Unregulated) fishing using SAR imagery

---

## 🔗 Useful Resources / Ressources utiles

- [OCCRP — Maritime Investigations](https://www.occrp.org)
- [Bellingcat — Ship Tracking Guide](https://www.bellingcat.com)
- [IMO Ship Search](https://www.imo.org)
- [OpenSanctions](https://www.opensanctions.org)
- [Global Fishing Watch](https://globalfishingwatch.org)
