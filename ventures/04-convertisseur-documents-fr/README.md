# V04 · Convertisseur de documents français (relevés bancaires, bulletins de paie → Excel / CSV / FEC)

> ❌ **TUÉ le 22/10/2026 avant lancement** : au moins 5 spécialistes FR, dont RelevExcel gratuit. Voir `docs/06-verification-concurrence.md`.
>
> Statut initial : idée · Vague 1 (après le MVP V01) · Score : 37/50 (C2) — clone d'un modèle US solo (Bank Statement Converter, 16 k$ de MRR vérifiés en interview)

## 1. Fiche
- **Principe :** déposer un PDF → tableau propre (date, libellé, débit, crédit, solde) avec contrôle de cohérence du solde → export Excel, CSV, OFX ou **FEC**.
- **Cible :** comptables et experts-comptables (reprise de dossiers, banques sans export), TPE, associations, particuliers (dossier de location, divorce, succession, dossier de surendettement).
- **Prix :** 5 pages gratuites, puis 9 €/mois (particulier), 29 €/mois (pro, 500 pages), 79 €/mois (cabinet).

## 2. Étude de marché express
- **Preuve US :** 10 puis 16 k$ de MRR pour environ 500 $ de coûts, fondateur seul ([Founder Reports](https://founderreports.com/interview/bank-statement-converter/)).
- **FR :** outils génériques (Smallpdf, Lido, Parseur) et export natif de certaines banques. **Aucun spécialiste des formats français identifié** (petites banques, Crédit Agricole régionaux, Banque Postale, relevés de prêts, bulletins de paie, avis de taxe foncière).
- **Différenciation :** contrôle du solde ligne à ligne (la confiance), export FEC, catégorisation automatique selon le plan comptable général.
- **Cadre légal :** données bancaires sensibles → hébergement UE, suppression automatique sous 24 h, aucun entraînement sur les fichiers, DPA pour les cabinets.

## 3. Business plan
| | M1 | M3 | M6 | M12 |
|---|---|---|---|---|
| Visites (SEO « convertir relevé [banque] en Excel ») | 300 | 2 000 | 6 000 | 12 000 |
| Clients payants | 3 | 25 | 80 | 180 |
| MRR (ARPU 15 €) | 45 € | 375 € | 1 200 € | 2 700 € |
| Coûts (API d'extraction par LLM ≈ 0,01–0,03 € par page [NV], hébergement) | 30 € | 80 € | 200 € | 400 € |

## 4. Plan d'action
- [ ] **J1** : collecter 30 relevés anonymisés de banques différentes (entourage, générateurs d'exemples) → jeu de test avec le résultat attendu.
- [ ] **J2–J3** : pipeline extraction de texte → parseur par banque (règles) → repli LLM avec sortie JSON structurée → contrôle du solde.
- [ ] **J4** : 1 page SEO par banque et par format (« relevé LCL en Excel », « relevé Boursobank en CSV »…).
- [ ] **J5** : Stripe + quota de pages. **Lien depuis V01** (même cible TPE).
- [ ] **J30** : seuil de 10 clients payants, sinon pivot vers le B2B cabinet uniquement.
