# 📰 Open Sources OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

| Tool | Usage | Link |
|------|-------|------|
| Google Dorks | Advanced search using Google operators | — |
| OSINT Framework | OSINT tools directory by category | [osintframework.com](https://osintframework.com) |
| Wayback Machine | Web archives and deleted content | [web.archive.org](https://web.archive.org) |
| IntelTechniques | Custom search tools by Michael Bazzell | [inteltechniques.com](https://inteltechniques.com) |
| WHOIS | Domain registration and ownership info | [whois.domaintools.com](https://whois.domaintools.com) |
| Shodan | Search engine for connected devices | [shodan.io](https://www.shodan.io) |
| Censys | Internet infrastructure scanning | [censys.io](https://censys.io) |
| OpenCorporates | Global company registry database | [opencorporates.com](https://opencorporates.com) |
| Pappers | French company registry (France) | [pappers.fr](https://www.pappers.fr) |
| Spokeo | People search engine (US-focused) | [spokeo.com](https://www.spokeo.com) |
| NMapper | Online platform for network scanning and OSINT reconnaissance tools | Plateforme en ligne de scanning réseau et d'outils de reconnaissance OSINT | [nmmapper.com](https://www.nmmapper.com) |
| C99 Subdomain Finder | Subdomain discovery with Cloudflare bypass detection and historical records | Découverte de sous-domaines avec détection de bypass Cloudflare et historique | [subdomainfinder.c99.nl](https://subdomainfinder.c99.nl) |
| SubdomainRadar | All-in-one subdomain enumeration, port scanning and vulnerability detection | Énumération de sous-domaines tout-en-un avec scan de ports et détection de vulnérabilités | [subdomainradar.io](https://subdomainradar.io) |
| SecurityTrails | DNS history, subdomain enumeration and infrastructure intelligence | Historique DNS, énumération de sous-domaines et renseignement sur les infrastructures | [securitytrails.com](https://securitytrails.com) |
| PugRecon | Passive subdomain enumeration database with billions of indexed records | Base de données passive d'énumération de sous-domaines avec des milliards d'entrées indexées | [pugrecon.com](https://pugrecon.com) |
| PublicWWW | Source code search engine for HTML, JS and CSS pivot by shared identifiers | Moteur de recherche dans le code source web avec pivoting par identifiants partagés | [publicwww.com](https://publicwww.com) |
| NerdyData | Source code search engine with tech stack and company data enrichment | Moteur de recherche dans le code source avec enrichissement du stack technologique et des données d'entreprise | [nerdydata.com](https://www.nerdydata.com) |
| Grep.app | Source code search across public GitHub repositories with regex support | Recherche dans le code source de dépôts GitHub publics avec support des expressions régulières | [grep.app](https://grep.app) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Start broad — identify all available public sources
2. Use Google Dorks to surface hidden or indexed content
3. Check domain history and registration via WHOIS and Wayback Machine
4. Search company registries for corporate structures and key individuals
5. Cross-reference across multiple sources before drawing conclusions
6. Archive everything — pages disappear fast

**FR**
1. Commencer large — identifier toutes les sources publiques disponibles
2. Utiliser les Google Dorks pour faire remonter des contenus cachés ou indexés
3. Vérifier l'historique et l'enregistrement des domaines via WHOIS et Wayback Machine
4. Consulter les registres d'entreprises pour les structures et personnes clés
5. Recouper sur plusieurs sources avant de tirer des conclusions
6. Tout archiver — les pages disparaissent vite

---

## 💡 Google Dorks — Quick Reference

| Operator | Usage | Example |
|----------|-------|---------|
| `site:` | Search within a specific site | `site:linkedin.com "John Doe"` |
| `filetype:` | Search for specific file types | `filetype:pdf "annual report"` |
| `intitle:` | Search in page titles | `intitle:"index of" passwords` |
| `inurl:` | Search in URLs | `inurl:admin login` |
| `"..."` | Exact phrase search | `"John Doe" "Paris"` |
| `-` | Exclude a term | `apple -fruit` |

---

## 💡 Tips & Good Practices / Conseils

- Combine multiple Dorks for more precise results
- Always check the cached version of a page — the live version may have changed
- Company registries are underused but extremely valuable for financial investigations
- Cross-border investigations : adapt your tools to the target country
- Use Wayback Machine systematically to recover deleted content

---

## 🔗 Useful Resources / Ressources utiles

- [Google Dorks Cheatsheet — Exploit-DB](https://www.exploit-db.com/google-hacking-database)
- [OSINT Framework](https://osintframework.com)
- [IntelTechniques Blog](https://inteltechniques.com/blog/)
- [Bellingcat Online Investigation Toolkit](https://docs.google.com/spreadsheets/d/18rtqh8EG2q1xBo2cLNyhIDuK9jrPGwYr9DI2UncoqJQ)
