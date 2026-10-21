# Méthode de sélection des niches

Objectif : un portefeuille de petits actifs qui rapportent vite et sans risque, à côté de l'agence et du logiciel.
Une niche n'entre en production que si elle passe les **5 filtres éliminatoires**, puis obtient un **score ≥ 32/50**.

## 1. Filtres éliminatoires (un seul « non » suffit à rejeter)

| # | Filtre | Question | Preuve exigée |
|---|--------|----------|---------------|
| F1 | Besoin réel | Des gens cherchent ou paient **déjà** pour ça ? | Volume de recherche (Google Keyword Planner, Ahrefs, Semrush), ou acheteurs existants (plateformes de leads, annonceurs Google Ads sur la requête) |
| F2 | Monétisation identifiée | Qui paie, combien, par quel canal ? | Prix de lead constaté, programme d'affiliation actif, prix concurrent |
| F3 | Légalité | Pas d'interdiction de démarchage, de statut obligatoire non obtenable (ORIAS, avocat…), ni de zone grise RGPD | Texte de loi vérifié |
| F4 | Coût d'entrée | MVP ≤ 300 € hors temps, et ≤ 5 jours de travail avec l'IA | Budget détaillé |
| F5 | Concurrence | Page 1 Google non verrouillée par des marques géantes sur **la requête longue traîne locale** | Analyse manuelle de la SERP sur 10 requêtes |

## 2. Grille de score (10 critères × 5 points)

| Critère | 1 | 3 | 5 |
|---------|---|---|---|
| Valeur d'une conversion | < 5 € | 20–50 € | > 100 € |
| Urgence / intention | Curiosité | Projet à 3 mois | Urgence (< 48 h) |
| Concurrence SERP | Nationaux partout | Mixte | Annuaires faibles, forums |
| Récurrence | One shot | Annuel | Mensuel / abonnement |
| Vitesse au premier euro | > 6 mois | 2–3 mois | < 30 jours |
| Automatisable par IA | Travail manuel | Partiel | Quasi total |
| Duplicabilité (départements, pays, niches sœurs) | Non | 5–10 copies | 100+ copies (programmatique) |
| Défendabilité (data, outil, relation acheteur) | Aucune | Moyenne | Forte |
| Risque réglementaire / plateforme | Fort | Moyen | Nul |
| Synergie agence / Waimia | Aucune | Indirecte | Upsell direct (clients agence, prospects) |

**Lecture :** ≥ 40 = lancement immédiat · 32–39 = lancement en vague 2 · < 32 = backlog.

## 3. Règle de validation avant de construire (« test 7 jours »)

Ne rien construire de lourd avant un signal :
1. **Leads / devis :** landing page + Google Ads à 50–100 € sur 1 département. Signal = CPL payé < 40 % du prix de revente, **et** 1 acheteur prêt à payer (appel ou message à 10 pros locaux).
2. **Affiliation :** 1 page outil + 5 articles. Signal = indexation et impressions Search Console en 21 jours, ou un clic affilié via Pinterest/TikTok.
3. **App freemium :** landing + liste d'attente + vidéo TikTok/Reels. Signal = > 200 inscrits ou 3 % de conversion vers la liste.
4. **E-commerce :** précommande ou dropshipping local. Signal = 10 ventes avant tout stock.
5. **Micro drop service :** offre sur Malt / Fiverr / LinkedIn. Signal = 3 clients payants.

## 4. Règles du portefeuille

- **Kill rule :** pas de signal à J+30 (test) ou pas de revenu à J+90 → on arrête ou on pivote, sans état d'âme.
- **Double down :** dès qu'une niche fait > 500 €/mois, on la duplique (départements voisins, niche sœur, pays francophone).
- **Une stack unique** pour tout : Astro + Vercel + un moteur de pages programmatiques + formulaire → base de données (Supabase / Neon) → routage des leads (email/SMS acheteur) + Stripe. Chaque nouvelle niche = nouvelle config, pas nouveau code.
- **Revue hebdo de 30 min :** trafic, leads, CA, coût, décision (continuer / dupliquer / tuer).
