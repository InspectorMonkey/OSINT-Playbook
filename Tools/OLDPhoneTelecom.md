# 📞 Phone & Telecom OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

### Reverse Phone Lookup & Carrier Intelligence

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| PhoneInfoga | Advanced phone number OSINT framework (carrier lookup, reputation scan, pivot to social accounts) | Framework OSINT avancé pour les numéros de téléphone (lookup opérateur, scan de réputation, pivot vers comptes sociaux) | Truecaller, NumLookup | Free | 🇫🇷 France | [GitHub](https://github.com/sundowndev/phoneinfoga) |
| Truecaller | Caller ID and reverse phone lookup (crowdsourced database of 3B+ numbers) | Identification d'appelant et lookup inversé (base crowdsourcée de plus de 3 milliards de numéros) | Sync.me, EmobileTracker | Freemium | 🇸🇪 Sweden | [truecaller.com](https://www.truecaller.com) |
| EmobileTracker | Worldwide reverse phone lookup (carrier, line type, approximate region, spam reports) | Reverse lookup téléphonique mondial (opérateur, type de ligne, région approximative, signalements spam) | Truecaller, NumLookup | Free | 🌐 International | [emobiletracker.com](https://www.emobiletracker.com) |
| NumLookup | Phone number lookup with carrier info and line type detection | Lookup de numéros avec informations sur l'opérateur et le type de ligne | EmobileTracker, Carrier Lookup | Free | 🌐 International | [numlookup.com](https://www.numlookup.com) |
| Sync.me | Reverse phone lookup and caller ID with social media enrichment | Lookup inversé et identification d'appelant avec enrichissement réseaux sociaux | Truecaller, EmobileTracker | Freemium | 🇮🇱 Israel | [sync.me](https://sync.me) |
| Carrier Lookup | Identify carrier and line type (mobile, landline, VoIP) by phone number | Identifier l'opérateur et le type de ligne (mobile, fixe, VoIP) par numéro de téléphone | EmobileTracker, NumLookup | Free | 🇺🇸 USA | [carrierlookup.com](https://www.carrierlookup.com) |
| OpenCNAM | Caller name (CNAM) lookup, US-focused, useful for business number identification | Recherche du nom d'appelant (CNAM), centré sur les États-Unis, utile pour l'identification des numéros professionnels | Truecaller | Freemium | 🇺🇸 USA | [opencnam.com](https://www.opencnam.com) |

### Breach & Identity Pivot

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| OSINT Industries | Real-time pivot from phone number to email, username, social accounts and geospatial data | Pivot temps réel d'un numéro de téléphone vers email, pseudo, comptes sociaux et données géospatiales | Epieos, Predicta Search | Paid | 🇬🇧 UK | [osint.industries](https://www.osint.industries) |
| Epieos | Phone number → linked Google account and registered platforms | Numéro de téléphone → compte Google associé et plateformes liées | OSINT Industries | Freemium | 🌐 International | [epieos.com](https://epieos.com) |
| IntelX | Search phone numbers in paste sites and leaked databases | Rechercher des numéros de téléphone dans les paste sites et bases de données fuités | DeHashed | Freemium | 🇩🇪 Germany | [intelx.io](https://intelx.io) |
| DeHashed | Phone number search across breach datasets | Recherche de numéros de téléphone dans les jeux de données de fuites | IntelX, LeakCheck | Freemium | 🇺🇸 USA | [dehashed.com](https://www.dehashed.com) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Identify the target phone number : note country code and number format
2. Determine carrier and line type : mobile, landline or VoIP (EmobileTracker, Carrier Lookup)
3. Run reverse lookup to find associated name and identity (Truecaller, Sync.me, EmobileTracker)
4. Pivot from phone to linked online accounts (OSINT Industries, Epieos)
5. Search the number in breach databases (IntelX, DeHashed)
6. Check if the number is linked to WhatsApp, Telegram or Signal : look for profile pictures and bios
7. Search the number in Google and Yandex with quotes: `"+1XXXXXXXXXX"`
8. Document all findings with timestamps

**FR**
1. Identifier le numéro de téléphone cible : noter l'indicatif pays et le format
2. Déterminer l'opérateur et le type de ligne : mobile, fixe ou VoIP (EmobileTracker, Carrier Lookup)
3. Effectuer un lookup inversé pour trouver le nom et l'identité associés (Truecaller, Sync.me)
4. Pivoter du téléphone vers les comptes en ligne liés (OSINT Industries, Epieos)
5. Rechercher le numéro dans les bases de données de fuites (IntelX, DeHashed)
6. Vérifier si le numéro est lié à WhatsApp, Telegram ou Signal : chercher photos de profil et bios
7. Rechercher le numéro sur Google et Yandex entre guillemets : `"+33XXXXXXXXX"`
8. Documenter tous les résultats avec horodatage

---

## 🚩 Key Red Flags / Signaux d'alerte

**ENG**
| Red Flag | Possible Implication |
|----------|---------------------|
| VoIP number with no carrier attribution | Anonymous or disposable number |
| Number linked to multiple identities | Shared, recycled or fraudulent number |
| Number found in breach databases | Compromised or exposed identity |
| No results across any platform | Deliberate anonymization |
| Burner app provider (Google Voice, TextNow, etc.) | Temporary use — low traceability |

**FR**
| Signal d’alerte | Implication possible |
| ------------------------------------------------------------------ | ------------------------------------------ |
| Numéro VoIP sans attribution d’opérateur | Numéro anonyme ou jetable |
| Numéro lié à plusieurs identités | Numéro partagé, recyclé ou frauduleux |
| Numéro trouvé dans des bases de données de fuites | Identité compromise ou exposée |
| Aucun résultat sur aucune plateforme | Anonymisation délibérée |
| Fournisseur d’application « burner » (Google Voice, TextNow, etc.) | Utilisation temporaire, faible traçabilité |


---

## 💡 Tips & Good Practices / Conseils

**ENG**
- Always search the number with AND without country code — results differ
- VoIP numbers are significantly harder to trace — flag them immediately
- WhatsApp, Telegram and Signal accounts are often linked to phone numbers — check profile pictures and bios immediately after lookup
- A phone number appearing in breach data is a high-value pivot point — it may unlock email, name, address
- Truecaller relies on crowdsourced data — coverage varies by country and region
- Always run Google and Yandex quoted searches — users leave phone numbers in forums, listings and social bios

**FR**
- Recherche toujours le numéro avec ET sans indicatif pays : les résultats diffèrent
- Les numéros VoIP sont nettement plus difficiles à tracer : signale-les immédiatement
- Les comptes WhatsApp, Telegram et Signal sont souvent liés aux numéros de téléphone : vérifie les photos de profil et les biographies immédiatement après la recherche
- Un numéro de téléphone apparaissant dans des données de fuite est un point de pivot de grande valeur : il peut révéler un e-mail, un nom ou une adresse
- Truecaller repose sur des données issues du crowdsourcing : la couverture varie selon les pays et les régions
- Effectue toujours des recherches entre guillemets sur Google et Yandex : les utilisateurs laissent des numéros de téléphone dans des forums, des annonces et des biographies de réseaux sociaux


---

## 🔗 Useful Resources / Ressources utiles

- [PhoneInfoga GitHub](https://github.com/sundowndev/phoneinfoga)
- [IntelX](https://intelx.io)
- [Truecaller](https://www.truecaller.com)
