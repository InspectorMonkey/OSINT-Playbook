# 🔍 OSINT Playbook

> **Investigator's reference guide | Guide de référence pour investigateur**  
> *Last updated: February 2026*

---

## 🇬🇧 About / 🇫🇷 À propos

**EN** — This repository centralizes my tools, methodologies and best practices for OSINT investigations. It covers social media, dark web, geolocation, open-source intelligence, maritime, crypto, cyber breaches, corporate intelligence, threat intelligence, phone & telecom, image analysis, disinformation and aviation.

**FR** — Ce repository centralise mes outils, méthodologies et bonnes pratiques en matière d'investigation OSINT. Il couvre les réseaux sociaux, le dark web, la géolocalisation, les sources ouvertes, le maritime, la crypto, les fuites de données, l'intelligence corporate, la threat intelligence, le téléphone, l'analyse d'image, la désinformation et l'aviation.

---

## 📁 Structure
```
OSINT-Playbook/
├── README.md
├── Tools/
│   ├── SocialMedia.md
│   ├── DarkWeb.md
│   ├── Geolocation.md
│   ├── OpenSources.md
│   ├── Maritime.md
│   ├── Crypto.md
│   ├── CyberBreaches.md
│   ├── CorporateIntelligence.md
│   ├── ThreatIntelligence.md
│   ├── PhoneTelecom.md
│   ├── ImageMetadata.md
│   ├── Disinformation.md
│   └── Aviation.md
├── Methodology/
│   ├── Investigation-Process.md
│   └── Reporting-Template.md
└── References/
    └── Resources.md
```

---

## 🛠️ Main Tools / Outils principaux

### Identity & Social Media
| Tool | Usage | Link |
|------|-------|------|
| Maltego | Relationship mapping and pivoting | [maltego.com](https://www.maltego.com) |
| Sherlock | Username search across 300+ platforms | [GitHub](https://github.com/sherlock-project/sherlock) |
| Maigret | Advanced profiling by username | [GitHub](https://github.com/soxoj/maigret) |
| Holehe | Email verification across platforms | [GitHub](https://github.com/megadose/holehe) |
| Social-Analyzer | Multi-platform analysis | [GitHub](https://github.com/qeeqbox/social-analyzer) |

### Infrastructure & Network
| Tool | Usage | Link |
|------|-------|------|
| Shodan | Search engine for connected devices | [shodan.io](https://www.shodan.io) |
| WHOIS | Domain registration information | [whois.domaintools.com](https://whois.domaintools.com) |
| theHarvester | Email, domain and IP harvesting | [GitHub](https://github.com/laramies/theHarvester) |
| Censys | Internet infrastructure scanning | [censys.io](https://censys.io) |

### Cyber & Breaches
| Tool | Usage | Link |
|------|-------|------|
| HaveIBeenPwned | Check email in known breaches | [haveibeenpwned.com](https://haveibeenpwned.com) |
| DeHashed | Search leaked credentials | [dehashed.com](https://www.dehashed.com) |
| IntelX | Search pastes, leaks, dark web | [intelx.io](https://intelx.io) |

### Corporate Intelligence
| Tool | Usage | Link |
|------|-------|------|
| OpenCorporates | Global company registry | [opencorporates.com](https://opencorporates.com) |
| OCCRP Aleph | Leaked documents and corporate data | [aleph.occrp.org](https://aleph.occrp.org) |
| ICIJ Offshore Leaks | Panama & Pandora Papers | [offshoreleaks.icij.org](https://offshoreleaks.icij.org) |
| OpenSanctions | Global sanctions and PEP lists | [opensanctions.org](https://www.opensanctions.org) |

### Maritime
| Tool | Usage | Link |
|------|-------|------|
| MarineTraffic | Real-time AIS vessel tracking | [marinetraffic.com](https://www.marinetraffic.com) |
| Equasis | Ship ownership and inspection records | [equasis.org](https://www.equasis.org) |
| Windward | AI-powered maritime intelligence | [windward.ai](https://windward.ai) |

### Crypto
| Tool | Usage | Link |
|------|-------|------|
| Etherscan | Ethereum blockchain explorer | [etherscan.io](https://etherscan.io) |
| Breadcrumbs | Free crypto transaction tracing | [breadcrumbs.app](https://www.breadcrumbs.app) |
| Arkham Intelligence | On-chain entity identification | [arkhamintelligence.com](https://platform.arkhamintelligence.com) |

### Threat Intelligence
| Tool | Usage | Link |
|------|-------|------|
| VirusTotal | File, URL and domain reputation | [virustotal.com](https://www.virustotal.com) |
| OTX AlienVault | Open threat intelligence community | [otx.alienvault.com](https://otx.alienvault.com) |
| MalwareBazaar | Malware samples and IOC database | [bazaar.abuse.ch](https://bazaar.abuse.ch) |

### Geolocation / IMINT
| Tool | Usage | Link |
|------|-------|------|
| GeoSpy | AI-based image geolocation | [geospy.ai](https://geospy.ai) |
| SunCalc | Shadow analysis for dating images | [suncalc.org](https://www.suncalc.org) |
| Google Earth Pro | Geospatial analysis | [earth.google.com](https://earth.google.com) |

### Phone & Telecom
| Tool | Usage | Link |
|------|-------|------|
| PhoneInfoga | Advanced phone number OSINT | [GitHub](https://github.com/sundowndev/phoneinfoga) |
| Truecaller | Caller ID and phone number search | [truecaller.com](https://www.truecaller.com) |

### Image & Metadata
| Tool | Usage | Link |
|------|-------|------|
| ExifTool | Extract metadata from images | [exiftool.org](https://exiftool.org) |
| FotoForensics | Image authenticity analysis | [fotoforensics.com](https://fotoforensics.com) |
| Deepware Scanner | Deepfake detection | [deepware.ai](https://deepware.ai) |

### Disinformation & Influence Ops
| Tool | Usage | Link |
|------|-------|------|
| Botometer | Twitter/X bot detection | [botometer.osome.iu.edu](https://botometer.osome.iu.edu) |
| Hoaxy | Visualize spread of claims | [hoaxy.osome.iu.edu](https://hoaxy.osome.iu.edu) |
| Sensity | Deepfake and synthetic media detection | [sensity.ai](https://sensity.ai) |

### Aviation
| Tool | Usage | Link |
|------|-------|------|
| FlightRadar24 | Real-time ADS-B flight tracking | [flightradar24.com](https://www.flightradar24.com) |
| ADS-B Exchange | Unfiltered global ADS-B tracking | [adsbexchange.com](https://www.adsbexchange.com) |
| Rzjets | Aircraft ownership and history | [rzjets.net](https://rzjets.net) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. **Define** — Clarify objectives and scope
2. **Collect** — Gather data using appropriate tools
3. **Verify** — Cross-check and validate each piece of information
4. **Analyze** — Identify connections, patterns and anomalies
5. **Synthesize** — Produce a clear and actionable report

**FR**
1. **Définir** — Clarifier les objectifs et le périmètre de l'investigation
2. **Collecter** — Rassembler les données via les outils adaptés
3. **Vérifier** — Recouper et valider chaque information
4. **Analyser** — Identifier les liens, patterns et anomalies
5. **Synthétiser** — Produire un rapport clair et exploitable

---

## 📚 References / Références

- [OSINT Framework](https://osintframework.com)
- [Bellingcat Guides](https://www.bellingcat.com/category/resources/)
- [IntelTechniques Blog](https://inteltechniques.com/blog/)
- [The OSINT Curious Project](https://osintcurio.us)
- [MITRE ATT&CK](https://attack.mitre.org)
- [OCCRP](https://www.occrp.org)
- [EU DisinfoLab](https://www.disinfo.eu)

---

## 🔗 Detailed Pages / Pages détaillées

| Domain | EN | FR | Link |
|--------|----|----|------|
| 📱 Social Media | Identify and profile individuals through their online presence, usernames and accounts | Identifier et profiler des individus via leur présence en ligne, pseudos et comptes | [Tools/SocialMedia.md](Tools/SocialMedia.md) |
| 🌑 Dark Web | Monitor hidden networks for illicit activity, data leaks and threat actor communications | Surveiller les réseaux cachés pour détecter activités illicites, fuites de données et communications d'acteurs malveillants | [Tools/DarkWeb.md](Tools/DarkWeb.md) |
| 🌍 Geolocation / IMINT | Locate and verify places, events and individuals through imagery and visual analysis | Localiser et vérifier des lieux, événements et individus via l'analyse d'images et de visuels | [Tools/Geolocation.md](Tools/Geolocation.md) |
| 📰 Open Sources | Extract intelligence from publicly available sources, registries and web archives | Extraire du renseignement depuis les sources publiques, registres et archives web | [Tools/OpenSources.md](Tools/OpenSources.md) |
| ⚓ Maritime | Track vessels, identify ownership structures and detect sanctions evasion at sea | Suivre les navires, identifier les structures de propriété et détecter les contournements de sanctions en mer | [Tools/Maritime.md](Tools/Maritime.md) |
| 💰 Crypto | Trace blockchain transactions, identify wallets and follow illicit financial flows | Tracer les transactions blockchain, identifier les portefeuilles et suivre les flux financiers illicites | [Tools/Crypto.md](Tools/Crypto.md) |
| 💻 Cyber & Data Breaches | Detect exposed credentials, monitor data leaks and investigate cybercriminal ecosystems | Détecter les credentials exposés, surveiller les fuites de données et investiguer les écosystèmes cybercriminels | [Tools/CyberBreaches.md](Tools/CyberBreaches.md) |
| 🏢 Corporate Intelligence | Map corporate structures, identify beneficial owners and detect financial irregularities | Cartographier les structures corporate, identifier les bénéficiaires effectifs et détecter les irrégularités financières | [Tools/CorporateIntelligence.md](Tools/CorporateIntelligence.md) |
| 🎯 Threat Intelligence | Identify threat actors, analyze TTPs and monitor malicious infrastructure | Identifier les acteurs malveillants, analyser les TTPs et surveiller les infrastructures malveillantes | [Tools/ThreatIntelligence.md](Tools/ThreatIntelligence.md) |
| 📞 Phone & Telecom | Investigate phone numbers, identify carriers and link numbers to identities | Investiguer les numéros de téléphone, identifier les opérateurs et relier les numéros à des identités | [Tools/PhoneTelecom.md](Tools/PhoneTelecom.md) |
| 🖼️ Image & Metadata | Analyze image authenticity, extract metadata and detect deepfakes | Analyser l'authenticité des images, extraire les métadonnées et détecter les deepfakes | [Tools/ImageMetadata.md](Tools/ImageMetadata.md) |
| 📢 Disinformation & Influence Ops | Detect coordinated inauthentic behavior, trace narrative origins and identify bot networks | Détecter les comportements inauthentiques coordonnés, tracer l'origine des narratifs et identifier les réseaux de bots | [Tools/Disinformation.md](Tools/Disinformation.md) |
| ✈️ Aviation | Track aircraft, identify owners and detect sanctions evasion through private aviation | Suivre les aéronefs, identifier les propriétaires et détecter les contournements de sanctions via l'aviation privée | [Tools/Aviation.md](Tools/Aviation.md) |

---

## ⚠️ Ethics & Legality / Éthique & Légalité

**EN** — All investigations referenced here comply with applicable law and OSINT ethical standards. No sensitive or personally identifiable data is published in this repository.

**FR** — Toutes les investigations présentées ici respectent le cadre légal en vigueur et les principes éthiques de l'OSINT. Aucune donnée sensible ou personnelle identifiable n'est publiée dans ce repository.

---

*OSINT Analyst | Strategic Intelligence & Cybersecurity*
