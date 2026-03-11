# 🏢 Corporate Intelligence OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

### Company Registries

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| OpenCorporates | World's largest open database of companies (200M+ entities across 140+ jurisdictions) | Plus grande base de données ouverte d'entreprises (200M+ entités dans 140+ juridictions) | Orbis, national registries | Free (API paid) | 🇬🇧 UK | [opencorporates.com](https://opencorporates.com) |
| Pappers | French company registry with full financials, Kbis extracts, UBO data and alerts | Registre des entreprises françaises avec bilans complets, extraits Kbis, données UBO et alertes | Societe.com, Infogreffe | Free | 🇫🇷 France | [pappers.fr](https://www.pappers.fr) |
| Societe.com | French company information, directors, legal notices, financial data | Informations sur les entreprises françaises, dirigeants, annonces légales, données financières | Pappers, Infogreffe | Freemium | 🇫🇷 France | [societe.com](https://www.societe.com) |
| Orbis (Bureau van Dijk) | Global corporate intelligence with ownership structure mapping and financial data, industry standard | Intelligence corporate mondiale avec cartographie des structures de propriété et données financières | OpenCorporates | Paid | 🇳🇱 Netherlands | [bvdinfo.com](https://www.bvdinfo.com) |
| Companies House | UK company registry, directors, filings, financials, PSC register (beneficial owners) | Registre des entreprises britanniques, dirigeants, dépôts, financiers, registre PSC (bénéficiaires effectifs) | OpenCorporates | Free | 🇬🇧 UK | [find-and-update.company-information.service.gov.uk](https://find-and-update.company-information.service.gov.uk) |
| EDGAR (SEC) | US publicly listed company filings, 10-K, 10-Q, proxy statements, ownership disclosures | Dépôts des sociétés cotées américaines, 10-K, 10-Q, déclarations de mandataires, informations sur la propriété | OpenCorporates | Free | 🇺🇸 USA | [sec.gov/edgar](https://www.sec.gov/cgi-bin/browse-edgar) |
| GLEIF | Global Legal Entity Identifier database, connects LEI codes to corporate entities worldwide | Base de données mondiale des identifiants d'entités légales, relie les codes LEI aux entités corporate | OpenCorporates | Free | 🇨🇭 Switzerland | [gleif.org](https://www.gleif.org) |

### Leaked Documents & Investigative Databases

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| OCCRP Aleph | Leaked documents, corporate data and investigative databases (300M+ public records) | Documents fuités, données corporate et bases d'investigation (300M+ dossiers publics) | DocumentCloud, ICIJ Offshore Leaks | Free | 🌐 International | [aleph.occrp.org](https://aleph.occrp.org) |
| ICIJ Offshore Leaks | Panama Papers, Pandora Papers and Offshore Leaks searchable database | Base de données des Panama Papers, Pandora Papers et Offshore Leaks | OCCRP Aleph | Free | 🌐 International | [offshoreleaks.icij.org](https://offshoreleaks.icij.org) |

### Sanctions, PEPs & Risk Screening

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| OpenSanctions | Global sanctions lists and PEP (Politically Exposed Persons) database (aggregates 100+ official sources) | Listes de sanctions mondiales et base PEP (agrège 100+ sources officielles) | World-Check, Dow Jones Risk | Free (bulk API paid) | 🇩🇪 Germany | [opensanctions.org](https://www.opensanctions.org) |
| OFAC SDN List | US Treasury sanctions list, Specially Designated Nationals | Liste de sanctions du Trésor américain, Ressortissants spécialement désignés | OpenSanctions | Free | 🇺🇸 USA | [sanctionssearch.ofac.treas.gov](https://sanctionssearch.ofac.treas.gov) |
| EU Sanctions Map | EU consolidated sanctions list with company and individual search | Liste consolidée des sanctions de l'UE avec recherche d'entreprises et de personnes | OpenSanctions | Free | 🇪🇺 Europe | [sanctionsmap.eu](https://www.sanctionsmap.eu) |

### Mapping & Pivoting

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| Maltego | Visual corporate structure and relationship mapping, directors, shareholders, subsidiaries | Cartographie visuelle des structures corporate et relations, dirigeants, actionnaires, filiales | SpiderFoot, Neo4j | Freemium | 🇩🇪 Germany | [maltego.com](https://www.maltego.com) |
| LinkedIn | Identify key personnel, corporate structure and hiring patterns | Identifier le personnel clé, la structure corporate et les tendances de recrutement | Xing, Zoominfo | Freemium | 🇺🇸 USA | [linkedin.com](https://www.linkedin.com) |
| Wayback Machine | Recover historical website content, past directors, products, controversies | Récupérer le contenu historique des sites web, anciens dirigeants, produits, controverses | archive.ph | Free | 🇺🇸 USA | [web.archive.org](https://web.archive.org) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Identify the target company, full legal name, registration number, country of incorporation
2. Search national and international company registries (OpenCorporates, Pappers, Companies House)
3. Map the corporate structure, subsidiaries, parent companies, affiliated entities
4. Identify the Ultimate Beneficial Owner (UBO), not just the registered director
5. Identify key individuals, directors, shareholders, executives (LinkedIn, registries)
6. Cross-reference with sanctions and PEP lists (OpenSanctions, OFAC)
7. Search leaked documents databases (OCCRP Aleph, ICIJ Offshore Leaks)
8. Analyze financial data and flag anomalies
9. Document the full corporate network with source attribution

**FR**
1. Identifier l'entreprise cible, raison sociale complète, numéro d'enregistrement, pays de constitution
2. Rechercher dans les registres nationaux et internationaux (OpenCorporates, Pappers, Companies House)
3. Cartographier la structure corporate, filiales, maisons mères, entités affiliées
4. Identifier le bénéficiaire effectif ultime (UBO), pas seulement le dirigeant enregistré
5. Identifier les personnes clés, dirigeants, actionnaires, executives (LinkedIn, registres)
6. Recouper avec les listes de sanctions et PPE (OpenSanctions, OFAC)
7. Rechercher dans les bases de documents fuités (OCCRP Aleph, ICIJ Offshore Leaks)
8. Analyser les données financières et signaler les anomalies
9. Documenter l'intégralité du réseau corporate avec attribution des sources

---

## 🚩 Key Red Flags / Signaux d'alerte

**ENG**
| Red Flag | Possible Implication |
|----------|---------------------|
| Multiple companies registered at the same address | Shell company network |
| Frequent director changes | Deliberate obfuscation or instability |
| Ownership chain through multiple offshore jurisdictions | Tax evasion or money laundering |
| Company or director appears in sanctions lists | Direct sanctions exposure |
| No public financial filings despite legal obligation | Lack of transparency |
| Director shares name/address with dozens of other companies | Professional nominee director |
| Company incorporated shortly before a major contract | Purpose-built vehicle |

**FR**
| Signal d’alerte | Implication possible |
| ----------------| ---------------------|
| Plusieurs entreprises enregistrées à la même adresse | Réseau de sociétés écrans |
| Changements fréquents de dirigeant | Obfuscation délibérée ou instabilité |
| Chaîne de propriété passant par plusieurs juridictions offshore | Évasion fiscale ou blanchiment d’argent |
| L’entreprise ou le dirigeant apparaît sur des listes de sanction | Exposition directe aux sanctions |
| Absence de dépôts financiers publics malgré une obligation légale | Manque de transparence |
| Un dirigeant partage le même nom/adresse avec des dizaines d’autres entreprises | Directeur prête-nom professionnel |
| Entreprise créée peu avant l’obtention d’un contrat important | Structure créée pour une opération spécifique |

---

## 💡 Tips & Good Practices / Conseils

**ENG**
- Always search for the Ultimate Beneficial Owner (UBO) — not just the registered director
- Shell companies are often layered across multiple jurisdictions — follow each layer
- LinkedIn is underrated for mapping corporate structure and identifying key individuals
- Cross-reference company addresses — the same address shared by many companies is a major red flag
- Historical web archives reveal past directors, products or controversies that current sites hide
- Offshore leaks databases are freely searchable — run every target through them as a matter of routine
- GLEIF is essential for financial investigations — it links LEI codes to verified corporate identities

**FR**
- Cherche toujours le bénéficiaire effectif ultime (UBO), pas seulement le dirigeant enregistré
- Les sociétés écrans sont souvent réparties sur plusieurs juridictions, suis chaque niveau de la structure
- LinkedIn est sous-estimé pour cartographier la structure d’une entreprise et identifier les personnes clés
- Recoupe les adresses des entreprises, la même adresse partagée par de nombreuses sociétés est un signal d’alerte majeur
- Les archives web historiques révèlent d’anciens dirigeants, produits ou controverses que les sites actuels cachent
- Les bases de données de fuites offshore sont consultables gratuitement, vérifie systématiquement chaque cible dans ces bases
- GLEIF est essentiel pour les enquêtes financières, il relie les codes LEI à des identités d’entreprises vérifiées

---

## 🔗 Useful Resources / Ressources utiles

- [OCCRP Aleph](https://aleph.occrp.org)
- [ICIJ Offshore Leaks](https://offshoreleaks.icij.org)
- [OpenCorporates](https://opencorporates.com)
- [OpenSanctions](https://www.opensanctions.org)
- [Pappers](https://www.pappers.fr)
- [FATF Guidance on Beneficial Ownership](https://www.fatf-gafi.org)

>*Next [tool](Tools/Crypto.md)*

> *Discover other [tools](../Tools)*

> *Back to [Main Playbook](../README.md)*

