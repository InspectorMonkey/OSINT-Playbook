# 🎯 Threat Intelligence OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

### IOC Analysis & Reputation

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| VirusTotal | File, URL and domain reputation analysis (70+ antivirus engines and threat intel feeds) | Analyse de réputation de fichiers, URL et domaines (70+ moteurs antivirus et flux de renseignement) | URLScan, OTX | Free (Enterprise paid) | 🇺🇸 USA | [virustotal.com](https://www.virustotal.com) |
| URLScan | Website scanning and behavioral analysis (screenshots, DOM, request logs, indicators) | Analyse comportementale de sites web (captures d'écran, DOM, logs des requêtes, indicateurs) | VirusTotal, AnyRun | Free | 🇩🇪 Germany | [urlscan.io](https://urlscan.io) |
| AbuseIPDB | IP reputation database and community-driven abuse reporting | Base de réputation IP et signalement des abus communautaire | GreyNoise, Criminal IP | Free | 🇺🇸 USA | [abuseipdb.com](https://www.abuseipdb.com) |
| MalwareBazaar | Malware sample repository and IOC database by Abuse.ch | Dépôt d'échantillons de malware et base IOC par Abuse.ch | VirusTotal, ANY.RUN | Free | 🇨🇭 Switzerland | [bazaar.abuse.ch](https://bazaar.abuse.ch) |
| OTX AlienVault | Open threat intelligence sharing community — pulses, IOCs and collaborative analysis | Communauté ouverte de partage de renseignement sur les menaces —(pulses, IOCs et analyse collaborative) | MISP, Pulsedive | Free | 🇺🇸 USA | [otx.alienvault.com](https://otx.alienvault.com) |
| Pulsedive | Community threat intelligence with MITRE ATT&CK enrichment and IOC correlation | Renseignement sur les menaces communautaire avec enrichissement MITRE ATT&CK et corrélation IOC | OTX, Shodan | Freemium | 🇺🇸 USA | [pulsedive.com](https://pulsedive.com) |
| ThreatBook | Intelligence-driven threat detection and analysis with deep APAC threat actor coverage | Détection et analyse de menaces pilotées par le renseignement : couverture approfondie des acteurs APAC | OTX, Pulsedive | Freemium | 🇨🇳 China | [threatbook.io](https://threatbook.io) |
| ANY.RUN | Interactive online malware analysis sandbox, real-time behavioral analysis | Sandbox d'analyse de malware interactive en ligne, analyse comportementale en temps réel | Cuckoo Sandbox, VirusTotal | Freemium | 🇪🇪 Estonia | [any.run](https://any.run) |

### Infrastructure Scanning & Threat Mapping

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| Shodan | Identify exposed infrastructure and IoT (powerful for C2 server hunting) | Identifier les infrastructures et IoT exposés (puissant pour la chasse aux serveurs C2) | Censys, ZoomEye | Freemium | 🇺🇸 USA | [shodan.io](https://www.shodan.io) |
| Censys | Internet infrastructure scanning with deep certificate and TLS analysis | Scan d'infrastructures internet avec analyse approfondie des certificats et TLS | Shodan, ZoomEye | Freemium | 🇺🇸 USA | [censys.io](https://censys.io) |
| ZoomEye | Chinese cyberspace mapping, useful for tracking infrastructure operated from China | Cartographie du cyberespace chinois, utile pour suivre les infrastructures opérées depuis la Chine | Shodan, FOFA | Freemium | 🇨🇳 China | [zoomeye.ai](https://www.zoomeye.ai) |
| FOFA | Cyberspace asset mapping with favicon hash and TLS pivoting (strong APAC coverage) | Cartographie des actifs du cyberespace avec pivoting favicon et TLS (forte couverture APAC) | Shodan, Censys | Freemium | 🇨🇳 China | [fofa.info](https://fofa.info) |
| GreyNoise | Distinguish malicious scanning traffic from benign internet noise (IP qualification) | Distinguer le trafic de scan malveillant du bruit internet bénin (qualification des IPs) | AbuseIPDB, Criminal IP | Freemium | 🇺🇸 USA | [greynoise.io](https://www.greynoise.io) |
| Onyphe | French cyber threat intelligence combining passive DNS, scan data and threat feeds | Cyber threat intelligence français combinant DNS passif, données de scan et flux de menaces | Shodan, LeakIX | Freemium | 🇫🇷 France | [onyphe.io](https://www.onyphe.io) |
| LeakIX | Real-time detection of exposed services and active data leaks (European infrastructure focus) | Détection en temps réel des services exposés et fuites actives (focus infrastructure européenne) | Shodan, FullHunt | Freemium | 🇪🇺 Europe | [leakix.net](https://leakix.net) |
| Criminal IP | AI-powered IP threat intelligence with real-time risk scoring and VPN/proxy/Tor detection | Renseignement sur les menaces IP par IA avec scoring de risque temps réel | GreyNoise, AbuseIPDB | Freemium | 🇰🇷 South Korea | [criminalip.io](https://www.criminalip.io) |
| FullHunt | External attack surface discovery and continuous exposure monitoring | Découverte de la surface d'attaque externe et surveillance continue des expositions | Censys, Netlas | Freemium | 🌐 International | [fullhunt.io](https://fullhunt.io) |
| SynapsInt | Unified OSINT search with multi-pivot: Domain / IP / ASN / SSL / Email / Phone | Moteur OSINT unifié avec pivots multiples : Domaine / IP / ASN / SSL / Email / Téléphone | Maltego, SpiderFoot | Freemium | 🌐 International | [synapsint.com](https://synapsint.com) |
| Quake 360 | Cyberspace mapping by Qihoo 360, specialized in ICS/SCADA and industrial systems | Cartographie du cyberespace par Qihoo 360, spécialisé dans les systèmes ICS/SCADA et industriels | Shodan, FOFA | Freemium | 🇨🇳 China | [quake.360.net](https://quake.360.net) |
| Netlas | Internet-wide scanning with regex search, temporal querying and Maltego integration | Scanner internet avec recherche regex, requêtage temporel et intégration Maltego | Shodan, Censys | Freemium (50 req/day free) | 🌐 International | [app.netlas.io](https://app.netlas.io) |

### Threat Intelligence Platforms

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| MISP | Open-source threat intelligence sharing and correlation platform | Plateforme open source de partage et de corrélation du renseignement sur les menaces | OpenCTI, OTX | Free (self-hosted) | 🇧🇪 Belgium | [misp-project.org](https://www.misp-project.org) |
| Recorded Future | Real-time threat intelligence with predictive analytics — industry standard for CTI teams | Renseignement sur les menaces en temps réel avec analyse prédictive | Mandiant, Flashpoint | Paid | 🇺🇸 USA | [recordedfuture.com](https://www.recordedfuture.com) |
| Maltego | Visual threat actor and infrastructure mapping, correlate IOCs across sources | Cartographie visuelle des acteurs de menace et des infrastructures, corrélation IOC | SpiderFoot, Neo4j | Freemium | 🇩🇪 Germany | [maltego.com](https://www.maltego.com) |
| IntelX | Search across dark web, forums and paste sites for threat actor mentions and leaked data | Recherche sur le dark web, forums et paste sites pour les mentions d'acteurs de menace | OTX, Pulsedive | Freemium | 🇩🇪 Germany | [intelx.io](https://intelx.io) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Define the threat : actor, campaign, malware family or IOC type
2. Collect IOCs : IP addresses, domains, file hashes, email addresses, URLs
3. Analyze each IOC across threat intelligence platforms (VirusTotal, OTX, Pulsedive)
4. Map associated infrastructure : pivot from IOC to related domains, IPs and hosting patterns
5. Hunt for active infrastructure (Shodan, Censys, FOFA) using SSL, banner and favicon fingerprints
6. Monitor dark web forums and Telegram channels for actor mentions
7. Attribute when possible : link to known threat actors or groups using MITRE ATT&CK TTPs
8. Produce an actionable threat report with recommendations

**FR**
1. Définir la menace : acteur, campagne, famille de malware ou type d'IOC
2. Collecter les IOCs : adresses IP, domaines, hashes de fichiers, adresses email, URLs
3. Analyser chaque IOC sur les plateformes de renseignement (VirusTotal, OTX, Pulsedive)
4. Cartographier l'infrastructure associée : pivoter de l'IOC vers les domaines liés, IPs et patterns d'hébergement
5. Chasser l'infrastructure active (Shodan, Censys, FOFA) via les empreintes SSL, banners et favicons
6. Surveiller les forums dark web et canaux Telegram pour les mentions d'acteurs
7. Attribuer si possible : relier à des acteurs ou groupes connus via les TTPs MITRE ATT&CK
8. Produire un rapport de menace exploitable avec recommandations

---

## 💡 MITRE ATT&CK Framework — Quick Reference

| Tactic | EN Description | FR Description |
|--------|---------------|----------------|
| Reconnaissance | Gathering info before attack | Collecte d'informations avant l'attaque |
| Resource Development | Building attack infrastructure | Construction de l'infrastructure d'attaque |
| Initial Access | Entry point into target | Point d'entrée dans la cible |
| Execution | Running malicious code | Exécution du code malveillant |
| Persistence | Maintaining foothold | Maintien de l'accès |
| Privilege Escalation | Gaining higher permissions | Élévation de privilèges |
| Defense Evasion | Avoiding detection | Contournement des mécanismes de détection |
| Lateral Movement | Moving through the network | Déplacement au sein du réseau |
| Exfiltration | Stealing data | Exfiltration de données |
| Impact | Disrupting or destroying systems | Perturbation ou destruction des systèmes |

> Full framework: [attack.mitre.org](https://attack.mitre.org)

---

## 🚩 Key Red Flags / Signaux d'alerte

**ENG**
| Red Flag | Possible Implication |
|----------|---------------------|
| IP flagged on multiple threat feeds | Active malicious infrastructure |
| Recently registered domain with privacy protection | Potential phishing or C2 preparation |
| File hash matches known malware family | Active malware deployment |
| Actor mentioned on dark web forums | Planned or active campaign |
| Infrastructure reuse across multiple campaigns | Confirmed single threat actor |
| Self-signed certificate on unexpected port | Potential C2 or MitM infrastructure |

**FR**
| Signal d’alerte | Implication possible |
|-----------------|----------------------|
| IP signalée sur plusieurs flux de menaces | Infrastructure malveillante active |
| Domaine récemment enregistré avec protection de confidentialité | Potentiel phishing ou préparation d’une infrastructure C2 |
| Empreinte de fichier (hash) correspondant à une famille de malware connue | Déploiement actif de malware |
| Acteur mentionné sur des forums du dark web | Campagne planifiée ou en cours |
| Réutilisation d’infrastructure sur plusieurs campagnes | Acteur de menace unique confirmé |
| Certificat auto-signé sur un port inattendu | Infrastructure potentielle de C2 ou MitM |


---

## 💡 Tips & Good Practices / Conseils

**ENG**
- IOCs have a shelf life — always check the intelligence date before acting on it
- Attribution is hard: never over-attribute without strong corroborating evidence
- Correlate multiple independent sources before drawing conclusions
- MITRE ATT&CK is the standard framework for structuring TTPs in threat reports
- Telegram channels have replaced forums as the primary real-time threat actor communication vector
- False flags are common — state-sponsored actors frequently mimic other groups' TTPs
- Certificate and favicon pivoting on Shodan/Censys can find entire C2 infrastructure from a single IOC

**FR**
- Les IOC ont une durée de vie limitée : vérifiez toujours la date du renseignement avant d’agir
- L’attribution est difficile : ne jamais sur-attribuer sans preuves solides de corroboration
- Corrélez plusieurs sources indépendantes avant de tirer des conclusions
- MITRE ATT&CK est le cadre standard pour structurer les TTP dans les rapports de menace
- Les canaux Telegram ont remplacé les forums comme principal vecteur de communication en temps réel des acteurs de menace
- Les faux drapeaux sont fréquents : les acteurs étatiques imitent souvent les TTP d’autres groupes
- Le pivot par certificat et favicon sur Shodan/Censys peut révéler toute une infrastructure C2 à partir d’un seul IOC


---

## 🔗 Useful Resources / Ressources utiles

- [MITRE ATT&CK](https://attack.mitre.org)
- [OTX AlienVault](https://otx.alienvault.com)
- [MalwareBazaar](https://bazaar.abuse.ch)
- [Recorded Future Blog](https://www.recordedfuture.com/blog)
- [Krebs on Security](https://krebsonsecurity.com)
- [The DFIR Report](https://thedfirreport.com)

> *Discover other [tools](../Tools)*

> *Back to [Main Playbook](../README.md)*
