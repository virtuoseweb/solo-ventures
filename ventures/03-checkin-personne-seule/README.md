# V03 · Service de check-in quotidien pour les personnes seules et les parents âgés

> Statut : idée · Vague 1 · Score : 42/50 (C1) — modèle importé des US (Snug Safety, CheckinBee) et de Chine (« Are You Dead? »)

## 1. Fiche
- **Principe :** chaque jour, à l'heure choisie, la personne reçoit un SMS ou un appel automatisé (« Tout va bien ? Répondez 1 »). Sans réponse au bout de X minutes → relance → alerte SMS et e-mail à 1–3 proches.
- **Pas d'application à installer** pour la personne âgée (c'est l'avantage sur la téléassistance et sur les apps). App ou PWA pour les jeunes actifs seuls (check-in en un tap).
- **Payeur :** les enfants, 4,90 €/mois ou 49 €/an (essai de 30 jours : les trials de 17 à 32 jours convertissent le mieux selon RevenueCat). B2B : CCAS, bailleurs sociaux, mutuelles, résidences seniors (1–2 € par bénéficiaire et par mois).
- **Zone :** France, puis Belgique, Suisse, Québec (même produit, en français).

## 2. Étude de marché express
- **Demande :** environ 12 M de personnes vivent seules en France (Insee 2023 relayé par la presse, à confirmer). Les canicules relancent chaque été le sujet de l'isolement (registres canicule des mairies).
- **Preuves :** Snug Safety (9,99 $/mois, 20 M de check-ins), CheckinBee (14 $/mois par SMS), un actif similaire en vente sur Acquire ; « Are You Dead? » n° 1 des apps payantes en Chine en janvier 2026.
- **Concurrence FR :** téléassistance classique (Présence Verte, Filien ADMR, Nexecur [NV]) à 10–30 €/mois avec un boîtier et une logique d'urgence. **Aucun service grand public de check-in léger identifié.**
- **Cadre légal :**
  - **Ne pas se présenter comme un dispositif médical ni comme de la téléassistance** : c'est un service de rappel et d'alerte aux proches, sans promesse de secours. CGU claires : « ne remplace pas le 15 / 112 ».
  - Données : pas de données de santé collectées ; consentement de la personne suivie (et non seulement de l'enfant payeur).
  - SMS : coût d'environ 0,05–0,08 € par SMS en France [NV] → environ 2 € par mois et par utilisateur avec relances, à intégrer dans le prix.
- **Risque :** responsabilité en cas d'alerte non envoyée → redondance (2 fournisseurs SMS), journal des envois, CGU rédigées par un avocat (≈ 300–500 €, seule vraie dépense).

## 3. Business plan
| | M1 | M3 | M6 | M12 |
|---|---|---|---|---|
| Inscriptions à l'essai | 30 | 150 | 400 | 1 000 (cumul) |
| Abonnés payants (40 % des essais) | 0 | 45 | 150 | 380 |
| MRR (4,30 € net moyen) | 0 € | 195 € | 645 € | 1 630 € |
| Contrats B2B (CCAS, bailleurs) | 0 | 0 | 1 | 3 (≈ 600 € de MRR) |
| Coûts (SMS, téléphonie, avocat la première fois) | 500 € | 120 € | 350 € | 850 € |

**Potentiel à 24 mois :** 1 500 abonnés + 10 contrats B2B ≈ 8 k€/mois. Actif revendable (multiple de 2 à 3× le profit annuel sur Acquire).

## 4. Plan d'action
- [ ] **J1** : landing page « Votre maman vit seule ? Un SMS par jour, et vous êtes prévenu si elle ne répond pas » + liste d'attente + prix affiché.
- [ ] **J2** : test de la demande : 50 € de Meta Ads ciblant les 40–60 ans + 3 posts dans des groupes Facebook d'aidants. Seuil : 3 % des visiteurs inscrits.
- [ ] **J3–J5** : MVP : Vercel Cron toutes les 5 minutes + base Postgres + API SMS (Twilio, Brevo, OVH SMS) + Stripe Billing. Réponse par SMS entrant (webhook).
- [ ] **J6** : 10 bêta-testeurs gratuits (entourage, associations d'aidants) ; mesurer le taux de réponse et les fausses alertes.
- [ ] **J30** : ouverture payante. **J60** : démarcher 5 CCAS (registres canicule obligatoires depuis 2004 : argument « suivi quotidien hors épisode »).
