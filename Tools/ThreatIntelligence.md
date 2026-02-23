# 🎯 Threat Intelligence OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

| Tool | Usage | Usages | Link |
|------|-------|--------|------|
| IntelX | Search dark web, forums, paste sites | Recherches sur le darkweb, ses forums et ses paste sites | [intelx.io](https://intelx.io) |
| Shodan | Identify exposed infrastructure and IoT | Identifie les infrastructures et objets connectés exposés | [shodan.io](https://www.shodan.io) |
| VirusTotal | File, URL and domain reputation analysis | Analyse de la réputations de fichiers, URL et noms de domaine | [virustotal.com](https://www.virustotal.com) |
| MalwareBazaar | Malware samples and IOC database | Échantillons de malware et bases de données d’indicateurs de compromission | [bazaar.abuse.ch](https://bazaar.abuse.ch) |
| URLScan | Website scanning and behavior analysis | Analyse du comportement des sites web et scan de sécurité | [urlscan.io](https://urlscan.io) |
| AbuseIPDB | IP reputation and abuse reporting | Analyse de la réputation des adresses IP et signalement des abus | [abuseipdb.com](https://www.abuseipdb.com) |
| OTX AlienVault | Open threat intelligence community | Communauté ouverte de renseignement sur les menaces | [otx.alienvault.com](https://otx.alienvault.com) |
| MISP | Threat intelligence sharing platform | Plateforme de partage de renseignement sur les menaces | [misp-project.org](https://www.misp-project.org) |
| Maltego | Actor and infrastructure mapping | Cartographie des acteurs et des infrastructures | [maltego.com](https://www.maltego.com) |
| Recorded Future | Real-time threat intelligence | Renseignement sur les menaces en temps réel | [recordedfuture.com](https://www.recordedfuture.com) |
| DarkBeast | Dark web monitoring and search | Veille et recherche sur le Dark Web |  [darkbeast.io](https://darkbeast.io) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Define the threat — actor, campaign, malware family or IOC
2. Collect IOCs — IPs, domains, hashes, email addresses
3. Search threat intelligence platforms (OTX, VirusTotal, MalwareBazaar)
4. Map infrastructure — identify related domains, IPs and hosting patterns
5. Monitor dark web forums and channels for mentions
6. Attribute if possible — link to known threat actors or groups
7. Produce an actionable threat report with TTPs (Tactics, Techniques, Procedures)

**FR**
1. Définir la menace — acteur, campagne, famille de malware ou IOC
2. Collecter les IOCs — IPs, domaines, hashes, adresses email
3. Rechercher sur les plateformes de threat intelligence (OTX, VirusTotal, MalwareBazaar)
4. Cartographier l'infrastructure — identifier les domaines liés, IPs et patterns d'hébergement
5. Surveiller les forums et canaux dark web pour les mentions
6. Attribuer si possible — lier à des acteurs ou groupes de menace connus
7. Produire un rapport de menace exploitable avec les TTPs (Tactiques, Techniques, Procédures)

---

## 💡 MITRE ATT&CK Framework

| Tactic | Description |
|--------|-------------|
| Reconnaissance | Gathering info before attack |
| Resource Development | Building infrastructure |
| Initial Access | Entry point into target |
| Execution | Running malicious code |
| Persistence | Maintaining foothold |
| Defense Evasion | Avoiding detection |
| Exfiltration | Stealing data |

> Full framework : [attack.mitre.org](https://attack.mitre.org)

---

## 🚩 Key Red Flags / Signaux d'alerte

| Red Flag | Possible Implication |
|----------|---------------------|
| IP flagged on multiple threat feeds | Active malicious infrastructure |
| Domain registered recently with privacy protection | Potential phishing or C2 |
| Hash matches known malware family | Active malware deployment |
| Actor mentioned on dark web forums | Planned or active campaign |
| Reuse of infrastructure across campaigns | Same threat actor |

---

## 💡 Tips & Good Practices / Conseils

- IOCs have a shelf life — always check the date of the intelligence
- Attribution is hard — never over-attribute without strong evidence
- Correlate multiple sources before drawing conclusions
- MITRE ATT&CK is your best framework for structuring TTPs
- Monitor Telegram channels — threat actors increasingly use them to leak data and communicate
- False flags are common — state-sponsored actors often mimic other groups

---

## 🔗 Useful Resources / Ressources utiles

- [MITRE ATT&CK](https://attack.mitre.org)
- [OTX AlienVault](https://otx.alienvault.com)
- [MalwareBazaar](https://bazaar.abuse.ch)
- [Recorded Future Blog](https://www.recordedfuture.com/blog)
- [Krebs on Security](https://krebsonsecurity.com)
