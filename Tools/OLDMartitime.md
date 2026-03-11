# ⚓ Maritime OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

| Tool | Usage | Link |
|------|-------|------|
| MarineTraffic | Real-time AIS vessel tracking | [marinetraffic.com](https://www.marinetraffic.com) |
| VesselFinder | Ship tracking and history | [vesselfinder.com](https://www.vesselfinder.com) |
| FleetMon | Fleet monitoring and port activity | [fleetmon.com](https://www.fleetmon.com) |
| Equasis | Ship ownership and inspection records | [equasis.org](https://www.equasis.org) |
| IMO Global Integrated Shipping | Official IMO ship database | [gisis.imo.org](https://gisis.imo.org) |
| OpenSanctions | Sanctions lists including vessels | [opensanctions.org](https://www.opensanctions.org) |
| Windward | AI-powered maritime intelligence | [windward.ai](https://windward.ai) |
| SkyTruth | Satellite-based vessel monitoring | [skytruth.org](https://skytruth.org) |
| Global Fishing Watch | Fishing vessel activity monitoring | [globalfishingwatch.org](https://globalfishingwatch.org) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Identify the vessel — name, IMO number, MMSI number
2. Track real-time and historical positions via AIS (MarineTraffic, VesselFinder)
3. Check ownership and flag history via Equasis
4. Cross-reference with sanctions lists (OpenSanctions)
5. Identify port calls and route anomalies
6. Use satellite imagery to verify position when AIS is disabled
7. Document all findings with timestamps and screenshots

**FR**
1. Identifier le navire — nom, numéro IMO, numéro MMSI
2. Suivre les positions en temps réel et historiques via AIS (MarineTraffic, VesselFinder)
3. Vérifier la propriété et l'historique du pavillon via Equasis
4. Recouper avec les listes de sanctions (OpenSanctions)
5. Identifier les escales et anomalies de route
6. Utiliser l'imagerie satellite pour vérifier la position quand l'AIS est désactivé
7. Documenter tous les résultats avec horodatage et captures d'écran

---

## 💡 Tips & Good Practices / Conseils

- AIS can be manipulated or disabled — always cross-reference with satellite imagery
- Flag of convenience countries are often used to obscure true ownership
- IMO number is permanent and unique — it's your most reliable identifier
- Dark vessel activity (AIS off) is a major red flag for sanctions evasion
- Check ownership layers carefully — shell companies are common in maritime sector
- Port call history can reveal trade routes and business relationships

---

## 🚩 Key Red Flags / Signaux d'alerte

| Red Flag | Possible Implication |
|----------|---------------------|
| AIS disabled in open sea | Sanctions evasion, smuggling |
| Frequent flag changes | Attempt to obscure identity |
| Ship-to-ship transfers at sea | Illicit cargo transfer |
| Ownership via multiple shell companies | Money laundering |
| Calls at sanctioned ports | Sanctions violation |

---

## 🔗 Useful Resources / Ressources utiles

- [OCCRP — Maritime Investigations](https://www.occrp.org)
- [Bellingcat — Ship Tracking Guide](https://www.bellingcat.com)
- [IMO Ship Search](https://www.imo.org/en/OurWork/IIIS/Pages/GISIS.aspx)
- [OpenSanctions](https://www.opensanctions.org)
