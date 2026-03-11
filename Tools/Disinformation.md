# 📢 Disinformation & Influence Operations OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

### Bot Detection & Account Analysis

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| Botometer | Twitter/X bot probability scoring — analyzes account behavior, content patterns and network | Scoring de probabilité de bot Twitter/X — analyse le comportement, les contenus et le réseau du compte | SparkToro, TweetAnalyzer | Free (API access) | 🇺🇸 USA | [botometer.osome.iu.edu](https://botometer.osome.iu.edu) |
| SparkToro | Audience analysis and fake follower detection, source quality assessment | Analyse d'audience et détection de faux abonnés, évaluation de la qualité des sources | Botometer | Freemium | 🇺🇸 USA | [sparktoro.com](https://sparktoro.com) |
| Whotwi | Twitter/X account analysis — followers, activity patterns, timeline and network map | Analyse de comptes Twitter/X — abonnés, patterns d'activité, timeline et carte réseau | Botometer | Freemium | 🇯🇵 Japan | [en.whotwi.com](https://en.whotwi.com) |

### Narrative Tracking & Claim Verification

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| Google Fact Check Explorer | Searchable database of verified fact-checks from accredited organizations worldwide | Base de données de fact-checks vérifiés provenant d'organisations accréditées dans le monde | AFP Fact Check, Snopes | Free | 🇺🇸 USA | [toolbox.google.com/factcheck](https://toolbox.google.com/factcheck/explorer) |
| Hoaxy | Visualize the spread of claims and fact-checks across Twitter/X — timeline and network view | Visualiser la propagation de contenus et fact-checks sur Twitter/X — vue chronologique et réseau | Gephi (manual) | Free | 🇺🇸 USA | [hoaxy.osome.iu.edu](https://hoaxy.osome.iu.edu) |
| IntelX | Search disinformation narratives across paste sites, forums and dark web sources | Rechercher des narratifs de désinformation sur les paste sites, forums et sources dark web | Maltego | Freemium | 🇩🇪 Germany | [intelx.io](https://intelx.io) |
| CrowdTangle | Meta social media content tracking — trace content virality across Facebook, Instagram | Suivi de contenus sur les réseaux sociaux Meta — tracer la viralité sur Facebook, Instagram | IntelX | Free (researchers) | 🇺🇸 USA | [crowdtangle.com](https://www.crowdtangle.com) |

### Synthetic Media Detection

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| Deepware Scanner | Deepfake video and image detection | Détection de deepfakes vidéo et image | Sensity, Hive Moderation | Freemium | 🌐 International | [deepware.ai](https://deepware.ai) |
| Sensity | AI-generated and synthetic media detection (enterprise grade) | Détection de médias synthétiques et générés par IA (niveau enterprise) | Deepware | Paid | 🇳🇱 Netherlands | [sensity.ai](https://sensity.ai) |
| Hive Moderation | AI-generated content detection for images, text and audio | Détection de contenu généré par IA pour images, texte et audio | Sensity, AI or Not | Freemium | 🇺🇸 USA | [hivemoderation.com](https://hivemoderation.com) |
| AI or Not | Fast AI-generated image detection | Détection rapide d'images générées par IA | Deepware, Hive | Free | 🌐 International | [aiornot.com](https://www.aiornot.com) |

### Monitoring & Archiving

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| Maltego | Map influence operation networks (accounts, domains, infrastructure and funding) | Cartographier les réseaux d'opérations d'influence (comptes, domaines, infrastructure et financement) | SpiderFoot | Freemium | 🇩🇪 Germany | [maltego.com](https://www.maltego.com) |
| Wayback Machine | Archive original content before deletion, critical for preserving evidence | Archiver le contenu original avant suppression, essentiel pour préserver les preuves | archive.ph | Free | 🇺🇸 USA | [web.archive.org](https://web.archive.org) |
| archive.ph | On-demand permanent page snapshots (resists takedowns) | Snapshots permanents de pages à la demande (résistants aux suppressions) | Wayback Machine | Free | 🌐 International | [archive.ph](https://archive.ph) |
| TweetDeck | Real-time Twitter/X monitoring across multiple search columns | Surveillance Twitter/X en temps réel sur de multiples colonnes de recherche | Hootsuite | Free | 🇺🇸 USA | [tweetdeck.twitter.com](https://tweetdeck.twitter.com) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Identify the narrative or claim to investigate (be precise about what you are verifying)
2. Trace the origin : who posted it first and when? Use reverse image search and Google date filtering
3. Analyze account behavior (creation date, posting frequency, follower/following ratio, avatar source)
4. Check for bot activity (Botometer) and indicators of coordinated inauthentic behavior
5. Map the spread of the narrative across platforms (Hoaxy, CrowdTangle)
6. Cross-reference with verified fact-checks (Google Fact Check Explorer)
7. Identify amplification networks — who is pushing this narrative and through what infrastructure?
8. Check for synthetic media — deepfakes, AI-generated text or manipulated images
9. Document the full information chain with archived sources

**FR**
1. Identifier le narratif ou l'affirmation à investiguer (être précis sur ce qu'on vérifie)
2. Tracer l'origine : qui l'a publié en premier et quand ? Utiliser la recherche inversée d'images et le filtrage par date de Google
3. Analyser le comportement des comptes (date de création, fréquence de publication, ratio followers, source de l'avatar)
4. Vérifier l'activité de bots (Botometer) et les indicateurs de comportements inauthentiques coordonnés
5. Cartographier la propagation du narratif sur les plateformes (Hoaxy, CrowdTangle)
6. Recouper avec les fact-checks vérifiés (Google Fact Check Explorer)
7. Identifier les réseaux d'amplification — qui pousse ce narratif et via quelle infrastructure ?
8. Vérifier la présence de médias synthétiques — deepfakes, texte généré par IA ou images manipulées
9. Documenter l'intégralité de la chaîne informationnelle avec sources archivées

---

## 💡 Indicators of Inauthentic Behavior / Indicateurs de comportement inauthentique

**ENG**
| Indicator | Description |
|-----------|-------------|
| Account age vs activity volume | New account with unusually high posting output |
| Follower/following ratio | Abnormally high following count, few genuine followers |
| Posting hours | Activity concentrated at unusual hours for the claimed timezone |
| Content repetition | Identical or near-identical content pushed across multiple accounts |
| Profile picture | Stock photo, AI-generated face or stolen image |
| Coordinated posting | Multiple accounts amplifying the same content within minutes |
| Linguistic patterns | Machine translation artifacts (unnatural phrasing or syntax) |
| Sudden engagement spikes | Rapid artificial inflation of likes, shares or retweets |

**FR**
| Indicateur | Description |
|------------|-------------|
|Âge du compte vs volume d'activité | Nouveau compte avec un volume de publication anormalement élevé |
| Ration abonnés/abonnements | Nombre d'abonnements très élevé, mais peu d'abonnés authentiques |
| Heures de publication | Activité concentrée à des heures inhabituelles pour le fuseau horaire déclaré |
| Répétition de contenu | Contenu identique ou quasi identique publié sur plusieurs comtpes |
| Photo de profil | Photo de banque, visage généré par IA ou image volée |
| Publication coordonnée | Plusieurs comptes amplifiant le même contenu en quelques minutes | 
| Schémas linguistiques | Artéfacts de traduction automatique (phrasé ou syntaxe peu naturels) | 
| Pics d'engagement soudains | Inflation artificielle rapide des likes, partages ou retweets |

---

## 🚩 Key Red Flags / Signaux d'alerte

**ENG**
| Red Flag | Possible Implication |
|----------|---------------------|
| Narrative origin traces to state-adjacent media | Coordinated state-sponsored operation |
| Same content in multiple languages posted simultaneously | Industrialized multilingual influence operation |
| Accounts created in bursts around the same date | Pre-positioned bot or sockpuppet network |
| Shared infrastructure across apparently unrelated accounts | Same operator behind multiple accounts |
| Profile picture identified as AI-generated | Inauthentic persona |
| Rapid deletion of original posts | Awareness of exposure |

**FR**
| Indicateur d'alerte | Implication possible | 
|---------------------|----------------------|
| Origine du récit traçable à des médias proches d'un Etat | Opération coordonée parrainée par un Etat |
| Même contenu publié simultanément dans plusieurs langues | Opération d'influence multilingue industrialisée |
| Comptes créés en rafale autour de la même date | Réseau de bots ou de faux comptes prépositionnées |
| Infrastructure partagée entre comptes apparement sans lien | Même opérateur derrière plusieurs comptes |
| Phoyo de profil identifiée comme générée par IA | Persona non authentique |
|Supression rapide des publications originales | Prise de conscience d'une exposition ou d'une détection |

---

## 💡 Tips & Good Practices / Conseils

**ENG**
- Always archive before engaging, content gets deleted immediately when exposure begins
- Check account creation dates, spikes around key political events are highly suspicious
- Reverse image search all profile pictures : stolen or AI-generated faces are common
- Linguistic analysis can identify machine translation or non-native speakers pretending to be local
- State-sponsored operations often leave infrastructure traces, check domains, hosting and registrant data
- Correlation is not attribution, document carefully before drawing any conclusions
- Look beyond Twitter/X, influence operations increasingly operate on Telegram, TikTok and local platforms

**FR**
- Archive toujours avant d’interagir, le contenu est souvent supprimé dès que l’exposition commence.
- Vérifie les dates de création des comptes, les pics autour d’événements politiques clés sont très suspects.
- Fais une recherche inversée sur toutes les photos de profil : les visages volés ou générés par IA sont fréquents.
- L’analyse linguistique peut révéler des traductions automatiques ou des locuteurs non natifs qui se font passer pour des locaux.
- Les opérations parrainées par des États laissent souvent des traces d’infrastructure, vérifie les domaines, l’hébergement et les données du registrant.
- La corrélation n’est pas une attribution, documente bien avant de tirer des conclusions.
- Ne te limite pas à Twitter/X, les opérations d’influence s’étendent de plus en plus à Telegram, TikTok et aux plateformes locales.

---

## 🔗 Useful Resources / Ressources utiles

- [EU DisinfoLab](https://www.disinfo.eu)
- [Bellingcat — Influence Operations](https://www.bellingcat.com)
- [Stanford Internet Observatory](https://io.stanford.edu)
- [First Draft — Verification Handbook](https://firstdraftnews.org)
- [DFRLab — Atlantic Council](https://www.atlanticcouncil.org/programs/digital-forensic-research-lab/)
- [EU vs Disinfo](https://euvsdisinfo.eu)
