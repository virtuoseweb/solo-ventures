# V02 · Réseau de sites de leads locaux exclusifs (assainissement, élagage, ramonage, puis OLD et frelons)

> Statut : idée · Vague 1 · Score : 38–41/50 (A1, A2, A3 maintenant ; A4, A5 en vague 2) + G1 rank & rent + E1 upsell agence

## 1. Fiche
- **Modèle :** un site par **niche × département** (ex. `assainissement-24.fr`), simulateur de devis → lead **vendu à un seul pro par zone** → passage au loyer mensuel quand le volume est stable.
- **Cible :** propriétaires ruraux et périurbains avec une obligation ou un besoin saisonnier.
- **Payeurs :** artisans locaux. Prix : 60–120 € par lead exclusif, ou loyer de 150 à 400 € + paiement au-delà d'un quota.
- **Zone de départ :** 3 départements ruraux à forte part d'assainissement individuel et à SERP faible (à choisir au test : ex. Dordogne, Lot-et-Garonne, Sarthe, Morbihan, Vendée) ; Var, Bouches-du-Rhône et Landes pour OLD.

## 2. Étude de marché express
- **Prix constatés :** 25–45 € en partagé, 75–120 € en exclusif. Assainissement : 30–40 / 90–120 € (voir `docs/recherche/01`).
- **Pourquoi l'exclusif gagne :** 30 € partagé à 8 % de signature → 375 € par chantier ; 60 € exclusif à 30 % → 200 €. C'est l'argument de vente.
- **Moteurs légaux :**
  - Assainissement : travaux obligatoires 1 an après une vente non conforme ([service-public F447](https://www.service-public.gouv.fr/particuliers/vosdroits/F447)), panier de 6 à 12 k€.
  - Ramonage : obligation annuelle (règlement sanitaire départemental), pic d'octobre à décembre.
  - OLD : amende jusqu'à 50 €/m², information obligatoire de l'acquéreur ([F33298](https://www.service-public.gouv.fr/particuliers/vosdroits/F33298)).
  - Frelons : loi n° 2025-237 et décret du 29/12/2025.
- **Concurrence :** plateformes nationales qui revendent à 3–5 pros ; artisans ruraux peu visibles. Contrôler la SERP de 10 requêtes par département avant d'acheter un domaine.
- **Cadre légal (impératif) :**
  - Formulaire : case non précochée, **nom de l'acheteur affiché** (« Votre demande sera transmise à [Entreprise], qui vous rappellera »), preuve du consentement conservée 3 ans (loi n° 2025-594, depuis le 11/08/2026).
  - RGPD : liste des partenaires accessible, aucune revente à plusieurs acheteurs sans consentement explicite pour chacun.
  - Aucune niche de rénovation énergétique.
  - Contrat de location conforme L221-9 (arrêt de la CA de Rennes, 2026).

## 3. Business plan (par site niche × département)
| | M1 | M3 | M6 | M12 |
|---|---|---|---|---|
| Visites (SEO + Google Ads de test) | 150 | 600 | 1 200 | 1 800 |
| Leads (4 %) | 6 | 24 | 48 | 72 |
| Leads vendus (70 %) à 70 € | 290 € | 1 180 € | 2 350 € | — |
| Passage au loyer (300 € + quota) | — | — | — | 300–600 € fixes |
| Coûts (domaine, Ads de test 80 €/mois les 3 premiers mois) | 95 € | 95 € | 15 € | 15 € |

**Portefeuille cible à M12 :** 15 sites (5 niches × 3 départements). Hypothèse médiane : 8 sites rentables × 500 € = **4 000 €/mois**, presque sans temps passé une fois loués. Hypothèse basse : 4 sites × 300 € = 1 200 €/mois.

Fragilités : vendre et retenir l'artisan (c'est le point dur du rank & rent, voir l'audit Newp) ; délai SEO en rural (3 à 6 mois).

## 4. Plan d'action
- [ ] **J1** : moteur commun `lead-engine` (voir `docs/03-stack-commune.md`) : config par niche (questions du simulateur, fourchettes de prix, textes légaux) × département (communes INSEE, SPANC, arrêtés préfectoraux).
- [ ] **J2** : site pilote **assainissement × 1 département** : simulateur « combien coûte ma mise aux normes ? », 1 page par commune de plus de 2 000 habitants, page SPANC.
- [ ] **J3** : **vendre avant d'avoir le trafic** : appeler 10 installateurs et vidangeurs du département (Pages Jaunes, Google Maps). Offre : 3 leads gratuits, puis 70 € par lead exclusif ou 290 €/mois. Objectif : 1 pro signé.
- [ ] **J4** : Google Ads à 80 € sur les 15 requêtes les plus transactionnelles → mesurer le coût par lead réel.
- [ ] **J5–J7** : cloner pour élagage et ramonage (saison en cours) sur le même département.
- [ ] **J30** : kill / continuer / dupliquer. Seuil : CPL Ads < 25 € et 1 acheteur actif.
- [ ] **Janvier 2027** : lancer OLD (Var, Bouches-du-Rhône, Landes) et frelons (piégeage de printemps) pour être indexé avant le pic de mars.
- [ ] **Chaque acheteur** : proposer E1 (site + Google Business Profile + avis à 490 € + 49 €/mois) via l'agence.
