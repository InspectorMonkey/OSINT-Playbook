# 💻 Cyber & Data Breaches OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

| Tool | Usage | Link |
|------|-------|------|
| HaveIBeenPwned | Check if email appears in known breaches | [haveibeenpwned.com](https://haveibeenpwned.com) |
| DeHashed | Search leaked credentials and PII | [dehashed.com](https://www.dehashed.com) |
| IntelX | Search pastes, leaks and dark web sources | [intelx.io](https://intelx.io) |
| LeakCheck | Credential leak verification | [leakcheck.io](https://leakcheck.io) |
| Pastebin Search | Monitor public pastes for sensitive data | [pastebin.com](https://pastebin.com) |
| Grep.app | Search across public code repositories | [grep.app](https://grep.app) |
| GitHub Dorks | Find exposed credentials in public repos | [github.com](https://github.com) |
| Shodan | Find exposed databases and services | [shodan.io](https://www.shodan.io) |
| Censys | Identify misconfigured or exposed systems | [censys.io](https://censys.io) |
| BreachDirectory | Free breach data lookup | [breachdirectory.org](https://breachdirectory.org) |
| Pulsedive | Community-driven threat intelligence platform with MITRE ATT&CK enrichment | Plateforme de renseignement sur les menaces communautaire avec enrichissement MITRE ATT&CK | [pulsedive.com](https://pulsedive.com) |
| ThreatBook | Intelligence-driven threat detection with deep APAC threat actor coverage | Détection de menaces pilotée par l'intelligence avec couverture approfondie des acteurs APAC | [threatbook.io](https://threatbook.io) |
| Hudson Rock | Infostealer intelligence and compromised credentials database | Renseignement sur les infostealers et base de données de credentials compromis | [hudsonrock.com](https://www.hudsonrock.com/threat-intelligence-cybercrime-tools) |
| LeakRadar | Cleartext credential leak search across 290B+ records with real-time alerts | Recherche de credentials en clair sur 290 milliards d'enregistrements avec alertes temps réel | [leakradar.io](https://leakradar.io) |
| NAPALM FTP Indexer | Search engine for publicly accessible FTP servers indexing 316M+ files across 1,200+ servers to find exposed documents and data | Moteur de recherche dans les serveurs FTP publics indexant 316M+ fichiers sur 1 200+ serveurs pour détecter des documents et données exposés | [searchftps.net](https://www.searchftps.net) |
| Google Hacking Database (GHDB) | Community-maintained index of Google Dorks organized by category to find sensitive data, exposed devices and login portals via search engines | Index communautaire de Google Dorks classés par catégorie pour découvrir données sensibles, équipements exposés et portails de connexion via les moteurs de recherche | [exploit-db.com/google-hacking-database](https://www.exploit-db.com/google-hacking-database) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Identify target email addresses, domains or usernames
2. Check known breach databases (HaveIBeenPwned, DeHashed, LeakCheck)
3. Search paste sites for exposed data (IntelX, Pastebin)
4. Search public code repositories for accidentally exposed credentials (GitHub Dorks, Grep.app)
5. Check for exposed databases or services via Shodan / Censys
6. Cross-reference findings to build a broader profile
7. Document all findings responsibly — never exploit or share raw credentials

**FR**
1. Identifier les adresses email, domaines ou pseudos cibles
2. Consulter les bases de données de fuites connues (HaveIBeenPwned, DeHashed, LeakCheck)
3. Rechercher sur les sites de paste les données exposées (IntelX, Pastebin)
4. Rechercher dans les dépôts publics les credentials accidentellement exposés (GitHub Dorks, Grep.app)
5. Vérifier les bases de données ou services exposés via Shodan / Censys
6. Recouper les résultats pour construire un profil plus large
7. Documenter tous les résultats de manière responsable — ne jamais exploiter ou partager des credentials bruts

---

## 💡 GitHub Dorks — Quick Reference

| Dork | Usage |
|------|-------|
| `filename:.env password` | Find exposed environment files |
| `filename:config.php dbpassword` | Find database credentials |
| `filename:id_rsa` | Find exposed SSH private keys |
| `"api_key" "secret"` | Find exposed API keys |
| `filename:.htpasswd` | Find exposed password files |

---

## 🚩 Key Red Flags / Signaux d'alerte

| Red Flag | Possible Implication |
|----------|---------------------|
| Credentials found in multiple breaches | High-value target or poor security hygiene |
| Corporate emails in breach databases | Potential insider threat or phishing risk |
| Exposed API keys in public repos | Active security vulnerability |
| Database exposed on Shodan | Misconfiguration or negligence |
| Credentials posted on paste sites | Active data leak in progress |

---

## 🕵️ Cybercriminal Ecosystems / Écosystèmes cybercriminels

**EN** — Before data appears in public breach databases, it circulates in cybercriminal ecosystems. Monitoring these sources gives earlier visibility on active leaks and threat actors.

**FR** — Avant d'apparaître dans les bases publiques, les données circulent dans les écosystèmes cybercriminels. Surveiller ces sources permet une visibilité anticipée sur les fuites actives et les acteurs malveillants.

### Key Platforms / Plateformes clés

| Platform | Type | Usage |
|----------|------|-------|
| Telegram channels | Messaging | Primary vector for data leaks and sales |
| RaidForums / BreachForums | Forums | Leaked data trading and sharing |
| XSS.is / Exploit.in | Russian forums | High-level cybercriminal activity |
| Dark web marketplaces | .onion sites | Credential and data sales |
| Paste sites (Pastebin, GhostBin) | Paste | Rapid public data dumps |

### Monitoring Methodology / Méthodologie de surveillance

**EN**
1. Identify relevant Telegram channels for your target sector
2. Monitor paste sites regularly for domain or email mentions
3. Set up alerts on IntelX for target domains and keywords
4. Track known cybercriminal forums for mentions of target organizations
5. Cross-reference with HaveIBeenPwned and DeHashed for validation
6. Document findings immediately — content disappears fast

**FR**
1. Identifier les canaux Telegram pertinents pour votre secteur cible
2. Surveiller régulièrement les sites de paste pour les mentions de domaines ou emails
3. Configurer des alertes sur IntelX pour les domaines et mots-clés cibles
4. Suivre les forums cybercriminels connus pour les mentions d'organisations cibles
5. Recouper avec HaveIBeenPwned et DeHashed pour validation
6. Documenter immédiatement — le contenu disparaît vite

### 🚩 Early Warning Signs / Signaux d'alerte précoces

| Signal | Implication |
|--------|-------------|
| Corporate data advertised on forums | Active breach in progress |
| Credentials posted on Telegram | Imminent exploitation risk |
| Domain mentioned in paste sites | Data leak or reconnaissance |
| Employee emails in fresh dumps | Targeted phishing risk |

---

## ⚠️ Ethics & Legality / Éthique & Légalité

**EN** — Breach data must only be used for investigative or defensive purposes. Never exploit, redistribute or use credentials for unauthorized access. Always operate within applicable law.

**FR** — Les données de fuites ne doivent être utilisées qu'à des fins investigatives ou défensives. Ne jamais exploiter, redistribuer ou utiliser des credentials pour un accès non autorisé. Toujours opérer dans le cadre légal en vigueur.

---

## 🔗 Useful Resources / Res
