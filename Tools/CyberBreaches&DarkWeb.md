# 💻 Cyber Breaches & Dark Web OSINT

> *Back to [Main Playbook](../README.md)*

---

## ⚠️ Legal Notice / Avertissement légal

🇬🇧
-Breach data must only be used for investigative or defensive purposes. 
-Never exploit, redistribute or use credentials for unauthorized access. 
-Dark web investigation must strictly comply with applicable law. 
-Never engage with illegal content or services.

🇫🇷
-Les fuites de données ne doivent être utilisées qu'à des fins défensives ou d'investigation. 
-Ne jamais exploiter, redistribuer ou utiliser des credentials pour un accès non autorisé. 
-Toute investigation sur le dark web doit strictement respecter le cadre légal en vigueur. 
-Ne jamais interagir avec des contenus ou services illégaux.

---

## 🛠️ Tools / Outils

### Breach & Credential Search

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| HaveIBeenPwned | Check if an email appears in known data breaches | Vérifier si un email apparaît dans des fuites de données connues | LeakCheck, BreachDirectory | Free (API paid) | 🇦🇺 Australia | [haveibeenpwned.com](https://haveibeenpwned.com) |
| DeHashed | Search leaked credentials and PII across multiple breach datasets | Rechercher des credentials et données personnelles fuités dans de multiples jeux de données | IntelX, LeakCheck | Freemium | 🇺🇸 USA | [dehashed.com](https://www.dehashed.com) |
| IntelX | Search engine for pastes, leaks, dark web sources and historical data (12+ PB indexed) | Moteur de recherche pour les pastes, fuites, sources dark web et données historiques (12+ PO indexés) | DeHashed, LeakCheck | Freemium | 🇩🇪 Germany | [intelx.io](https://intelx.io) |
| LeakCheck | Credential leak verification with reverse search by password | Vérification de fuites de credentials avec recherche inversée par mot de passe | DeHashed, HIBP | Freemium | 🌐 International | [leakcheck.io](https://leakcheck.io) |
| LeakRadar | Real-time cleartext credential leak detection across 290B+ records with domain monitoring and alerts | Détection temps réel de credentials en clair sur 290Mds+ d'enregistrements avec surveillance de domaine et alertes | IntelX, DeHashed | Freemium | 🌐 International | [leakradar.io](https://leakradar.io) |
| Hudson Rock | Infostealer intelligence platform - compromised credentials database and Cavalier API | Plateforme de renseignement infostealer — base de données de credentials compromis et API Cavalier | LeakRadar, Flare | Freemium | 🇮🇱 Israel | [hudsonrock.com](https://www.hudsonrock.com/threat-intelligence-cybercrime-tools) |
| BreachDirectory | Breach data lookup — email, username and password reverse search | Lookup dans les données de fuites : recherche inversée par email, pseudo et mot de passe | HIBP, LeakCheck | Free | 🌐 International | [breachdirectory.org](https://breachdirectory.org) |
| Pulsedive | Community threat intelligence platform with MITRE ATT&CK enrichment — correlates IOCs | Plateforme de renseignement sur les menaces communautaire avec enrichissement MITRE ATT&CK | OTX AlienVault | Freemium | 🇺🇸 USA | [pulsedive.com](https://pulsedive.com) |
| ThreatBook | Intelligence-driven threat detection with deep APAC threat actor coverage | Détection de menaces pilotée par le renseignement avec couverture approfondie des acteurs APAC | Pulsedive, OTX | Freemium | 🇨🇳 China | [threatbook.io](https://threatbook.io) |

### Paste & Code Exposure

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| IntelX | Comprehensive paste and leak search including Pastebin, GhostBin and dark web sources | Recherche complète dans les pastes et fuites incluant Pastebin, GhostBin et sources dark web | Pastebin Search | Freemium | 🇩🇪 Germany | [intelx.io](https://intelx.io) |
| Grep.app | Regex search across public GitHub repositories, find exposed API keys and credentials | Recherche regex dans les dépôts GitHub publics, trouver les clés API et credentials exposés | Searchcode, GitHub Search | Free | 🌐 International | [grep.app](https://grep.app) |

### Dark Web Search & Monitoring

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| Ahmia | Ethical Tor hidden services search engine accessible from the clearnet — indexes .onion sites | Moteur de recherche éthique des services cachés Tor accessible depuis le web classique | DarkSearch, OnionSearch | Free | 🇫🇮 Finland | [ahmia.fi](https://ahmia.fi) |
| DarkSearch | Indexed dark web search engine accessible from the clearnet | Moteur de recherche dark web indexé accessible depuis le clearnet | Ahmia | Freemium | 🌐 International | [darksearch.io](https://darksearch.io) |
| DarkBeast | Dark web monitoring and keyword-based search for brand and data exposure | Veille dark web et recherche par mots-clés pour la surveillance d'exposition de marque et de données | IntelX, Ahmia | Paid | 🌐 International | [darkbeast.io](https://darkbeast.io) |
| Tor Browser | Anonymous access to .onion sites via the Tor network | Accès anonyme aux sites .onion via le réseau Tor | — | Free | 🌐 International | [torproject.org](https://www.torproject.org) |
| OnionSearch | CLI tool for searching multiple dark web search engines simultaneously | Outil CLI pour rechercher simultanément sur plusieurs moteurs dark web | Ahmia | Free | 🌐 International | [GitHub](https://github.com/megadose/OnionSearch) |

---

## 🔎 Methodology / Méthodologie

### Breach Investigation

🇬🇧
1. Identify target email addresses, domains or usernames
2. Check known breach databases (HIBP, DeHashed, LeakCheck)
3. Search paste sites and dark web sources (IntelX, LeakRadar)
4. Search public code repositories for accidentally exposed credentials (Grep.app)
5. Cross-reference findings to build a broader identity or risk profile
6. Document all findings responsibly (never exploit or share raw credentials)

🇫🇷
1. Identifier les adresses email, domaines ou pseudos cibles
2. Consulter les bases de données de fuites connues (HIBP, DeHashed, LeakCheck)
3. Rechercher sur les sites de paste et sources dark web (IntelX, LeakRadar)
4. Rechercher dans les dépôts publics les credentials accidentellement exposés (Grep.app)
5. Recouper les résultats pour construire un profil d'identité ou de risque plus large
6. Documenter tous les résultats de manière responsable (ne jamais exploiter ou partager des credentials bruts)

### Dark Web Investigation

🇬🇧
1. Define scope : what exactly are you looking for?
2. Use clearnet-accessible search engines first (Ahmia, DarkSearch, IntelX)
3. Access .onion sites only via Tor in a secure, isolated environment (dedicated VM)
4. Never download files directly, open only in sandboxed environment
5. Document every finding with screenshots and timestamps
6. Cross-reference with clearnet sources to validate

🇫🇷
1. Définir le périmètre : que cherche-t-on exactement ?
2. Utiliser d'abord les moteurs accessibles depuis le clearnet (Ahmia, DarkSearch, IntelX)
3. Accéder aux sites .onion uniquement via Tor dans un environnement sécurisé et isolé (VM dédiée)
4. Ne jamais télécharger de fichiers directement, ouvrir uniquement dans un environnement sandboxé
5. Documenter chaque découverte avec captures d'écran et horodatage
6. Recouper avec des sources clearnet pour valider

---

## 💡 GitHub Dorks — Quick Reference

| Dork | Usage | Usages |
|------|-------|
| `filename:.env password` | Find exposed environment files | Détecter les fichiers d'environnement accessibles publiquement |
| `filename:config.php dbpassword` | Find database credentials | Détecter les informations d'identification des bases de données |
| `filename:id_rsa` | Find exposed SSH private keys | Détecter les clés privées SSH accessibles publiquement |
| `"api_key" "secret"` | Find exposed API keys | Détexter les clefs API exposées |
| `filename:.htpasswd` | Find exposed password files | Détecter les fichiers de mots de passe exposés |
| `"DB_PASSWORD" extension:env` | Find database passwords in .env files | Détecter les bases de données de mots de passe en fichier .env |
| `"privatekey" extension:pem` | Find exposed private keys | Détecter les clefs privées exposées |

---

## 🕵️ Cybercriminal Ecosystems / Écosystèmes cybercriminels

🇬🇧
— Before data appears in public breach databases, it circulates in cybercriminal ecosystems. Monitoring these sources provides earlier visibility on active leaks and threat actor activity.

🇫🇷
— Avant que les données n'apparaissent dans les bases de données publiques de fuites, elles circulent au sein des écosystèmes cybercriminels. Surveiller ces sources permet d'obtenir une visibilité plus précoce sur les fuites actives et l'activité des acteurs malveillants.

🇬🇧
| Platform | Type | Note |
|----------|------|------|
| Telegram channels | Messaging | Primary vector for data leaks and initial sales |
| BreachForums | Forum | Major leaked data trading and sharing hub |
| XSS.is / Exploit.in | Russian forums | High-level cybercriminal activity |
| Dark web marketplaces | .onion sites | Credential and data sales with escrow |
| Paste sites (Pastebin, GhostBin) | Paste | Rapid public data dumps |

🇫🇷
| Plateforme | Type | Note |
|------------|------|------|
| Canaux Telegram | Messagerie | Principal vecteur de fuites de données et de ventes initiales |
| BreachForums | Forum | Plateforme majeure d'échange et de partage de données piratés |
| XSS.is/Exploit.in | Forums russes | Activités cybercriminelles de haut niveau |
| Marchés du dark web | Sites .onion | Vente de données et d'identifiants avec système de dépôt de garantie |
| Sites de paste (Pastebin, GhistBin) | Paste | Publication rapide de données en accès public |

---

## 🚩 Key Red Flags / Signaux d'alerte

**ENG**
| Red Flag | Possible Implication |
|----------|---------------------|
| Corporate email found in infostealer logs | Active device compromise |
| Credentials found in multiple breach datasets | Persistent password reuse, high exploitation risk |
| Exposed API keys in public repos | Active security vulnerability, immediate action required |
| Domain mentioned on dark web forums | Targeted attack or active breach |
| Data advertised before public disclosure | Zero-day breach still under exploitation |
| Employee credentials on Telegram channels | Imminent phishing or account takeover risk |

🇫🇷
| Indicateur d'alerte (Red Flag) | Implication possible |
| Adresse email professionnelle dans des logs d'infostealers | Compromission active d'un appareil |
| Identifiants présents dans plusieurs jeux de données de fuites | Réutilisation persistante de mots de passe, risque élevé d'exploitation |
| Clés API exposées dans des dépôts publics | Vulnérabilité de sécurité active, action immédiate requise |
| Domaine mentionné sur des forums du dark web | Attaque ciblée ou fuite active en cours |
| Données annoncées avant une divulgation publique | Fuite zero-day encore exploitée |
| Identifiants d'employés sur des canaux Telegram | Risque imminent de phishing ou de prise de contrôle de compte |

---

## 💡 Tips & Good Practices / Conseils

🇬🇧
- Always operate from a dedicated, isolated machine or VM for dark web investigation
- Never use your real identity or personal accounts on dark web platforms
- Disable JavaScript in Tor Browser for better anonymity
- Infostealer logs (Hudson Rock, LeakRadar) predate public breach disclosure — use them early
- Telegram has become the primary distribution vector for fresh breach data — monitor relevant channels
- Many .onion sites are honeypots or scams — prioritize passive observation, never interact unless necessary

🇫🇷
- Toujours opérer depuis une machine dédiée et isolée ou une VM pour les investigations sur le dark web
- Ne jamais utiliser votre véritable identité ou vos comptes personnels sur les plateformes du dark web
- Désactiver JavaScript dans Tor Browser pour une meilleure anonymité
- Les logs des infostealers (comme Hudson Rock, LeakRadar) précèdent souvent les divulgations publiques de fuites : utilise-les tôt
- Telegram est devenu le principal vecteur de distribution des données fraîches issues de fuites : surveille les canaux pertinents.
- De nombreux sites .onion sont des honeypots ou des arnaques : privilégie l'observation passive, n'interagis que si nécessaire.

Tu peux te rendre [ici](https://github.com/OmphalosOSINT/Awesome-OSINT-Toolbox/blob/main/Tools/DarkWeb.md) pour avoir accès à une boîte à outils crypto plus complète/You can go [here](https://github.com/OmphalosOSINT/Awesome-OSINT-Toolbox/blob/main/Tools/DarkWeb.md) to access a more comprehensive crypto toolkit

>*Next [tool](../Tools/Disinformation.md)*

> *Discover other [tools](../Tools)*

> *Back to [Main Playbook](../README.md)*

