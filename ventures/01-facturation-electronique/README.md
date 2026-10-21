# V01 · Hub « facturation électronique » pour micro-entreprises et TPE

> ❌ **TUÉ le 22/10/2026 avant lancement** : comparateurs spécialisés déjà en place et offres gratuites (Tiime, Shine, Henrri, Indy, Abby). Voir `docs/06-verification-concurrence.md`.
>
> Statut initial : idée · Vague 1 · Score : 43/50 (B1 + E4 + C2 en upsell)

## 1. Fiche
- **Modèle :** site outil et guide (affiliation au lead / CPA) + service clé en main payant (E4).
- **Cible :** environ 2,6 millions de micro-entrepreneurs [NV] et les TPE qui ne savent pas quelle plateforme agréée choisir.
- **Payeurs :** éditeurs (Indy, Qonto, Shine, logiciels de facturation sur Affilae / PartnerStack / Awin) et clients du service à 149–290 €.
- **Zone :** France, puis Belgique (Peppol obligatoire en B2B depuis le 1er janvier 2026 [NV, à vérifier]).

## 2. Étude de marché express
- **Pourquoi maintenant :** réception obligatoire depuis le 1er septembre 2026, émission et e-reporting au 1er septembre 2027 pour TPE, PME et micro-entreprises ([Keobiz](https://www.keobiz.fr/le-mag/facturation-electronique-calendrier-2026-2027/)). 137 plateformes agréées en juillet 2026 : le choix est illisible, c'est l'opportunité.
- **Concurrence :** éditeurs (Abby, Dougs, Indy) et comparateurs génériques (La Fabrique du Net). **Créneau libre :** l'angle **par métier** (« facture électronique pour un taxi / une coiffeuse / un plombier / un formateur ») et l'**outil de diagnostic interactif** (statut, TVA, clients B2B/B2C → obligations et dates précises → 3 outils adaptés).
- **Monétisation vérifiée :** Indy annonce jusqu'à 345 € par lead, Qonto dès 15 €, Shine jusqu'à 200 € par parrainage (voir `docs/recherche/02`). Montants à confirmer après acceptation dans les programmes.
- **Cadre légal :** comparateur → afficher les critères de classement et la rémunération (L.111-7). Mention « liens affiliés » au-dessus de la ligne de flottaison. Aucun statut réglementé.
- **Risque :** les sanctions divergent selon les sources (15 € contre 50 € par facture) → citer seulement impots.gouv.fr.

## 3. Business plan (hypothèses prudentes)
| | M1 | M3 | M6 | M12 |
|---|---|---|---|---|
| Visites / mois | 500 | 4 000 | 15 000 | 30 000 (pic juin–sept. 2027) |
| Diagnostics réalisés (25 %) | 125 | 1 000 | 3 750 | 7 500 |
| Conversions affiliées (2 % des visites) | 10 | 80 | 300 | 600 |
| Revenu affilié moyen 40 € | 400 € | 3 200 € | 12 000 € | 24 000 € |
| Services clé en main à 190 € | 2 | 8 | 20 | 30 |
| **CA total** | **780 €** | **4 720 €** | **15 800 €** | **29 700 €** |
| Coûts (domaine, ads tests, outils) | 150 € | 300 € | 500 € | 800 € |

Hypothèse la plus fragile : les 40 € moyens par conversion. À valider dès le premier mois via les dashboards des réseaux. **La fenêtre se referme après septembre 2027** : il faut donc récupérer la valeur pendant 11 mois, puis pivoter vers C2 (convertisseur) et la conformité e-reporting.

## 4. Plan d'action
- [ ] **J1** : domaine (.fr), inscription Indy, Qonto, Shine, Awin, Affilae, PartnerStack ; liste des 137 plateformes agréées (impots.gouv.fr) en JSON.
- [ ] **J2** : diagnostic interactif « Quelles obligations pour moi et à quelle date ? » (Astro + îlot React, aucune donnée stockée sans consentement).
- [ ] **J3** : 30 pages programmatiques « facture électronique + métier » générées depuis un JSON de métiers (codes APE, B2B ou B2C, TVA), relues une par une.
- [ ] **J4** : comparateur des 10 outils les plus adaptés aux micro-entreprises, page « méthodologie et rémunération ».
- [ ] **J5** : offre « mise en conformité en 48 h » (Stripe Payment Link à 190 €) ; contenus LinkedIn et TikTok « 60 secondes pour comprendre ».
- [ ] **J7–J30** : Search Console, 3 contenus par semaine, partenariats avec des comptables (commission de 20 % sur le service).
- [ ] **J30** : décision. Signal minimal : 1 000 visites et 10 conversions.
