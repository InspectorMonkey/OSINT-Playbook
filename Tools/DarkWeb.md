# 🌑 Dark Web OSINT

> *Back to [Main Playbook](../README.md)*

---

## ⚠️ Legal Notice / Avertissement légal

**EN** — Dark web investigation must strictly comply with applicable law. This document is for informational and investigative purposes only. Never engage with illegal content or services.

**FR** — Toute investigation sur le dark web doit strictement respecter le cadre légal en vigueur. Ce document est à visée informative et investigative uniquement. Ne jamais interagir avec des contenus ou services illégaux.

---

## 🛠️ Tools / Outils

| Tool | Usage | Link |
|------|-------|------|
| Tor Browser | Anonymous access to .onion sites | [torproject.org](https://www.torproject.org) |
| OnionSearch | Search engine for .onion sites | [GitHub](https://github.com/megadose/OnionSearch) |
| Ahmia | Dark web search engine (clearnet access) | [ahmia.fi](https://ahmia.fi) |
| DarkSearch | Indexed dark web search engine | [darksearch.io](https://darksearch.io) |
| Shodan | Identifying hidden infrastructure | [shodan.io](https://www.shodan.io) |
| ExifTool | Metadata extraction from documents found | [exiftool.org](https://exiftool.org) |
| Ahmia | Ethical Tor hidden services search engine accessible from the clearnet | Moteur de recherche éthique des services cachés Tor accessible depuis le web classique | [ahmia.fi](https://ahmia.fi) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Define the scope — what are you looking for exactly?
2. Use clearnet search engines first (Ahmia, DarkSearch)
3. Access .onion sites only via Tor in a secure environment
4. Never download files directly — use a sandboxed VM
5. Document every finding with screenshots and timestamps
6. Cross-reference with clearnet sources to validate

**FR**
1. Définir le périmètre — que cherche-t-on exactement ?
2. Utiliser d'abord les moteurs accessibles depuis le clearnet (Ahmia, DarkSearch)
3. Accéder aux sites .onion uniquement via Tor dans un environnement sécurisé
4. Ne jamais télécharger de fichiers directement — utiliser une VM sandboxée
5. Documenter chaque découverte avec captures d'écran et horodatage
6. Recouper avec des sources clearnet pour valider

---

## 💡 Tips & Good Practices / Conseils

- Always operate from a dedicated, isolated machine or VM
- Never use your real identity or personal accounts
- Disable JavaScript in Tor Browser for better anonymity
- Use a VPN in addition to Tor when possible
- Be aware that many .onion sites are honeypots or scams
- Prioritize passive observation — never interact unless necessary

---

## 🔗 Useful Resources / Ressources utiles

- [Ahmia Search](https://ahmia.fi)
- [Tor Project Documentation](https://tb-manual.torproject.org)
- [Bellingcat — Dark Web Investigations](https://www.bellingcat.com)
