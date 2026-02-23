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
1. Définir la menace : acteur, campagne, famille de malware ou IOC
2. Collecter les IOCs : IPs, domaines, hashes, adresses email
3. Rechercher sur les plateformes de threat intelligence (OTX, VirusTotal, MalwareBazaar)
4. Cartographier l'infrastructure : identifier les domaines liés, IPs et patterns d'hébergement
5. Surveiller les forums et canaux dark web pour les mentions
6. Attribution si possible : établir un lien avec des acteurs ou groupes de menace connus
7. Produire un rapport de menace exploitable avec les TTPs (Tactiques, Techniques, Procédures)

---

## 💡 MITRE ATT&CK Framework

**ENG**
| Tactic | Description |
|--------|-------------|
| Reconnaissance | Gathering info before attack |
| Resource Development | Building infrastructure |
| Initial Access | Entry point into target |
| Execution | Running malicious code |
| Persistence | Maintaining foothold |
| Defense Evasion | Avoiding detection |
| Exfiltration | Stealing data |

**FR**
| Tactique | Description |
| -------- | ----------- |
| Reconnaissance | Collecte d’informations avant une attaque |
| Développement de ressources | Mise en place de l’infrastructure |
| Accès initial | Point d’entrée dans la cible |
| Exécution | Exécution de code malveillant |
| Persistance | Maintien de l’accès |
| Évasion des défenses | Contournement des mécanismes de détection |
| Exfiltration | Vol de données |


> Full framework : [attack.mitre.org](https://attack.mitre.org)

---

## 🚩 Key Red Flags / Signaux d'alerte

**ENG** 
| Red Flag | Possible Implication |
|----------|---------------------|
| IP flagged on multiple threat feeds | Active malicious infrastructure |
| Domain registered recently with privacy protection | Potential phishing or C2 |
| Hash matches known malware family | Active malware deployment |
| Actor mentioned on dark web forums | Planned or active campaign |
| Reuse of infrastructure across campaigns | Same threat actor |

**FR**
| Alerte | Implication possible |
| ------ | -------------------- |
| IP signalée sur plusieurs flux de menaces | Infrastructure malveillante active |
| Domaine récemment enregistré avec protection de la vie privée | Potentiel phishing ou serveur de commande et contrôle (C2) |
| Hash correspondant à une famille de malware connue | Déploiement actif de malware |
| Acteur mentionné sur des forums du dark web | Campagne planifiée ou en cours |
| Réutilisation d’infrastructures à travers plusieurs campagnes | Même acteur de menace |                       

---

## 💡 Tips & Good Practices / Conseils

**ENG**
- IOCs have a shelf life, always check the date of the intelligence
- Attribution is hard : never over-attribute without strong evidence
- Correlate multiple sources before drawing conclusions
- MITRE ATT&CK is your best framework for structuring TTPs
- Monitor Telegram channels, threat actors increasingly use them to leak data and communicate
- False flags are common : state-sponsored actors often mimic other groups

**FR**
- Les IOC ont une durée de validité. Vérifie toujours la date des renseignements
- L’attribution est difficile : ne surattribue jamais sans preuves solides
- Corrèle plusieurs sources avant de tirer des conclusions
- MITRE ATT&CK est le meilleur cadre pour structurer les TTP (Tactiques, Techniques, Procédures)
- Surveille les chaînes Telegram, les acteurs de menace les utilisent de plus en plus pour divulguer des données et communiquer
- Les fausses pistes sont fréquentes : les acteurs sponsorisés par des États imitent souvent d’autres groupes

---

## 🔗 Useful Resources / Ressources utiles

- [MITRE ATT&CK](https://attack.mitre.org)
- [OTX AlienVault](https://otx.alienvault.com)
- [MalwareBazaar](https://bazaar.abuse.ch)
- [Recorded Future Blog](https://www.recordedfuture.com/blog)
- [Krebs on Security](https://krebsonsecurity.com)
