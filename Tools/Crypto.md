# 💰 Crypto OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

| Tool | Usage | Link |
|------|-------|------|
| Chainalysis Reactor | Professional blockchain investigation platform | [chainalysis.com](https://www.chainalysis.com) |
| Elliptic | Crypto transaction tracing and risk scoring | [elliptic.co](https://www.elliptic.co) |
| Etherscan | Ethereum blockchain explorer | [etherscan.io](https://etherscan.io) |
| Blockchain.com Explorer | Bitcoin blockchain explorer | [blockchain.com](https://www.blockchain.com/explorer) |
| Breadcrumbs | Free crypto transaction tracing | [breadcrumbs.app](https://www.breadcrumbs.app) |
| Crystal Blockchain | Transaction tracing and compliance | [crystalblockchain.com](https://crystalblockchain.com) |
| Maltego | Entity mapping including crypto addresses | [maltego.com](https://www.maltego.com) |
| OSINT Industries | Cross-platform identity resolution | [osint.industries](https://osint.industries) |
| DeBankPro | DeFi wallet and portfolio analysis | [debank.com](https://debank.com) |
| Arkham Intelligence | On-chain entity identification | [arkhamintelligence.com](https://platform.arkhamintelligence.com) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Identify the wallet address (Bitcoin, Ethereum, etc.)
2. Explore transaction history via blockchain explorer (Etherscan, Blockchain.com)
3. Trace fund flows using visualization tools (Breadcrumbs, Chainalysis)
4. Identify exchange deposits — exchanges apply KYC, creating a potential identity link
5. Cross-reference addresses with known entities (sanctions lists, darknet markets)
6. Look for clustering — addresses controlled by the same entity
7. Document the full transaction trail with timestamps

**FR**
1. Identifier l'adresse du portefeuille (Bitcoin, Ethereum, etc.)
2. Explorer l'historique des transactions via les explorateurs blockchain (Etherscan, Blockchain.com)
3. Tracer les flux de fonds via des outils de visualisation (Breadcrumbs, Chainalysis)
4. Identifier les dépôts sur des exchanges — les exchanges appliquent le KYC, créant un lien d'identité potentiel
5. Recouper les adresses avec des entités connues (listes de sanctions, marchés darknet)
6. Rechercher le clustering — adresses contrôlées par la même entité
7. Documenter l'intégralité de la chaîne de transactions avec horodatage

---

## 💡 Tips & Good Practices / Conseils

- Bitcoin is pseudonymous, not anonymous — transactions are permanently public
- Follow the money to exchanges — that's where identities get revealed
- Mixers and tumblers are used to obscure trails — flag them immediately
- DeFi protocols add complexity but the blockchain trail always exists
- Cross-chain bridges are increasingly used to move funds and complicate tracing
- Always note the cryptocurrency type — each blockchain has its own explorer

---

## 🚩 Key Red Flags / Signaux d'alerte

| Red Flag | Possible Implication |
|----------|---------------------|
| Use of mixing services | Attempt to obscure fund origin |
| Transactions to sanctioned addresses | Sanctions violation |
| Rapid fund movement across multiple wallets | Layering (money laundering) |
| Links to darknet market addresses | Illicit activity |
| Large transactions to unhosted wallets | Potential evasion |

---

## 🔗 Useful Resources / Ressources utiles

- [Chainalysis Crypto Crime Report](https://www.chainalysis.com/blog/crypto-crime-report/)
- [Bellingcat — Crypto Investigations](https://www.bellingcat.com)
- [FATF Guidance on Virtual Assets](https://www.fatf-gafi.org)
- [Breadcrumbs App (free tracing)](https://www.breadcrumbs.app)
