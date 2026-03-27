# 💰 Crypto OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

### Blockchain Explorers

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| Etherscan | Ethereum blockchain explorer, transactions, wallet balances, smart contracts, token transfers | Explorateur de la blockchain Ethereum, transactions, soldes, contrats intelligents, transferts de tokens | Blockscout, Ethplorer | Free | 🇺🇸 USA | [etherscan.io](https://etherscan.io) |
| Blockchain.com Explorer | Bitcoin blockchain explorer, transactions, wallet history and UTXO analysis | Explorateur de la blockchain Bitcoin, transactions, historique de portefeuille et analyse UTXO | Blockstream.info, OXT | Free | 🇺🇸 USA | [blockchain.com/explorer](https://www.blockchain.com/explorer) |
| Blockstream.info | Privacy-focused Bitcoin blockchain explorer, no tracking, Tor accessible | Explorateur Bitcoin orienté vie privée, pas de tracking, accessible via Tor | Blockchain.com | Free | 🇺🇸 USA | [blockstream.info](https://blockstream.info) |
| TRONScan | TRON blockchain explorer, commonly used in illicit finance due to USDT on TRON | Explorateur de la blockchain TRON, fréquemment utilisé dans la finance illicite pour USDT sur TRON | Etherscan | Free | 🇨🇳 China | [tronscan.org](https://tronscan.org) |
| Solscan | Solana blockchain explorer, transactions, NFTs, DeFi activity | Explorateur de la blockchain Solana, transactions, NFTs, activité DeFi | Solana Explorer | Free | 🌐 International | [solscan.io](https://solscan.io) |

### Transaction Tracing & Visualization

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| Breadcrumbs | Free visual crypto transaction tracing, fund flow mapping and entity labeling | Traçage visuel gratuit des transactions crypto, cartographie des flux et étiquetage des entités | Arkham, Chainalysis | Free | 🇺🇸 USA | [breadcrumbs.app](https://www.breadcrumbs.app) |
| Arkham Intelligence | On-chain entity identification and deanonymization, links wallets to real-world identities | Identification et désanonymisation d'entités on-chain, relie les portefeuilles à des identités réelles | Breadcrumbs, Chainalysis | Freemium | 🇺🇸 USA | [platform.arkhamintelligence.com](https://platform.arkhamintelligence.com) |
| DeBankPro | DeFi wallet and multi-chain portfolio analysis, tracks cross-chain activity | Analyse de portefeuilles DeFi et multi-chaînes, suit l'activité cross-chain | Zapper, Zerion | Freemium | 🇨🇳 China | [debank.com](https://debank.com) |
| Crystal Blockchain | Blockchain transaction tracing and compliance risk scoring | Traçage des transactions blockchain et scoring de risque de conformité | Chainalysis, Elliptic, OXT | Paid | 🇺🇦 Ukraine | [crystalblockchain.com](https://crystalblockchain.com) |
| Chainalysis Reactor | Professional blockchain investigation platform, industry standard for LE and compliance | Plateforme professionnelle d'investigation blockchain, standard industrie pour les forces de l'ordre et la conformité | Elliptic, Crystal, OXT | Paid | 🇺🇸 USA | [chainalysis.com](https://www.chainalysis.com) |
| Elliptic | Enterprise blockchain analytics for financial institutions, AML/CFT compliance focus | Analyse blockchain pour les institutions financières, focus conformité AML/CFT | Chainalysis, Crystal, OXT | Paid | 🇬🇧 UK | [elliptic.co](https://www.elliptic.co) |
| OXT.me | Bitcoin transaction graph analysis | Analyse de graphique des transaction de bitcoin | Chainalysis, Elliptic, Crystal | Free | 🇫🇷 France | [OXT.me](https://oxt.me) |
### Cross-Chain & DeFi Intelligence

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| OSINT Industries | Cross-platform identity resolution, pivot from crypto wallet to email, phone and social accounts | Résolution d'identité multiplateforme, pivoter depuis un wallet crypto vers email, téléphone et comptes sociaux | Arkham, Maltego | Paid | 🇬🇧 UK | [osint.industries](https://www.osint.industries) |
| Maltego | Entity mapping including crypto addresses, correlate wallets with real-world identities | Cartographie d'entités incluant les adresses crypto, corréler les portefeuilles avec des identités réelles | SpiderFoot | Freemium | 🇩🇪 Germany | [maltego.com](https://www.maltego.com) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Identify the wallet address, note the blockchain (Bitcoin, Ethereum, TRON, Solana, etc.)
2. Explore transaction history via the appropriate blockchain explorer
3. Trace fund flows using visualization tools (Breadcrumbs, Arkham)
4. Identify exchange deposits, exchanges apply KYC, creating a potential identity link
5. Flag mixer or tumbler usage, indicates deliberate obfuscation attempt
6. Cross-reference addresses with known entities (sanctions lists, darknet market databases)
7. Look for clustering, multiple addresses controlled by the same entity
8. Pivot to identity data (OSINT Industries, Arkham) to link wallet to real-world identity
9. Document the full transaction trail with timestamps and block numbers

**FR**
1. Identifier l'adresse du portefeuille, noter la blockchain concernée (Bitcoin, Ethereum, TRON, Solana, etc.)
2. Explorer l'historique des transactions via l'explorateur blockchain approprié
3. Tracer les flux de fonds via des outils de visualisation (Breadcrumbs, Arkham)
4. Identifier les dépôts sur des exchanges, les exchanges appliquent le KYC, créant un lien d'identité potentiel
5. Signaler l'utilisation de mixers ou tumblers, indique une tentative délibérée d'obscurcissement
6. Recouper les adresses avec des entités connues (listes de sanctions, bases de marchés darknet)
7. Rechercher le clustering, adresses multiples contrôlées par la même entité
8. Pivoter vers les données d'identité (OSINT Industries, Arkham) pour relier le portefeuille à une identité réelle
9. Documenter l'intégralité de la chaîne de transactions avec horodatage et numéros de blocs

---

## 🚩 Key Red Flags / Signaux d'alerte

**ENG**
| Red Flag | Possible Implication |
|----------|---------------------|
| Use of mixing or tumbling services | Active attempt to obscure fund origin |
| Transactions to or from sanctioned addresses | Sanctions violation |
| Rapid fund movement across multiple wallets | Layering phase of money laundering |
| Deposits to privacy coins (Monero, Zcash) | Deliberate trail obfuscation |
| Links to known darknet market addresses | Illicit activity |
| Large transactions to unhosted wallets | Potential evasion of reporting obligations |
| Cross-chain bridge usage immediately after suspicious activity | Complex layering attempt |

**FR**
| Signal d’alerte | Implication possible |
| --------------- | -------------------- |
| Utilisation de services de mixage ou de tumbling | Tentative active de masquer l’origine des fonds |
| Transactions vers ou depuis des adresses sanctionnées | Violation des sanctions |
| Mouvement rapide de fonds entre plusieurs portefeuilles | Phase de layering du blanchiment d’argent |
| Dépôts vers des cryptomonnaies axées sur la confidentialité (Monero, Zcash) | Dissimulation délibérée de la traçabilité |
| Liens avec des adresses connues de marchés du darknet | Activité illicite |
| Transactions importantes vers des portefeuilles non hébergés | Contournement potentiel des obligations de déclaration |
| Utilisation d’un bridge cross-chain immédiatement après une activité suspecte | Tentative de layering complexe |


---

## 💡 Tips & Good Practices / Conseils

- Bitcoin and Ethereum are pseudonymous, not anonymous, the full transaction trail is permanently public
- TRON (TRC-20 USDT) is the preferred network for illicit stablecoin transfers, never overlook it
- Follow the money to exchanges, that is where identities get linked through KYC
- Mixers and tumblers are major red flags but the trail rarely disappears completely
- DeFi protocols add complexity but the blockchain trail always exists, cross-chain bridges included
- Arkham's entity labeling can save hour, always check it before manual tracing
- A single known address in a cluster can deanonymize the entire wallet network

**FR**
- Le Bitcoin et l'Ethereum sont pseudonymes, pas anonymes, l’historique complet des transactions est publiquement et définitivement accessible
- TRON (TRC-20 USDT) est le réseau privilégié pour les transferts illicites de stablecoins, ne l’ignore jamais
- Suis l’argent jusqu’aux exchanges, c’est là que les identités sont associées via le KYC
- Les mixeurs et les tumblers sont des signaux d’alerte majeurs, mais la piste ne disparaît que rarement complètement
- Les protocoles DeFi ajoutent de la complexité, mais la trace sur la blockchain existe toujours, y compris pour les ponts inter-chaînes
- L’étiquetage des entités par Arkham peut faire gagner des heures, vérifie-le toujours avant de tracer manuellement
- Une seule adresse connue dans un cluster peut dé-anonymiser l’ensemble du réseau de portefeuilles
---

---

## 🔗 Useful Resources / Ressources utiles

- [Chainalysis Crypto Crime Report](https://www.chainalysis.com/blog/crypto-crime-report/)
- [FATF Guidance on Virtual Assets](https://www.fatf-gafi.org)
- [Breadcrumbs App](https://www.breadcrumbs.app)
- [Bellingcat — Crypto Investigations](https://www.bellingcat.com)


>*Next [tool](../Tools/CyberBreaches&DarkWeb.md)*

> *Discover other [tools](../Tools)*

> *Back to [Main Playbook](../README.md)*
