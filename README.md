# 🔍 OSINT Playbook

> **Investigator's reference guide | Guide de référence pour investigateur**
> *Last updated: March 2026*

---

## 🇬🇧 About / 🇫🇷 À propos

**EN** — This repository centralizes tools, methodologies and best practices for OSINT investigations. Organized by discipline, it covers identity & social media, infrastructure & network reconnaissance, cyber breaches & dark web monitoring, threat intelligence, corporate intelligence, crypto tracing, phone & telecom, geolocation & imagery, disinformation & influence operations, maritime and aviation.

**FR** — Ce repository centralise les outils, méthodologies et bonnes pratiques pour les investigations OSINT. Organisé par discipline, il couvre l'identité et les réseaux sociaux, la reconnaissance d'infrastructure et réseau, les fuites de données et la surveillance du dark web, la threat intelligence, l'intelligence corporate, le traçage crypto, le téléphone, la géolocalisation et l'imagerie, la désinformation et les opérations d'influence, le maritime et l'aviation.

---

## 📁 Structure

```
OSINT-Playbook/
├── README.md
├── Tools/
│   ├── Identity-SocialMedia.md         # Usernames, email finders, identity pivot, SOCMINT
│   ├── Infrastructure-Network.md       # DNS, WHOIS, IP, scanning, web recon, source code
│   ├── CyberBreaches-DarkWeb.md        # Leaks, credentials, dark web monitoring
│   ├── ThreatIntelligence.md           # Threat actors, IOCs, malicious infrastructure
│   ├── CorporateIntelligence.md        # Company registries, sanctions, beneficial owners
│   ├── Crypto.md                       # Blockchain tracing, wallet analysis
│   ├── PhoneTelecom.md                 # Phone number OSINT, carrier lookup
│   ├── Geolocation-IMINT.md            # Image geolocation, metadata, visual analysis, deepfakes
│   ├── Disinformation.md               # Influence ops, bot detection, narrative tracking
│   ├── Maritime.md                     # Vessel tracking, ownership, sanctions evasion
│   └── Aviation.md                     # Flight tracking, aircraft ownership
├── Methodology/
│   ├── Investigation-Process.md
│   └── Reporting-Template.md
└── References/
    └── Resources.md
```

---

## 🛠️ Quick Tool Index

### 👤 Identity & Social Media
| Tool | Usage | Link |
|------|-------|------|
| Sherlock | Username search across 300+ platforms | [GitHub](https://github.com/sherlock-project/sherlock) |
| Maigret | Advanced username profiling across 3000+ sites | [GitHub](https://github.com/soxoj/maigret) |
| Holehe | Email → registered accounts (120+ platforms) | [GitHub](https://github.com/megadose/holehe) |
| Epieos | Email/phone → Google account data & linked accounts | [epieos.com](https://epieos.com) |
| OSINT Industries | Real-time identity pivot from email/phone/username/wallet | [osint.industries](https://www.osint.industries) |
| Hunter.io | Professional email finder by domain | [hunter.io](https://hunter.io) |
| RecruitEm | X-Ray Google dorks for LinkedIn and 10 other platforms | [recruitin.net](https://recruitin.net) |
| Maltego | Visual relationship mapping and entity pivoting | [maltego.com](https://www.maltego.com) |

### 🌐 Infrastructure & Network
| Tool | Usage | Link |
|------|-------|------|
| Shodan | Search engine for internet-connected devices | [shodan.io](https://www.shodan.io) |
| Censys | Internet infrastructure scanning, strong TLS search | [censys.io](https://censys.io) |
| SecurityTrails | DNS history and subdomain enumeration | [securitytrails.com](https://securitytrails.com) |
| crt.sh | Certificate Transparency subdomain discovery | [crt.sh](https://crt.sh) |
| WhoisXML API | WHOIS history, reverse WHOIS, DNS intelligence | [whoisxmlapi.com](https://main.whoisxmlapi.com) |
| ViewDNS | Free DNS/IP multi-tool | [viewdns.info](https://viewdns.info) |
| Web-Check | All-in-one website recon, 30+ checks | [web-check.as93.net](https://web-check.as93.net) |
| Cylect.io | OSINT aggregator launching 475+ tools pre-filled | [cylect.io](https://cylect.io) |

### 💻 Cyber Breaches & Dark Web
| Tool | Usage | Link |
|------|-------|------|
| HaveIBeenPwned | Email breach check | [haveibeenpwned.com](https://haveibeenpwned.com) |
| DeHashed | Leaked credentials and PII search | [dehashed.com](https://www.dehashed.com) |
| IntelX | Pastes, leaks, dark web search | [intelx.io](https://intelx.io) |
| Hudson Rock | Infostealer intelligence | [hudsonrock.com](https://www.hudsonrock.com/threat-intelligence-cybercrime-tools) |
| LeakRadar | 290B+ cleartext credentials with real-time alerts | [leakradar.io](https://leakradar.io) |
| Ahmia | Ethical Tor hidden services search (clearnet access) | [ahmia.fi](https://ahmia.fi) |

### 🎯 Threat Intelligence
| Tool | Usage | Link |
|------|-------|------|
| VirusTotal | File, URL and domain reputation | [virustotal.com](https://www.virustotal.com) |
| OTX AlienVault | Open threat intelligence community | [otx.alienvault.com](https://otx.alienvault.com) |
| MalwareBazaar | Malware samples and IOC database | [bazaar.abuse.ch](https://bazaar.abuse.ch) |
| GreyNoise | Internet scan traffic analysis, IP qualification | [greynoise.io](https://www.greynoise.io) |
| URLScan | Website scanning and behavior analysis | [urlscan.io](https://urlscan.io) |

### 🏢 Corporate Intelligence
| Tool | Usage | Link |
|------|-------|------|
| OpenCorporates | Global company registry | [opencorporates.com](https://opencorporates.com) |
| OCCRP Aleph | Leaked documents and corporate data | [aleph.occrp.org](https://aleph.occrp.org) |
| ICIJ Offshore Leaks | Panama & Pandora Papers | [offshoreleaks.icij.org](https://offshoreleaks.icij.org) |
| OpenSanctions | Global sanctions and PEP lists | [opensanctions.org](https://www.opensanctions.org) |
| Pappers | French company registry and financials | [pappers.fr](https://www.pappers.fr) |

### 💰 Crypto
| Tool | Usage | Link |
|------|-------|------|
| Etherscan | Ethereum blockchain explorer | [etherscan.io](https://etherscan.io) |
| Breadcrumbs | Free crypto transaction tracing | [breadcrumbs.app](https://www.breadcrumbs.app) |
| Arkham Intelligence | On-chain entity identification | [platform.arkhamintelligence.com](https://platform.arkhamintelligence.com) |
| Chainalysis Reactor | Professional blockchain investigation | [chainalysis.com](https://www.chainalysis.com) |

### 📞 Phone & Telecom
| Tool | Usage | Link |
|------|-------|------|
| PhoneInfoga | Advanced phone number OSINT framework | [GitHub](https://github.com/sundowndev/phoneinfoga) |
| Truecaller | Caller ID and reverse phone lookup | [truecaller.com](https://www.truecaller.com) |
| EmobileTracker | Worldwide carrier, line type and spam lookup | [emobiletracker.com](https://www.emobiletracker.com) |

### 🌍 Geolocation & IMINT
| Tool | Usage | Link |
|------|-------|------|
| GeoSpy | AI-based image geolocation | [geospy.ai](https://geospy.ai) |
| SunCalc | Shadow analysis for dating and locating images | [suncalc.org](https://www.suncalc.org) |
| ExifTool | Metadata extraction from images and files | [exiftool.org](https://exiftool.org) |
| PimEyes | Face recognition reverse search | [pimeyes.com](https://pimeyes.com) |
| FotoForensics | Image authenticity and manipulation analysis | [fotoforensics.com](https://fotoforensics.com) |
| Deepware Scanner | Deepfake detection | [deepware.ai](https://deepware.ai) |

### 📢 Disinformation & Influence Ops
| Tool | Usage | Link |
|------|-------|------|
| Botometer | Twitter/X bot detection | [botometer.osome.iu.edu](https://botometer.osome.iu.edu) |
| Google Fact Check Explorer | Verified fact-checks database | [toolbox.google.com/factcheck](https://toolbox.google.com/factcheck/explorer) |
| Hoaxy | Visualize spread of claims and fact-checks | [hoaxy.osome.iu.edu](https://hoaxy.osome.iu.edu) |
| Sensity | Deepfake and synthetic media detection | [sensity.ai](https://sensity.ai) |

### ⚓ Maritime
| Tool | Usage | Link |
|------|-------|------|
| MarineTraffic | Real-time AIS vessel tracking | [marinetraffic.com](https://www.marinetraffic.com) |
| Equasis | Ship ownership and inspection records | [equasis.org](https://www.equasis.org) |
| VesselFinder | Ship tracking and voyage history | [vesselfinder.com](https://www.vesselfinder.com) |
| SkyTruth | Satellite-based vessel monitoring | [skytruth.org](https://skytruth.org) |

### ✈️ Aviation
| Tool | Usage | Link |
|------|-------|------|
| FlightRadar24 | Real-time ADS-B flight tracking | [flightradar24.com](https://www.flightradar24.com) |
| ADS-B Exchange | Unfiltered global ADS-B — no opt-out | [adsbexchange.com](https://www.adsbexchange.com) |
| Rzjets | Aircraft ownership and history | [rzjets.net](https://rzjets.net) |
| FAA Aircraft Registry | US aircraft ownership database | [registry.faa.gov](https://registry.faa.gov) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. **Define** — Clarify objectives, scope and legal boundaries
2. **Collect** — Gather data using appropriate tools
3. **Verify** — Cross-check and validate each piece of information
4. **Analyze** — Identify connections, patterns and anomalies
5. **Synthesize** — Produce a clear and actionable report

**FR**
1. **Définir** — Clarifier les objectifs, le périmètre et le cadre légal
2. **Collecter** — Rassembler les données via les outils adaptés
3. **Vérifier** — Recouper et valider chaque information
4. **Analyser** — Identifier les liens, patterns et anomalies
5. **Synthétiser** — Produire un rapport clair et exploitable

---

## 🔗 Detailed Pages / Pages détaillées

| Domain | EN | FR | Link |
|--------|----|----|------|
| 👤 Identity & Social Media | Identify and profile individuals through usernames, emails and social accounts | Identifier et profiler des individus via pseudos, emails et comptes | [Tools/Identity-SocialMedia.md](Tools/Identity-SocialMedia.md) |
| 🌐 Infrastructure & Network | Enumerate domains, IPs, DNS records and web infrastructure | Énumérer domaines, IPs, DNS et infrastructures web | [Tools/Infrastructure-Network.md](Tools/Infrastructure-Network.md) |
| 💻 Cyber Breaches & Dark Web | Detect exposed credentials, monitor leaks and dark web activity | Détecter les credentials exposés, surveiller les fuites et le dark web | [Tools/CyberBreaches-DarkWeb.md](Tools/CyberBreaches-DarkWeb.md) |
| 🎯 Threat Intelligence | Identify threat actors, analyze TTPs, monitor malicious infrastructure | Identifier les acteurs malveillants, analyser les TTPs, surveiller les infrastructures | [Tools/ThreatIntelligence.md](Tools/ThreatIntelligence.md) |
| 🏢 Corporate Intelligence | Map corporate structures, identify beneficial owners, detect irregularities | Cartographier les structures corporate, identifier les bénéficiaires effectifs | [Tools/CorporateIntelligence.md](Tools/CorporateIntelligence.md) |
| 💰 Crypto | Trace blockchain transactions, identify wallets, follow illicit financial flows | Tracer les transactions blockchain, identifier les portefeuilles | [Tools/Crypto.md](Tools/Crypto.md) |
| 📞 Phone & Telecom | Investigate phone numbers, identify carriers, link numbers to identities | Investiguer les numéros de téléphone, identifier les opérateurs | [Tools/PhoneTelecom.md](Tools/PhoneTelecom.md) |
| 🌍 Geolocation & IMINT | Locate and verify places through imagery, metadata and visual analysis | Localiser et vérifier des lieux via l'imagerie, les métadonnées et l'analyse visuelle | [Tools/Geolocation-IMINT.md](Tools/Geolocation-IMINT.md) |
| 📢 Disinformation | Detect coordinated inauthentic behavior, trace narratives, identify bots | Détecter les comportements inauthentiques coordonnés, tracer les narratifs | [Tools/Disinformation.md](Tools/Disinformation.md) |
| ⚓ Maritime | Track vessels, identify ownership, detect sanctions evasion at sea | Suivre les navires, identifier les propriétaires, détecter les contournements de sanctions | [Tools/Maritime.md](Tools/Maritime.md) |
| ✈️ Aviation | Track aircraft, identify owners, detect sanctions evasion via private aviation | Suivre les aéronefs, identifier les propriétaires, détecter les contournements de sanctions | [Tools/Aviation.md](Tools/Aviation.md) |

---

## 📚 Key References

- [OSINT Framework](https://osintframework.com)
- [Bellingcat Guides](https://www.bellingcat.com/category/resources/)
- [IntelTechniques](https://inteltechniques.com/blog/)
- [OSINT Curious](https://osintcurio.us)
- [MITRE ATT&CK](https://attack.mitre.org)
- [OCCRP](https://www.occrp.org)
- [EU DisinfoLab](https://www.disinfo.eu)

---

## ⚠️ Ethics & Legality / Éthique & Légalité

**EN** — All content in this repository complies with applicable law and OSINT ethical standards. Never access private data without authorization, exploit found credentials, or use findings to harass individuals. Always operate within your legal jurisdiction.

**FR** — Tout le contenu de ce repository respecte le cadre légal en vigueur et les principes éthiques de l'OSINT. Ne jamais accéder à des données privées sans autorisation, exploiter des credentials trouvés, ou utiliser les résultats pour harceler des individus. Toujours opérer dans le cadre légal de sa juridiction.

---

*OSINT Analyst | Strategic Intelligence & Cybersecurity*
