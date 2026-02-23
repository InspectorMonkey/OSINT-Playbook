# 📞 Phone & Telecom OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

| Tool | Usage | Link |
|------|-------|------|
| NumLookup | Phone number lookup and carrier info | [numlookup.com](https://www.numlookup.com) |
| Truecaller | Caller ID and phone number search | [truecaller.com](https://www.truecaller.com) |
| PhoneInfoga | Advanced phone number OSINT framework | [GitHub](https://github.com/sundowndev/phoneinfoga) |
| Sync.me | Reverse phone lookup | [sync.me](https://sync.me) |
| OpenCNAM | Caller name lookup (US-focused) | [opencnam.com](https://www.opencnam.com) |
| IntelX | Search phone numbers in leaked databases | [intelx.io](https://intelx.io) |
| DeHashed | Phone number search in breach data | [dehashed.com](https://www.dehashed.com) |
| Carrier Lookup | Identify carrier and line type | [carrierlookup.com](https://www.carrierlookup.com) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Identify the target phone number and country code
2. Determine carrier and line type (mobile, landline, VoIP)
3. Run reverse lookup to find associated identity (Truecaller, Sync.me)
4. Search number in breach databases (IntelX, DeHashed)
5. Check if number is linked to social media accounts
6. Search number in Google and Yandex with quotes : `"+33XXXXXXXXX"`
7. Document all findings with timestamps

**FR**
1. Identifier le numéro de téléphone cible et l'indicatif pays
2. Déterminer l'opérateur et le type de ligne (mobile, fixe, VoIP)
3. Effectuer une recherche inversée pour trouver l'identité associée (Truecaller, Sync.me)
4. Rechercher le numéro dans les bases de données de fuites (IntelX, DeHashed)
5. Vérifier si le numéro est lié à des comptes sur les réseaux sociaux
6. Rechercher le numéro sur Google et Yandex entre guillemets : `"+33XXXXXXXXX"`
7. Documenter tous les résultats avec horodatage

---

## 💡 Tips & Good Practices / Conseils

- VoIP numbers are harder to trace — they can be registered anonymously
- Always search the number with and without country code
- WhatsApp, Telegram and Signal accounts are often linked to phone numbers — check profile pictures and bios
- A phone number appearing in breach data is a major pivot point
- Truecaller relies on crowdsourced data — results may vary by region
- Search the number in quotes on Google : surprises happen frequently

---

## 🚩 Key Red Flags / Signaux d'alerte

| Red Flag | Possible Implication |
|----------|---------------------|
| VoIP number with no carrier info | Anonymous or disposable number |
| Number linked to multiple identities | Shared or recycled number |
| Number found in breach databases | Compromised identity |
| No results across all platforms | Deliberate anonymization |

---

## 🔗 Useful Resources / Ressources utiles

- [PhoneInfoga](https://github.com/sundowndev/phoneinfoga)
- [IntelX](https://intelx.io)
- [Truecaller](https://www.truecaller.com)
