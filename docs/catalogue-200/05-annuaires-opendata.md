# Famille 05 · Annuaires de niche, SEO programmatique open data, newsletters locales

Date : 22 octobre 2026. Analyste : agent 05.

## Avertissement de méthode (à lire d'abord)

Le quota de recherche web partagé entre les 8 agents (200 requêtes) s'est épuisé au milieu de la
vérification. Après ce point, WebFetch et curl ont aussi échoué : DNS introuvable, puis le proxy a
refusé avec un 403. Je n'ai pas contourné la limite.

Conséquences :
- **4 idées seulement passent la méthode complète.** Pour chacune, j'ai une source identifiée et un
  signal de demande, et j'ai fait la recherche de concurrence sur 2 villes. L'objectif de 26 n'est
  **pas atteint**. Je n'ai pas compté comme validées des idées dont la concurrence n'a pas été vérifiée.
- **17 rejets.** 8 viennent d'une recherche faite dans cette session (marqués [vérifié]).
  9 viennent d'une connaissance antérieure, sans nouvelle recherche web (marqués [non re-vérifié]).
- **15 candidates restent en attente.** Elles sont listées en fin de document avec ce qui manque.
  Il faut un nouveau tour de recherche pour les valider ou les rejeter.
- Je n'ai pas pu ouvrir les pages data.gouv.fr. Les licences sont donc celles que la plateforme
  applique par défaut aux données publiques (Licence Ouverte 2.0). Elles sont marquées « à confirmer »
  quand je ne les ai pas lues moi-même.
- Toute valeur suivie de « estim. » est une hypothèse de l'analyste, pas un fait sourcé.

Coûts déjà couverts et non comptés : Claude Code Max, Vercel Pro (hébergement), temps de développement.

---

## Idées validées

### D01 · Alerte CatNat sécheresse par commune + mise en relation experts d'assuré
- Modèle · Payeur · Prix : site programmatique (1 page par commune, avec l'historique des arrêtés
  CatNat « mouvements de terrain liés au retrait-gonflement des argiles »). Une alerte email gratuite
  part à chaque publication au Journal officiel, avec le compte à rebours des 30 jours de déclaration.
  Un formulaire « faire expertiser mes fissures » alimente des leads. Payeurs : experts d'assuré,
  rémunérés en pourcentage de l'indemnisation selon Reporterre, puis bureaux d'études géotechniques
  et avocats en droit des assurances. Prix : lead qualifié 40 à 120 € (estim.), ou commission
  d'apport négociée.
- Source de données : « Arrêtés de catastrophe naturelle par commune » (base GASPAR, 260 601 lignes,
  dernière mise à jour de la source annoncée en septembre 2025)
  [https://www.data.gouv.fr/datasets/arretes-de-catastrophe-naturelle-par-commune]. Le jeu voisin
  « RISQUES - Arrêtés_catastrophes_naturelles » affiche des mises à jour en août-septembre 2026
  [https://www.data.gouv.fr/datasets/risques-arretes-catastrophes-naturelles]. Pour la fraîcheur, on
  compare au Journal officiel (données DILA/Légifrance, publication quotidienne). Licence Ouverte
  (à confirmer). GASPAR est en retard : le différentiel avec le JO **est** la donnée fraîche que
  Google ne synthétise pas.
- Zone prioritaire : Nord et Pas-de-Calais (36 des 75 communes reconnues pour la sécheresse 2025,
  selon bien-dans-ma-ville et jechange), puis Centre-Val de Loire et Occitanie (sols argileux,
  maisons individuelles).
- Preuve de demande : la presse grand public publie les listes de communes (« 180 communes reconnues,
  228 rejetées », jechange.fr ; bien-dans-ma-ville.fr). Des fils de forum existent (forumconstruire,
  « dossier catnat sécheresse assurance »). Reporterre décrit « des millions de maisons » touchées et
  une « bataille des experts ». Le délai légal de 30 jours après publication crée une action urgente.
- Concurrence vérifiée : requêtes « expert fissures maison sécheresse catastrophe naturelle Toulouse »
  et « fissures maison sécheresse expert d'assuré Orléans Loiret catnat ». Il sort seulement du
  contenu national : avocats (Kohen, AGN), assureurs (Matmut, MAIF, Groupama, Allianz), Leocare,
  Selectra, Reporterre. Aucun outil local d'alerte, aucun annuaire d'experts d'assuré par commune.
  → **ouvert**.
- Coût d'entrée : domaine .fr 12 € (estim.) + test Google Ads 100 € + emailing en offre gratuite
  (Brevo ou Resend, 0 €) = **112 €**.
- Mini business plan (estim.) :
  - M1 : 0 €. Pages communes générées, 10 experts d'assuré démarchés.
  - M3 : 2 partenaires, 10 leads à 50 €, soit 500 €.
  - M6 : 30 leads à 50 €, soit 1 500 €/mois.
  - M12 : 3 000 €/mois les mois d'arrêtés (publication par vagues), environ 1 000 € les mois creux.
  - Hypothèses : 2 % de conversion visiteur → lead sur les pages des communes reconnues ; 1 lead
    sur 2 accepté par un partenaire.
- Premier test 7 jours + seuil kill : publier les pages des communes du dernier arrêté. Poster dans
  3 groupes Facebook locaux. Appeler 10 experts d'assuré pour prévendre le lead. **Kill** si moins de
  2 experts acceptent un prix ferme, ou si moins de 20 inscriptions à l'alerte.
- Score /50 : **38** (demande 9, concurrence 8, monétisation 8, coût 9, risque AIO et juridique 4 :
  rester sur la mise en relation, sans conseil juridique).

### D02 · Annuaire des vidangeurs agréés par département + devis vidange et assainissement non collectif
- Modèle · Payeur · Prix : annuaire départemental des vidangeurs agréés par la préfecture (numéro et
  date d'expiration de l'agrément), avec un formulaire de devis. Payeurs : vidangeurs et entreprises
  d'assainissement. Prix : lead 10 à 25 € (estim.), ou fiche premium 15 à 30 €/mois (estim.). Le
  diagnostic assainissement non collectif obligatoire à la vente immobilière peut s'ajouter ensuite.
- Source de données : listes préfectorales publiées en PDF, réutilisables comme informations
  publiques (CRPA), mises à jour de façon irrégulière selon la préfecture. Exemples : Calvados au
  27/03/2024
  [https://www.calvados.gouv.fr/contenu/telechargement/23920/176157/file/Tableau_Agrement_Internet_Prefecture_Vidangeurs_20240327.pdf],
  Oise [https://www.oise.gouv.fr/contenu/telechargement/82321/600010/file/Liste_vidangeurs_pour_site_prefecture.pdf],
  Orne au 26/10/2023, Pyrénées-Orientales en juin 2023, Alpes-de-Haute-Provence en 2022. Aucun jeu
  consolidé sur data.gouv n'a été trouvé, et cette barrière à l'entrée est un avantage. Extraction
  des PDF par Claude.
- Zone prioritaire : Calvados, Orne, Oise, Pyrénées-Orientales (listes récentes), puis Morbihan et
  Dordogne (rural, forte part d'assainissement non collectif, SERP vide).
- Preuve de demande : la vidange par une personne agréée par le préfet est une obligation légale
  (préfecture d'Ille-et-Vilaine). Fréquence d'environ 4 ans selon les guides. Prix de référence
  public : forfait 162,80 € TTC en 2026 au Pays Voironnais. Volume de requêtes non mesuré, faute
  d'outil de mots-clés.
- Concurrence vérifiée : requêtes « vidange fosse septique prix Vannes » et « vidange fosse septique
  Périgueux vidangeur agréé ». Il sort des guides nationaux (abctravaux, obat), des PDF de
  collectivités (beaucoup québécoises), une entreprise locale et 118712. Aucun annuaire spécialisé
  des agréés. → **ouvert**.
- Coût d'entrée : domaine 12 € + Google Ads 80 € + 0 € d'outils = **92 €**.
- Mini business plan (estim.) :
  - M1 : 0 €. 10 départements en ligne.
  - M3 : 20 leads à 15 €, soit 300 €.
  - M6 : 40 leads à 15 €, soit 600 €/mois.
  - M12 : 30 départements, 1 200 €/mois.
  - Hypothèses : 30 demandes par mois et par département actif à M12 ; revente à 1 ou 2 vidangeurs.
- Premier test 7 jours + seuil kill : 3 départements en ligne et 20 vidangeurs appelés, avec
  1 lead gratuit offert. **Kill** si aucun n'accepte 15 € par lead, ou si moins de 5 demandes de
  devis malgré 80 € d'annonces.
- Score /50 : **36**.

### D03 · Newsletter locale hebdomadaire sponsorisée pour une ville moyenne (Angers puis Tours)
- Modèle · Payeur · Prix : hebdomadaire gratuit (« 5 choses à faire ce week-end + nouveaux commerces
  + 1 chiffre local »), sur le modèle 6AM City : pas de politique ni de faits divers, revenus en
  publicité native. Payeurs : commerces, restaurants, salles, agences immobilières, salons locaux.
  Prix : 80 à 250 € par envoi sponsorisé à 3 000-5 000 abonnés (estim.), plus des petites annonces
  à 20-40 € (estim.).
- Source de données : agenda via OpenAgenda et DATAtourisme (Licence Ouverte, à confirmer),
  créations d'établissements via SIRENE (INSEE, Licence Ouverte, mise à jour quotidienne)
  [https://www.data.gouv.fr/datasets/base-sirene-des-entreprises-et-de-leurs-etablissements-siren-siret]
  (URL à confirmer), avec un filtre sur les personnes morales.
- Zone prioritaire : Angers, puis Tours. Ce sont des villes de 150 000 habitants ou plus, avec des
  revenus et un tissu commercial denses, et sans newsletter de sorties indépendante trouvée.
- Preuve de demande : 6AM City a passé 1 million d'abonnés, couvre 28 villes américaines et tire
  l'essentiel de ses revenus de publicité native locale (Press Gazette, Simon Owens). Signal
  français indirect : Angers Mag, mensuel gratuit, était en difficulté (2016). Le print local
  souffre et l'email reste à prendre. **Aucune preuve française directe de revenus.** C'est le
  point faible.
- Concurrence vérifiée : requêtes « newsletter hebdomadaire locale gratuite Angers bons plans
  sorties » et « newsletter locale Tours sorties week-end ». Il sort Groupon, Billetreduc, Maison de
  la Presse, le magazine municipal d'Angers, agenda-des-sorties.com (par département) et
  l'Office de tourisme. Pas de newsletter éditoriale indépendante. → **ouvert**. Je n'ai pas vérifié
  si Le Bonbon ou Secret Media couvrent ces villes (quota épuisé).
- Coût d'entrée : domaine 12 € + Beehiiv ou Brevo en offre gratuite 0 € + acquisition Meta Ads
  150 € = **162 €**.
- Mini business plan (estim.) :
  - M1 : 0 €, 500 abonnés.
  - M3 : 1 500 abonnés, 2 sponsors à 80 €, soit 160 €.
  - M6 : 3 000 abonnés, 4 envois sponsorisés à 120 €, soit 480 €/mois.
  - M12 : 6 000 abonnés, 1 200 €/mois, puis duplication à Tours.
  - Hypothèses : croissance organique par groupes Facebook et Instagram locaux, taux d'ouverture
    de 45 % ou plus.
- Premier test 7 jours + seuil kill : landing page et 3 numéros d'essai, 50 € de Meta Ads,
  10 commerces démarchés en personne. **Kill** si plus de 2 € par abonné, ou si aucune
  pré-réservation de sponsor à J+30.
- Score /50 : **30**. Le délai est long et la preuve française est absente.

### D04 · Radar régional des reprises (procédures collectives et cessions d'actifs, BODACC)
- Modèle · Payeur · Prix : alerte hebdomadaire payante par région et par secteur. Elle couvre les
  ouvertures de liquidation et de redressement, les appels d'offres de cession (fonds de commerce,
  matériel, droit au bail) et les coordonnées du mandataire, avec un tri par code NAF. Payeurs :
  repreneurs de fonds (CHR, commerce), concurrents en croissance externe, brocanteurs
  professionnels, conseils en reprise. Prix : 19 à 39 €/mois (estim.).
- Source de données : BODACC A (ventes et cessions, procédures collectives), publié par la DILA en
  open data quotidien, Licence Ouverte (à confirmer), avec des PDF unitaires par annonce. Exemple :
  annonces du TC de Bordeaux du 28/07/2026
  [https://www.bodacc.fr/telechargements/COMMERCIALES/PDF/A/2026/20260149/1/BODACC_A_PDF_Unitaire_20260149_02534.pdf].
  Les entrepreneurs individuels sont exclus (données de personnes physiques). On garde seulement les
  personnes morales.
- Zone prioritaire : Gironde (TC de Bordeaux actif, mandataires récurrents : Ekip', Philae,
  SCP Silvestri-Baujet), puis Rhône.
- Preuve de demande : il existe des guides juridiques « racheter une entreprise en liquidation »
  (swim.legal, documentissime) et une notice du greffe du TC de Paris pour les candidats à la
  reprise. Le CNAJMJ centralise une partie des annonces, et Actify publie des dossiers de vente.
  Volume de requêtes non mesuré.
- Concurrence vérifiée : requêtes « fonds de commerce liquidation judiciaire à reprendre Bordeaux »
  et « reprise entreprise liquidation judiciaire offres de reprise Lyon ». Il sort doctrine.fr
  (fiches entreprises), les PDF du BODACC, des commentaires de décisions et Actify (plateforme de
  dossiers de vente de mandataires). Pas d'alerte locale filtrée par secteur. → **ouvert mais
  disputé**. Actify et Doctrine sont à étudier avant de lancer.
- Coût d'entrée : domaine 12 € + Stripe 0 € (commission seulement) + LinkedIn ou Google Ads 100 € =
  **112 €**.
- Mini business plan (estim.) :
  - M1 : 0 €, liste gratuite à 200 inscrits.
  - M3 : 10 abonnés à 29 €, soit 290 €.
  - M6 : 15 abonnés, soit 435 €/mois.
  - M12 : 3 régions, 50 abonnés, soit 1 450 €/mois.
  - Hypothèses : 5 % de passage du gratuit au payant ; l'abonnement gratuit ne montre qu'un résumé
    sans coordonnées du mandataire.
- Premier test 7 jours + seuil kill : une page Gironde gratuite et 2 numéros envoyés à 30 contacts
  (brokers CHR, groupes LinkedIn de repreneurs). **Kill** si moins de 3 pré-paiements à 19 € à J+30.
- Score /50 : **31**.

---

## Rejetées

| # | Idée | Raison (1 ligne) | Statut |
|---|------|------------------|--------|
| R01 | Auto-écoles et taux de réussite par ville | vroomvroom.fr occupe tout le top 10 sur Nantes et Rennes, avec les taux officiels ; carte officielle sur autoecoles.securite-routiere.gouv.fr ; verrouillé | [vérifié] |
| R02 | Prix du contrôle technique (dont moto) | Comparateur officiel DGCCRF (prix.conso.gouv.fr), qui couvre la catégorie L depuis le 08/10/2025 ; idgarages, SGS et Simplauto sur Toulouse et Marseille ; leader gratuit installé | [vérifié] |
| R03 | Qualité de l'eau et PFAS par commune | Selectra, toutsurmoneau, UFC-Que Choisir, NextToYourPlace et eaupotable.sante.gouv couvrent déjà le sujet ; information pure exposée aux AI Overviews ; seulement 13 réseaux sur 9 900 hors norme, donc peu d'action d'achat | [vérifié, national] |
| R04 | Prix des terrains à bâtir (DVF) + leads constructeurs | Solvimo, unemplacement.com, PAP, RealAdvisor et Superimmo sur Angers et Valence ; unemplacement fait déjà le lien terrain-constructeur | [vérifié] |
| R05 | Annuaire du bonus réparation (QualiRépar, Refashion) | Annuaires officiels gratuits (bonusreparation.fr, label-qualirepar) ; pas d'open data trouvé ; réparateurs déjà listés gratuitement, donc pas de payeur | [vérifié] |
| R06 | Leads artisans à partir des permis de construire (Sitadel) | Usage commercial des données nominatives interdit sans consentement du pétitionnaire (note SDES 2021) ; données personnelles | [vérifié] |
| R07 | Fichier statique des restaurants (SIRENE 56.10) | Salesdorado le donne gratuitement (242 000 établissements) ; seul un flux de créations reste à étudier (voir C01) | [vérifié] |
| R08 | Arrêtés CatNat « information pure » | Listes publiées par jechange et bien-dans-ma-ville, avec un risque AIO ; retenu seulement sous l'angle alerte + lead (D01) | [vérifié] |
| R09 | Pharmacies de garde | Le 3237 officiel et les sites d'ordres et d'ARS servent la requête ; leader gratuit | [non re-vérifié] |
| R10 | Médecins acceptant de nouveaux patients | Aucune source publique ouverte (agendas privés Doctolib) ; donnée indisponible | [non re-vérifié] |
| R11 | Places en crèche et assistantes maternelles | mon-enfant.fr (CNAF), officiel et gratuit ; les assistantes maternelles relèvent des données personnelles | [non re-vérifié] |
| R12 | Aires de camping-car | Park4night et Camping-Car Park dominent, avec des apps communautaires | [non re-vérifié] |
| R13 | Bornes de recharge | Chargemap, apps constructeurs et jeu IRVE officiel ; verrouillé | [non re-vérifié] |
| R14 | Couverture 5G et fibre par rue | ARCEP « Ma connexion internet », officiel ; Ariase et Degrouptest | [non re-vérifié] |
| R15 | Risques par adresse avant achat | Géorisques (ERRIAL), gratuit et officiel ; information pure | [non re-vérifié] |
| R16 | Prestataires de mariage par département | Mariages.net et Zankyou verrouillent les SERP et les budgets annonceurs | [non re-vérifié] |
| R17 | Vide-greniers et brocantes | vide-greniers.org et Brocabrac, leaders gratuits et historiques | [non re-vérifié] |

---

## Candidates en attente (méthode incomplète, à reprendre au prochain tour)

Aucune n'est validée. Pour chacune, il manque au minimum la recherche de concurrence sur 2 villes.

| # | Idée | Source pressentie | Payeur pressenti | Manque |
|---|------|-------------------|------------------|--------|
| C01 | Flux hebdomadaire des ouvertures CHR par département (SIRENE, personnes morales) | SIRENE (INSEE), quotidien | Torréfacteurs, brasseurs, éditeurs de caisses, assureurs : 29-79 €/mois (estim.) | Concurrence (Pappers alertes, Société.com) et 2 villes |
| C02 | Vétérinaires de garde par ville | SIRENE NAF 75.00Z + annuaire de l'Ordre (licence à vérifier) | Cliniques (fiche premium), affiliation assurance animaux | SERP Clermont-Ferrand et Limoges (requête bloquée par le quota) |
| C03 | Écoles privées hors contrat et Montessori par ville | Annuaire de l'éducation nationale (data.education.gouv.fr) | Écoles (fiche premium 30-80 €/mois, estim.) | SERP Dijon et Grenoble (bloquée) |
| C04 | Location de benne et déchetteries acceptant les professionnels | Listes de déchetteries (SINOE, ADEME) | Loueurs de bennes : leads | SERP Reims (bloquée) |
| C05 | Encadrement des loyers : vérificateur + courrier de réclamation payant | Open data des loyers de référence (Paris, Lyon, Lille, Montpellier, Bordeaux) | Locataire : 9-19 € (estim.) | Concurrence (ADIL, simulateurs officiels) |
| C06 | Règles des meublés de tourisme par commune (enregistrement, quotas) | Délibérations communales (non structurées) | Conciergeries Airbnb : leads | Source structurée et SERP |
| C07 | Obligations légales de débroussaillement par commune (Sud-Est) | Zonages OLD départementaux (à confirmer) | Élagueurs et paysagistes : leads | Source et SERP |
| C08 | Privatisation de food-trucks pour événements | SIRENE + inscriptions volontaires | Food-truckers : leads ou commission | SERP 2 villes |
| C09 | Logement et emploi saisonnier par station | Offres France Travail (API) | Employeurs de station : annonce payante | Concurrence (Jobaviz, l'Hôtellerie) |
| C10 | Plages et lieux autorisés aux chiens | Arrêtés municipaux + OSM | Hébergements dog-friendly : affiliation | SERP |
| C11 | Activités extrascolaires enfants par ville | RNA (associations), data.gouv | Structures privées : fiches premium | SERP |
| C12 | Diagnostiqueurs immobiliers certifiés + devis | Annuaire officiel des diagnostiqueurs (ministère) | Diagnostiqueurs : leads | SERP |
| C13 | Salles d'anniversaire pour enfants | Données non ouvertes (collecte manuelle) | Salles : fiches premium | Source et SERP |
| C14 | Tarifs des pompes funèbres (devis types obligatoires) | Devis publiés par les communes (non structurés) | Opérateurs funéraires : leads | Source et SERP |
| C15 | Radon par commune + kits de mesure | Zonage radon IRSN | Affiliation kits | Faible ticket, SERP |

Autres pistes du brief non traitées faute de quota : déchetteries et horaires, marchés de
producteurs, salles à louer, padel, lieux de tournage, nuisances aériennes, écoles et IPS,
restaurants avec aire de jeux, artisans d'art.
