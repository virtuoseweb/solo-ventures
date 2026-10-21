# 08 · Hybrides en ligne → local et export

Agent 08 · recherche menée le 21-22 octobre 2026 · langue : français.

## Avertissement sur la méthode (à lire avant le catalogue)

- **15 idées validées sur les 26 visées.** Le budget de recherche web partagé par les 8 agents (200 requêtes)
  a été épuisé en cours de travail, et la lecture directe d'URL (WebFetch) échouait (DNS). Je n'ai pas
  complété le quota avec des idées non vérifiées : celles qui manquaient de preuve sont passées en
  « Rejetées » ou en « Non validées faute de preuve ».
- **Deuxième zone de concurrence :** elle n'a été vérifiée que pour T03, T05 et T09. Pour les autres,
  la ligne « Concurrence vérifiée » indique la zone contrôlée, et la seconde zone est à faire au J1 du test
  (signalé « 2e zone : à faire »).
- Tous les chiffres de business plan sont des **estimations** (« estim. »). Les seuls chiffres non estimés
  sont ceux suivis d'une source.
- Coûts d'entrée : Claude Code Max et Vercel Pro déjà payés, donc comptés à 0 €. Micro-entreprise : immatriculation
  gratuite. Domaine .fr ou .com : estim. 10 à 15 €/an.
- Grille de score /50 : demande prouvée (10), concurrence faible constatée (10), rapidité du premier euro (10),
  simplicité légale (10), avantage du profil dev + IA + agence (10).

---

## Tourisme et saisons

### T01 · Réservation directe pour écoles de surf indépendantes (sortir des places de marché)
- Modèle · Payeur · Prix : service d'agence productisé. Site d'école + agenda indexé sur les marées + paiement
  en ligne + avis. Payeur : l'école de surf. Prix : estim. 590 € de mise en place + 29 €/mois, ou 0 € de mise en
  place + 3 % des réservations directes.
- Zone précise : Hossegor, Seignosse, Capbreton (Landes sud), ensuite Lacanau. Pourquoi : densité d'écoles sur
  quelques kilomètres, saison longue (avril-octobre), horaires dépendants des marées que les plateformes
  gèrent mal.
- Preuve de demande / paiement : les écoles d'Hossegor vendent déjà leurs cours via des places de marché
  payantes (CheckYeti, Adrenactive) et l'office de tourisme. [CheckYeti Hossegor](https://www.checkyeti.com/fr/d/2051/15926),
  [Adrenactive Hossegor](https://www.adrenactive.com/cours-surf-hossegor-7937.htm),
  [Yo Surf School sur Tourisme Landes](https://www.tourismelandes.com/activite/yo-surf-school-ascaqu040fs001oi/).
  Taux de commission des plateformes : **non trouvé**, estim. 15 à 25 %.
- Concurrence vérifiée : requête « cours de surf Hossegor réservation » → CheckYeti (4 résultats sur 10),
  Adrenactive, Tourisme Landes, sites d'écoles. Verdict : le **B2C est verrouillé** par les places de marché
  (rejet R01), mais l'angle B2B (aider l'école à récupérer la réservation directe) n'est servi par aucun acteur
  local visible. 2e zone (Lacanau) : à faire.
- Légal : prestation de service B2B, contrat + CGV. Paiement par Stripe sur le compte de l'école (pas de
  détention de fonds). RGPD : l'école est responsable de traitement, le dev est sous-traitant (clause art. 28).
- Coût d'entrée : domaine de démo 12 € + 3 visites terrain en novembre (essence) estim. 60 € + cartes de visite
  estim. 25 € = **97 €**.
- Mini business plan (estim.) : hypothèses 40 écoles prospectées sur la zone, 10 % de conversion par saison.
  M1 : 1 école pilote gratuite (étude de cas). M3 (janvier) : 2 écoles × 590 € = 1 180 €. M6 (avril) : 4 écoles,
  2 360 € cumulés + 116 €/mois. M12 : 6 écoles, estim. 3 540 € de mises en place + 174 €/mois. Saisonnalité :
  vendre entre novembre et mars (hors saison), aucune vente en juillet-août.
- Premier test 7 jours + seuil kill : 15 écoles appelées ou visitées, démo sur le site de l'une d'elles.
  Kill si moins de 3 rendez-vous et 0 pilote accepté.
- Score /50 : 33 (demande 7, concurrence 6, premier euro 5, légal 9, profil 6).

### T02 · Agenda de biplaceurs parapente avec report météo automatique
- Modèle · Payeur · Prix : outil de réservation pour pilotes biplace et petites écoles, avec report
  automatique par SMS ou e-mail quand le vol est annulé pour météo. Payeur : le pilote. Prix : estim.
  39 €/mois en saison, ou 2 € par vol réservé.
- Zone précise : Doussard et col de la Forclaz (lac d'Annecy). Pourquoi : site de vol parmi les plus
  fréquentés, baptêmes vendus de 90 à 180 €, et la météo impose des reports constants.
- Preuve de demande / paiement : baptêmes affichés dès 90 € (formule enfants), 100 € (sensation) et 180 € (vol
  privé), revendus par plusieurs plateformes. [Adrenactive Forclaz](https://www.adrenactive.com/bapteme-parapente-annecy-forclaz-74-2012.htm),
  [Sport Découverte](https://www.sport-decouverte.com/bapteme-parapente-annecy.html),
  [Manawa](https://www.manawa.com/fr-FR/activite/france/annecy/parapente/bapteme-de-parapente-au-dessus-du-lac-dannecy/1532),
  [CheckYeti](https://www.checkyeti.com/fr/d/3123/24433).
- Concurrence vérifiée : requête « baptême parapente Annecy prix » → CheckYeti, Adrenactive, Sport Découverte,
  Manawa, Cap Adrénaline. Verdict : le **B2C est verrouillé** (rejet R02). L'outil de report météo destiné
  au pilote n'est pas proposé par ces revendeurs. 2e zone (Saint-Hilaire-du-Touvet) : à faire.
- Légal : SaaS B2B. Le pilote reste seul responsable de la décision de vol et de son assurance. RGPD :
  sous-traitance. SMS : envoi transactionnel seulement (pas de prospection).
- Coût d'entrée : domaine 12 € + crédits SMS de test estim. 20 € + déplacement Doussard estim. 60 € = **92 €**.
- Mini business plan (estim.) : hypothèses 30 pilotes ou structures autour du lac, 15 % d'adoption.
  M1 : prototype et 2 pilotes testeurs gratuits. M3 : 0 € (hiver, peu de vols). M6 (avril) : 3 abonnés × 39 € =
  117 €/mois. M12 : 5 abonnés, estim. 195 €/mois en saison. Saisonnalité forte : avril à octobre.
- Premier test 7 jours + seuil kill : entretien avec 8 pilotes, question « combien de reports par semaine en
  saison, et comment les gérez-vous ? ». Kill si moins de 3 pilotes déclarent plus de 5 reports par semaine.
- Score /50 : 29 (demande 6, concurrence 6, premier euro 3, légal 8, profil 6).

### T03 · Leads « séminaire au vert » de PME vers des gîtes de groupe
- Modèle · Payeur · Prix : site éditorial « séminaire au vert à moins de 2 h de Paris » avec fiches de gîtes
  de groupe et formulaire de demande. Payeur : le gîte, à la commission. Prix : estim. 8 à 10 % du séjour,
  ou 30 € par demande qualifiée.
- Zone précise : Eure et Calvados (Normandie), puis Morbihan. Pourquoi : gîtes de 20 à 35 couchages déjà
  positionnés sur le séminaire, proximité de Paris, et aucune place de marché B2B dominante dans les résultats.
- Preuve de demande / paiement : des gîtes normands se vendent comme lieux de séminaire (L'Orangerie, 20 pers.,
  ménage 200 € ; Les Blés verts, 29 pers.). [GreenGo L'Orangerie](https://www.greengo.voyage/hote/l-orangerie-normandie),
  [Gîtes de France Les Blés verts](https://www.gites-de-france.com/fr/normandie/eure/les-bles-verts-27g8055),
  [Tourmag, Normandie séminaires au vert](https://www.tourmag.com/La-Normandie-votre-destination-seminaires-au-vert_a109242.html).
  Les propriétaires acceptent déjà de payer : environ 12 % de commission sur la centrale Gîtes de France et
  280 €/an d'adhésion. [Tourmag, Gîtes de France](https://www.tourmag.com/Gites-de-France-un-pionnier-qui-veut-rappeler-sa-force-face-a-Airbnb-et-consorts-_a73509.html).
- Concurrence vérifiée : « séminaire au vert Normandie gîte groupe 20 personnes » → GreenGo, Gîtes de France,
  Normandie Tourisme, Aleou. « séminaire entreprise Bretagne lieu clé en main » → réseau institutionnel
  Morbihan Affaires, agence réceptive Funbreizh, Giggster (salles). [Morbihan Affaires](https://morbihan.com/espace-affaires/organisez-votre-evenement/).
  Verdict : marché fragmenté, pas de comparateur B2B qui tienne la requête. Validé.
- Légal : apport d'affaires entre professionnels, contrat écrit avec chaque gîte. Pas d'encaissement pour le
  compte du gîte (sinon statut d'agent de voyage, immatriculation Atout France). RGPD : consentement du
  demandeur à la transmission, gîtes nommés comme destinataires.
- Coût d'entrée : domaine 12 € + test Google Ads ou LinkedIn estim. 120 € + appels 0 € = **132 €**.
- Mini business plan (estim.) : hypothèses panier 20 pers. × 2 nuits × 60 € = 2 400 € par séminaire, commission
  8 % = 192 €. M1 : 10 gîtes partenaires signés, 0 €. M3 : 2 séminaires = 384 €. M6 (avril-juin, saison forte) :
  4 séminaires par mois = 768 €/mois. M12 : 6 par mois en pic, estim. 5 000 € cumulés. Saisonnalité :
  pics avril-juin et septembre-octobre.
- Premier test 7 jours + seuil kill : appeler 20 gîtes de groupe de l'Eure et du Calvados, obtenir 8 accords de
  commission écrits, et lancer 120 € de publicité. Kill si moins de 5 accords ou 0 demande sur 7 jours.
- Score /50 : 36 (demande 8, concurrence 8, premier euro 5, légal 7, profil 8).

### T04 · Site de réservation directe pour gîtes de groupe
- Modèle · Payeur · Prix : site + moteur de réservation + paiement d'acompte pour gîtes de groupe qui veulent
  réduire leur dépendance aux centrales. Payeur : le propriétaire. Prix : estim. 790 € de mise en place + 19 €/mois.
- Zone précise : Normandie (Eure, Calvados, Manche), puis Savoie. Pourquoi : forte densité de gîtes de groupe
  labellisés, commissions régionales de 10 à 20 %.
- Preuve de demande / paiement : commissions observées de 10 à 20 %, 10 % en Savoie, 12 % TTC dans le Gard, frais de
  dossier de 10 à 20 € par réservation. [Lodgify, coûts Gîtes de France](https://www.lodgify.com/fr/guides/gites-de-france/couts/),
  [Tourmag](https://www.tourmag.com/Gites-de-France-un-pionnier-qui-veut-rappeler-sa-force-face-a-Airbnb-et-consorts-_a73509.html).
  Calcul (estim.) : un gîte de 25 couchages à 20 000 € de CA par la centrale paie 2 400 € de commission par an.
- Concurrence vérifiée : même requête qu'en T03 (Normandie) → gîtes visibles uniquement via les centrales
  (Gîtes de France, GreenGo). Concurrents logiciels connus (Lodgify, etc.) vendent un outil, pas un site fait
  pour le propriétaire. 2e zone (Savoie) : à faire.
- Légal : B2B. Le propriétaire reste le vendeur. Attention au contrat Gîtes de France : la réservation directe
  est permise en contrat partagé, pas en contrat exclusif. [Lodgify](https://www.lodgify.com/fr/guides/gites-de-france/couts/).
- Coût d'entrée : domaine de démo 12 € + publipostage à 50 gîtes estim. 70 € = **82 €**.
- Mini business plan (estim.) : hypothèses 5 % de conversion sur 100 gîtes contactés. M1 : 1 pilote à prix réduit
  (390 €). M3 : 3 clients = 1 970 € cumulés. M6 : 5 clients = 3 550 € + 95 €/mois. M12 : 8 clients, estim. 5 900 €
  + 152 €/mois. Saisonnalité : vente en automne-hiver, avant l'ouverture des réservations d'été.
- Premier test 7 jours + seuil kill : 30 gîtes appelés avec le calcul de leur commission annuelle. Kill si moins
  de 2 rendez-vous.
- Score /50 : 34 (demande 8, concurrence 6, premier euro 6, légal 8, profil 6).

### T05 · Leads de propriétaires vers les conciergeries de location courte durée (villes moyennes)
- Modèle · Payeur · Prix : pages « conciergerie à [ville] : comparatif et devis » avec formulaire, transmission à
  2 ou 3 conciergeries locales. Payeur : la conciergerie. Prix : estim. 40 à 80 € par lead, ou un mois de
  commission au premier contrat.
- Zone précise : La Rochelle et Annecy. **Pas Lyon.** Pourquoi : marchés avec plusieurs conciergeries actives
  et un revenu par logement élevé (Annecy : moyenne de marché 30 623 €/an selon Airbtics), mais sans comparateur
  de devis dans les résultats. Lyon est saturée de comparatifs et soumise depuis le 1er janvier 2026 à un plafond
  de 90 nuits pour les résidences principales.
- Preuve de demande / paiement : commission moyenne d'environ 20 % HT des loyers à Lyon (15 à 25 %).
  [Toploc, conciergeries Lyon](https://toploc.com/blog/?p=133986), [GuestReady, Lyon](https://www.guestready.com/?p=25436),
  [Welkeys](https://www.welkeys.com/blog/comment-choisir-sa-conciergerie-airbnb-a-lyon).
  Conciergeries recensées à La Rochelle et Annecy : [Airbtics La Rochelle](https://airbtics.com/top-airbnb-management-companies-in-la-rochelle-france),
  [Airbtics Annecy](https://airbtics.com/top-airbnb-management-companies-in-annecy-france).
- Concurrence vérifiée : « conciergerie Airbnb Lyon comparatif tarifs commission » → GuestReady, Toploc,
  Welkeys, investissement-locatif-avis.fr : **saturé**. « conciergerie Airbnb La Rochelle Annecy comparateur devis »
  → uniquement des classements Airbtics (en anglais, sans formulaire). Verdict : validé sur La Rochelle et Annecy.
- Légal : une conciergerie qui encaisse des loyers relève de la loi Hoguet (carte G). Le site, lui, ne fait que
  transmettre un contact : contrat d'apporteur avec chaque conciergerie, aucune négociation, rémunération au lead.
  Jurisprudence nuancée sur les apporteurs : [Legalstart, loi Hoguet](https://www.legalstart.fr/fiches-pratiques/immobilier-patrimoine/loi-hoguet/).
  RGPD : consentement explicite, conciergeries nommées. Risque réglementaire local (quotas de nuits, changement
  d'usage à Annecy) : à vérifier en mairie.
- Coût d'entrée : 2 domaines 24 € + publicité test estim. 100 € = **124 €**.
- Mini business plan (estim.) : hypothèses 50 €/lead, 10 leads par ville et par mois après 3 mois de SEO.
  M1 : 3 conciergeries signées par ville, 0 €. M3 : 8 leads = 400 €. M6 (pré-saison) : 20 leads/mois = 1 000 €/mois.
  M12 : 25 leads/mois, estim. 9 000 € cumulés. Saisonnalité : pic de février à mai (préparation de l'été).
- Premier test 7 jours + seuil kill : appeler les conciergeries listées par Airbtics dans les deux villes. Kill si
  moins de 3 acceptent un prix au lead ≥ 30 €.
- Score /50 : 35 (demande 8, concurrence 7, premier euro 6, légal 6, profil 8).

---

## Événements

### T06 · Devis instantané + acompte en ligne pour loueurs de photobooth (alternative aux annuaires payants)
- Modèle · Payeur · Prix : site par département avec simulateur de devis et paiement d'acompte, pour un petit
  réseau de loueurs de bornes. Payeur : le loueur. Prix : estim. 49 €/mois par loueur, ou 25 € par réservation
  confirmée.
- Zone précise : Ille-et-Vilaine (Rennes et 150 km autour), puis Loire-Atlantique. Pourquoi : plusieurs loueurs
  locaux, réservation à 6 mois, et peu d'offres dans les annuaires (2 loueurs seulement sur Lokki à Rennes).
- Preuve de demande / paiement : prestation dès 350 € (Breizh-iBooth), livraison et installation 40 € (La Cabine
  Bretonne). [Mariages.net Breizh-iBooth](https://www.mariages.net/animation-mariage/breizh-ibooth--e147791),
  [Mariages.net La Cabine Bretonne](https://www.mariages.net/animation-mariage/la-cabine-bretonne--e401547).
  Les prestataires paient déjà 130 à 150 €/mois d'abonnement Mariages.net selon des avis, et s'en plaignent.
  [Trustpilot Mariages.net](https://at.trustpilot.com/review/mariage.net), [Forum Que Choisir](https://forum.quechoisir.org/post1277084.html).
- Concurrence vérifiée : « location photobooth mariage Rennes prix » → Mariages.net, Lokki, Évènementiel pour tous,
  Justacote. Verdict : le B2C mariage est tenu par Mariages.net, mais l'offre moins chère et à la performance
  pour le loueur n'est pas servie. 2e zone (Nantes) : à faire.
- Légal : B2B, CGV. Acompte encaissé sur le compte Stripe du loueur. RGPD : sous-traitance.
- Coût d'entrée : domaine 12 € + publicité test 80 € = **92 €**.
- Mini business plan (estim.) : hypothèses 8 loueurs sur 2 départements, 50 % d'adhésion. M1 : 2 loueurs gratuits.
  M3 : 3 × 49 € = 147 €/mois. M6 (saison des mariages) : 4 loueurs = 196 €/mois. M12 : 6 loueurs, estim. 294 €/mois.
  Saisonnalité : réservations d'octobre à mars pour les mariages de mai à septembre.
- Premier test 7 jours + seuil kill : 10 loueurs contactés avec le calcul « Mariages.net contre 49 € ». Kill si
  moins de 2 accords de test.
- Score /50 : 30 (demande 7, concurrence 5, premier euro 6, légal 8, profil 4).

---

## Animaux

### T07 · Leads d'éducation canine par ville
- Modèle · Payeur · Prix : pages par ville et par problème (« chiot qui mord Nantes », « chien réactif en laisse »),
  formulaire, transmission à 1 éducateur par secteur (exclusivité). Payeur : l'éducateur. Prix : estim. 15 à 25 €
  par lead, ou 59 €/mois pour l'exclusivité d'un secteur.
- Zone précise : métropole de Nantes (sud Loire, Rezé, Les Sorinières), puis Rennes. Pourquoi : éducateurs à
  domicile actifs dans un rayon de 40 km, et aucun site de mise en relation dans les résultats.
- Preuve de demande / paiement : séance individuelle de 30 à 80 €, programme de 5 à 10 séances de 200 à 1 000 €
  (fourchettes nationales). [SantéVet](https://www.santevet.com/?p=35898),
  [Modèles de business plan, éducateur canin](https://modelesdebusinessplan.com/blogs/infos/educateur-canin-estimation-revenu-outil).
  Éducateurs nantais listés : [chien.com, Mai Dog](https://www.chien.com/adresse/educateur-dresseur-canin/mai-dog-80777.php).
- Concurrence vérifiée : « éducateur canin Nantes tarif séance » → chien.com (annuaire), SantéVet, guides.
  Les prix ne sont presque jamais affichés. Verdict : pas de place de marché, validé. 2e zone (Rennes) : à faire.
- Légal : apport d'affaires B2B. Le métier d'éducateur demande un certificat de capacité (ACACED) : ne référencer
  que des éducateurs qui le présentent. RGPD : consentement.
- Coût d'entrée : domaine 12 € + publicité Meta test estim. 80 € = **92 €**.
- Mini business plan (estim.) : hypothèses 3 secteurs exclusifs à 59 €. M1 : 2 éducateurs en essai gratuit.
  M3 : 3 × 59 € = 177 €/mois. M6 : 5 secteurs (Nantes + Rennes) = 295 €/mois. M12 : 8 secteurs, estim. 470 €/mois.
  Saisonnalité : pics à l'arrivée des chiots (printemps) et après Noël.
- Premier test 7 jours + seuil kill : 1 page + 80 € de publicité ciblée Nantes. Kill si moins de 5 demandes ou si
  aucun éducateur n'accepte de payer ≥ 15 € le lead.
- Score /50 : 32 (demande 7, concurrence 8, premier euro 6, légal 7, profil 4).

### T08 · Leads d'ostéopathie équine et canine (écuries et propriétaires)
- Modèle · Payeur · Prix : annuaire limité aux praticiens inscrits au Registre national d'aptitude (RNA),
  avec prise de rendez-vous groupée par écurie (plusieurs chevaux = un seul déplacement). Payeur : l'ostéopathe.
  Prix : estim. 10 € par rendez-vous confirmé ou 39 €/mois.
- Zone précise : Gironde (Bruges, Médoc, Libournais), puis le Calvados (bassin équin). Pourquoi : forte densité
  d'écuries, déplacement facturé à part, et praticiens trouvables seulement par annuaire.
- Preuve de demande / paiement : prix libres, de 30 à 70 € pour un chien et autour de 100 € pour un cheval, plus le
  déplacement. Inscription RNA obligatoire depuis 2017 pour les non-vétérinaires.
  [Zoomalia, ostéopathie animale](https://www.zoomalia.com/blog/article/osteopathie-pour-animaux.html),
  [chien.com, Lucie Bireaud](https://www.chien.com/adresse/osteopathe-masseur-pour-chien/lucie-bireaud-87002.php).
- Concurrence vérifiée : « ostéopathe animalier Bordeaux tarif consultation » → Zoomalia, fiches métier, chien.com.
  Aucun service de réservation. Verdict : validé. 2e zone (Calvados) : à faire.
- Légal : n'afficher que des praticiens inscrits au RNA ou vétérinaires. Apport d'affaires B2B. RGPD : consentement.
- Coût d'entrée : domaine 12 € + flyers pour 30 écuries estim. 40 € + essence estim. 40 € = **92 €**.
- Mini business plan (estim.) : hypothèses 6 praticiens, 15 rendez-vous par mois à 10 €. M1 : 3 praticiens, 0 €.
  M3 : 80 €/mois. M6 : 150 €/mois. M12 : estim. 250 €/mois sur 2 départements. Saisonnalité : faible (reprise
  sportive au printemps).
- Premier test 7 jours + seuil kill : 10 praticiens appelés, 5 écuries visitées. Kill si moins de 2 praticiens
  prêts à payer.
- Score /50 : 27 (demande 6, concurrence 8, premier euro 4, légal 6, profil 3).

### T09 · Disponibilités en temps réel des pensions et garderies canines (août et fêtes)
- Modèle · Payeur · Prix : page « pension chien août [ville] places disponibles » alimentée par les pensions
  (mise à jour par SMS ou formulaire), demandes transmises. Arbitrage du modèle allemand des
  « Hundetagesstätten » (garderies de jour) pour la garderie. Payeur : la pension. Prix : estim. 5 à 8 € par
  réservation confirmée, ou 29 €/mois.
- Zone précise : Gironde (pensions entre Bordeaux et l'océan, Saint-Savin) et ouest lyonnais (Grézieu-la-Varenne,
  Saint-Cyr-au-Mont-d'Or). Pourquoi : pensions périurbaines difficiles à trouver, pics de saturation aux vacances.
- Preuve de demande / paiement : garderie de jour à 25 €/jour (chiffre de 2021, à réactualiser), garde à domicile
  à 12 €/h. [Le Bonbon, Educa Dog](https://www.lebonbon.fr/lyon/good-news/lyon-creche-garde-chien-saint-cyr-mont-or-educadog/),
  [Aladom Lyon](https://www.aladom.fr/garde-chien/lyon-69/garde-danimaux-et-promenades-lyon-et-villeurbanne-78ke),
  [chien.com, Dog Zone](https://www.chien.com/adresse/pension-pour-chien/dog-zone-51333.php).
- Concurrence vérifiée : « pension canine Bordeaux réserver avis » → chien.com, PagesJaunes. « garderie canine Lyon
  tarif journée » → chien.com, Aladom, Le Bonbon. Aucune information de disponibilité. Verdict : validé
  (2 zones vérifiées). Les plateformes de pet-sitting entre particuliers sont un autre segment.
- Légal : apport d'affaires. Les pensions doivent détenir le certificat d'activité et être déclarées en préfecture
  (ICPE au-delà de 9 chiens, à vérifier) : ne référencer que les structures déclarées.
- Coût d'entrée : 2 domaines 24 € + publicité juillet estim. 100 € = **124 €**.
- Mini business plan (estim.) : hypothèses 10 pensions, 6 € par réservation. M1 (novembre) : 5 pensions inscrites,
  premières demandes de Noël. M3 : estim. 60 €. M6 : creux (avril). M12 (après l'été) : estim. 1 200 € cumulés.
  Saisonnalité extrême : juillet-août, Noël, ponts de mai.
- Premier test 7 jours + seuil kill : 15 pensions appelées pour Noël 2026. Kill si moins de 5 acceptent de déclarer
  leurs places.
- Score /50 : 28 (demande 6, concurrence 8, premier euro 4, légal 6, profil 4).

---

## Immobilier

### T10 · Home staging virtuel « fait pour vous » pour mandataires indépendants
- Modèle · Payeur · Prix : envoi des photos, retour sous 24 h de photos meublées par IA, retouchées et contrôlées,
  plus une annonce rédigée. Payeur : mandataire iad, Safti, Capifrance ou agence. Prix : estim. 15 € par photo,
  ou 49 € par bien (5 photos + annonce).
- Zone précise : Bordeaux et Gironde, puis toute la France (service à distance). Pourquoi : forte densité de
  mandataires, et prospection possible bien par bien sur les annonces vides.
- Preuve de demande / paiement : staging virtuel classique en agence de rendu à 30 à 80 € par photo (24-72 h) ;
  home staging physique à 2 000-3 000 € par bien. [Genroom](https://genroom.io/fr/virtual-staging-real-estate),
  [SeLoger, home staging](https://edito.seloger.com/conseils-d-experts/vendre/home-staging-permet-de-vendre-vite-fourchette-haute-marche-interview-42774.html),
  [Tensoria](https://tensoria.fr/blog/home-staging-virtuel-ia-immobilier).
- Concurrence vérifiée : « home staging virtuel prix par photo agence immobilière » → outils IA en libre-service
  (Genroom dès 0,50 €/photo), éditeurs anglophones. « home staging Bordeaux tarif » → aucun prestataire local,
  seulement des conseils SeLoger et une consultante efficity. Verdict : le libre-service tire les prix vers le bas.
  L'angle « fait pour vous + contrôle qualité + annonce » reste vendable aux mandataires peu techniques. Validé
  avec prudence.
- Légal : mention obligatoire « photo retouchée / staging virtuel » sur l'annonce (sinon pratique trompeuse).
  [Tensoria](https://tensoria.fr/blog/home-staging-virtuel-ia-immobilier). Pas de loi Hoguet (prestation graphique).
- Coût d'entrée : crédits d'outil IA de génération d'images estim. 30 € + domaine 12 € = **42 €**.
- Mini business plan (estim.) : hypothèses 40 mandataires démarchés par e-mail B2B, 10 % de clients récurrents
  à 2 biens par mois. M1 : 5 biens = 245 €. M3 : 15 biens/mois = 735 €/mois. M6 : 25 biens/mois = 1 225 €/mois.
  M12 : estim. 30 biens/mois. Saisonnalité : faible (creux en août).
- Premier test 7 jours + seuil kill : 3 biens traités gratuitement pour 3 mandataires (avant/après), puis offre
  payante à 30 mandataires. Kill si moins de 2 commandes payées en 7 jours.
- Score /50 : 36 (demande 8, concurrence 5, premier euro 9, légal 8, profil 6).

### T11 · Pages « prix au m² par quartier » (DVF) et leads vendeurs pour mandataires
- Modèle · Payeur · Prix : pages par quartier construites à partir des données publiques DVF, avec formulaire
  « faire estimer mon bien ». Lead transmis à un mandataire exclusif par quartier. Payeur : le mandataire. Prix :
  estim. 30 à 60 € le lead, ou 99 €/mois d'exclusivité de quartier.
- Zone précise : villes moyennes (Angers, Tours) quartier par quartier. Pourquoi : les acteurs nationaux couvrent la
  ville, rarement le micro-quartier avec des ventes réelles commentées. (Choix non vérifié par une recherche
  dédiée : à faire au J1.)
- Preuve de demande / paiement : des plateformes vendent des leads vendeurs aux agences et mandataires
  (CGV d'achat de leads chez Immovrai, article RealAdvisor). [Immovrai, CGV](https://www.immovrai.com/cgv),
  [RealAdvisor, achat de leads](https://realadvisor.fr/fr/pro/blog/achat-de-lead-mandat-immobilier). Prix unitaire :
  **non trouvé**.
- Concurrence vérifiée : « prix lead vendeur immobilier estimation en ligne » → MeilleursAgents (mise en relation
  avec 2 agences), Efficity (estimation gratuite et agence). Verdict : concurrence nationale forte. Validé
  uniquement sur l'angle micro-quartier avec exclusivité, score bas.
- Légal : loi Hoguet. Le site transmet un contact et ne négocie rien, ne fait signer aucun mandat : apport
  d'affaires, mais requalification possible si le rôle déborde. [Thèse UT Capitole, applicabilité de la loi Hoguet](https://publications.ut-capitole.fr/49067/1/Applicabilit%C3%A9%20de%20la%20loi%20Hoguet-20260210-085725.pdf).
  Préférer une rémunération forfaitaire au lead, contrat écrit. Une estimation affichée doit être présentée comme
  indicative. RGPD : consentement du vendeur et nom du mandataire destinataire.
- Coût d'entrée : domaine 12 € + publicité test estim. 150 € = **162 €**.
- Mini business plan (estim.) : hypothèses 3 quartiers vendus à 99 €. M1 : pages et 1 mandataire en test. M3 : 2 ×
  99 € = 198 €/mois. M6 : 4 quartiers = 396 €/mois. M12 : 6 quartiers, estim. 594 €/mois. Saisonnalité : printemps.
- Premier test 7 jours + seuil kill : 10 mandataires d'Angers démarchés. Kill si aucun n'accepte un test payant.
- Score /50 : 26 (demande 6, concurrence 3, premier euro 5, légal 5, profil 7).

### T12 · Prescription d'acheteurs vers les chasseurs immobiliers (mutations et expatriés)
- Modèle · Payeur · Prix : contenu « s'installer à Nantes en 3 mois » pour cadres mutés et expatriés de retour,
  avec un formulaire qui oriente vers un chasseur immobilier. Payeur : le chasseur ou le réseau, au succès.
  Prix : part des honoraires (non chiffrée publiquement), estim. 10 % des honoraires.
- Zone précise : Nantes, puis Bordeaux. Pourquoi : villes de mutation, honoraires de 2 à 3,5 % avec un minimum
  de 7 900 € TTC jusqu'à 250 000 €.
- Preuve de demande / paiement : honoraires au succès de 2 à 3,5 % ; un réseau publie des CGV « prescripteur »
  (rémunération des apporteurs). [Mon Chasseur Immo Nantes](https://www.monchasseurimmo.com/achat-immobilier/pays-de-la-loire/loire-atlantique/nantes),
  [CGV prescripteur](https://compte.monchasseurimmo.com/hubfs/Prescripteurs/CGV_prescripteur.pdf) (PDF non lu :
  la lecture a échoué, montant non confirmé), [Immodvisor Nantes](https://www.immodvisor.com/professionnels/chasseur-immobilier/pays-de-la-loire/loire-atlantique/nantes).
- Concurrence vérifiée : « chasseur immobilier Nantes honoraires » → Mon Chasseur Immo (7 résultats sur 10),
  Immodvisor. Verdict : la requête « chasseur » est tenue par le réseau. L'angle « mutation et retour d'expatriation »
  (contenu en amont) n'est pas servi : le réseau devient alors un client, pas un concurrent. 2e zone : à faire.
- Légal : apport d'affaires vers un professionnel titulaire de la carte T. Aucune négociation ni visite. Contrat
  écrit. Rémunération versée par le professionnel.
- Coût d'entrée : domaine 12 € + LinkedIn Ads test estim. 100 € = **112 €**.
- Mini business plan (estim.) : hypothèses 1 achat abouti pour 15 leads, part de 800 €. M1 à M3 : 0 € (cycle d'achat
  de 3 à 6 mois). M6 : 1 commission = 800 €. M12 : estim. 3 commissions = 2 400 €. Saisonnalité : mutations de juin
  à septembre.
- Premier test 7 jours + seuil kill : lire les CGV prescripteur et signer avec 1 réseau ou 2 chasseurs indépendants.
  Kill si aucun ne s'engage par écrit sur un montant.
- Score /50 : 27 (demande 7, concurrence 5, premier euro 2, légal 6, profil 7).

---

## Export

### T13 · Leads de frontaliers vers les fiduciaires luxembourgeoises (déclaration 100F)
- Modèle · Payeur · Prix : simulateur « dois-je déposer une déclaration au Luxembourg ? » (classe d'impôt,
  assimilation, seuil de 13 000 € ou de 90 %) qui oriente vers une fiduciaire partenaire. Payeur : la fiduciaire.
  Prix : estim. 30 à 50 € par lead.
- Zone précise : frontaliers de Moselle et de Meurthe-et-Moselle (Thionville, Metz, Longwy). Pourquoi : flux massif
  de frontaliers, règles complexes, double déclaration France (2047) et Luxembourg.
- Preuve de demande / paiement : premier dépôt par fiduciaire estimé à 200-500 € (site commercial, pas un barème).
  [SalaireClair](https://salaireclair.fr/blog/impots-luxembourg-frontalier-2026), règles d'assimilation :
  [Paperjam](https://paperjam.lu/article/ce-que-vous-devez-savoir-avant-de-declarer-vos-impots),
  formulaire 100F : [Frontaliers Grand Est](https://frontaliers-grandest.eu/formulaires/100f/).
- Concurrence vérifiée : « frontalier Luxembourg déclaration impôt fiduciaire tarif » → Paperjam, SalaireClair,
  Luxtoday, Toutsurmesfinances, Frontaliers Grand Est (association). Aucun outil de mise en relation avec des
  fiduciaires. Verdict : validé. 2e zone (frontaliers belges d'Arlon) : à faire.
- Légal : ne pas donner de conseil fiscal personnalisé (le simulateur informe et renvoie au professionnel).
  Apport d'affaires B2B transfrontalier : facture HT avec autoliquidation de TVA intracommunautaire. RGPD :
  données fiscales sensibles, minimiser (aucun revenu exact stocké).
- Coût d'entrée : domaine 12 € + publicité Meta Moselle estim. 120 € = **132 €**.
- Mini business plan (estim.) : hypothèses 40 €/lead. M1 : 2 fiduciaires signées. M3 (janvier) : 10 leads = 400 €.
  M6 (avril-juin, période déclarative) : 40 leads/mois = 1 600 €/mois. M12 : estim. 6 000 € cumulés. Saisonnalité :
  forte de février à juin, et rappel en décembre.
- Premier test 7 jours + seuil kill : 15 fiduciaires contactées. Kill si moins de 2 acceptent un prix ≥ 25 € par lead.
- Score /50 : 35 (demande 8, concurrence 8, premier euro 5, légal 6, profil 8).

### T14 · Leads vers les entreprises de titres-services à Bruxelles
- Modèle · Payeur · Prix : pages par commune bruxelloise (Ixelles, Uccle, Woluwe) « aide-ménagère titres-services
  disponible », formulaire, transmission à une entreprise agréée. Payeur : l'entreprise agréée. Prix : estim.
  20 à 40 € par client actif.
- Zone précise : Région de Bruxelles-Capitale, communes aisées du sud-est. Pourquoi : dispositif massif, le client
  choisit l'agence et non l'aide-ménagère, et on ne trouve aucun annuaire comparatif dans les résultats.
- Preuve de demande / paiement : titres-services passés de 10,20 € à 11,40 € au 1er janvier 2026 à Bruxelles ;
  certaines agences facturent en plus des frais administratifs. [RTBF](https://www.rtbf.be/article/titres-services-3000-emplois-d-aide-menagere-en-moins-en-un-an-11765645),
  [BX1, frais administratifs](https://bx1.be/categories/news/des-agences-bruxelloises-de-titres-services-demandent-des-frais-administratifs-a-leurs-clients/),
  [economie-emploi.brussels](https://economie-emploi.brussels/media/124/download). Que les agences acceptent de payer
  un lead n'est **pas prouvé** (estim.).
- Concurrence vérifiée : « titres-services Bruxelles trouver aide ménagère entreprise agréée commune » → sources
  publiques, presse, ONEM. Aucun comparateur. Verdict : validé sous réserve. 2e zone (Wallonie, Namur) : à faire.
- Légal : droit belge. Vérifier que la réglementation des titres-services n'interdit pas aux entreprises agréées de
  rémunérer un apporteur : **point bloquant à lever au J1**. RGPD (identique dans l'UE).
- Coût d'entrée : domaine .be estim. 12 € + publicité test estim. 100 € = **112 €**.
- Mini business plan (estim.) : hypothèses 30 € par client. M1 : 3 agences signées. M3 : 10 clients = 300 €.
  M6 : 25 clients/mois = 750 €/mois. M12 : estim. 6 000 € cumulés. Saisonnalité : rentrée et janvier.
- Premier test 7 jours + seuil kill : question écrite au SPRB + appel à 10 agences. Kill si interdiction ou moins de 2
  agences intéressées.
- Score /50 : 28 (demande 7, concurrence 8, premier euro 4, légal 3, profil 6).

### T15 · Sites + paiement Wave et Orange Money pour hébergements et commerces au Sénégal
- Modèle · Payeur · Prix : export de l'agence. Site vitrine + réservation + encaissement Wave et Orange Money
  pour auberges, lodges et commerces (Saly, Dakar). Payeur : l'établissement. Prix : estim. 250 000 FCFA (environ
  380 €) de mise en place + 10 000 FCFA par mois.
- Zone précise : Dakar (Almadies, Plateau) et Petite-Côte (Saly). Pourquoi : Wave dominant, frais marchands
  d'environ 1 %, clientèle touristique et diaspora qui paie à distance.
- Preuve de demande / paiement : frais marchands Wave d'environ 1 %, API avec webhooks signés, NINEA et RCCM exigés
  pour le marchand. Un intégrateur local publie de nombreux guides, signe d'une demande.
  [Kolonell, intégration de l'API Wave](https://kolonell.com/fr/blog/wave-business-api-integration-guide-2026),
  [Kolonell, frais Wave](https://kolonell.com/fr/blog/wave-frais-1-pourcent-vraie-marge-marchand-senegal-2026).
  Les chiffres viennent d'un intégrateur, non de Wave : à confirmer sur business.wave.com.
- Concurrence vérifiée : « Wave Sénégal paiement marchand API » → Kolonell (agence concurrente, 8 résultats sur 10),
  TechCabal. Verdict : un concurrent local établi, mais le marché des PME est vaste. Validé, score moyen.
  2e zone (Abidjan) : à faire.
- Légal : le compte marchand est au nom du client (NINEA). Le dev facture une prestation depuis la France (export
  de services, TVA non applicable, art. 259 CGI à vérifier). Aucun encaissement pour compte de tiers.
- Coût d'entrée : 0 € de voyage (vente à distance par WhatsApp et LinkedIn) + domaine de démo 12 € + publicité Meta
  Sénégal estim. 50 € = **62 €**.
- Mini business plan (estim.) : hypothèses 1 client par mois après M2. M1 : démo et 1 client à prix réduit (200 €).
  M3 : 2 clients = 960 € cumulés. M6 : 5 clients = 2 100 € + 75 €/mois. M12 : 10 clients, estim. 4 000 € + 150 €/mois.
  Saisonnalité : saison touristique de novembre à avril, Tabaski et vacances de la diaspora.
- Premier test 7 jours + seuil kill : 30 établissements contactés par WhatsApp avec une démo. Kill si moins de 3
  conversations qualifiées.
- Score /50 : 30 (demande 6, concurrence 5, premier euro 5, légal 7, profil 7).

---

## Rejetées (1 ligne, 1 raison)

| # | Idée | Raison du rejet |
|---|---|---|
| R01 | Leads B2C de cours de surf (Hossegor) | Verrouillé : CheckYeti, Adrenactive, Tourisme Landes tiennent la SERP ([CheckYeti](https://www.checkyeti.com/fr/d/2051/15926)). Repris en B2B (T01). |
| R02 | Leads B2C de baptêmes de parapente (Annecy) | Verrouillé : Manawa, Sport Découverte, Cap Adrénaline, Adrenactive, CheckYeti ([Manawa](https://www.manawa.com/fr-FR/activite/france/annecy/parapente/bapteme-de-parapente-au-dessus-du-lac-dannecy/1532)). Repris en B2B (T02). |
| R03 | EVJF et EVG par ville (Bordeaux) | Verrouillé : Funbooker (6 résultats sur 9), Cap Adrénaline, Topito ([Funbooker](https://www.funbooker.com/fr/theme/evjf/bordeaux)). |
| R04 | Permis bateau (La Rochelle) | Verrouillé : Adrenactive, Cap Adrénaline, Sport Découverte, devispermis.fr ([devispermis](https://devispermis.fr/villes/la-rochelle/permis-bateau)). |
| R05 | Réparation de vélos à domicile (Lyon) | Roulez Jeunesse domine et publie des prix bas (révision à 36 €), panier faible ([Roulez Jeunesse](https://blog.roulezjeunesse.com/top-5-reparateurs-velo-lyon/)). |
| R06 | Animateurs d'anniversaire enfants (Lille) | Verrouillé : CitizenKid et Funbooker ([CitizenKid](https://www.citizenkid.com/lille/anniversaire/animateur-anniversaire-enfant)). |
| R07 | Activités enfants pendant les vacances scolaires | Offre surtout municipale et associative (HelloAsso, mairies) à tarif social : personne ne paie le lead ([HelloAsso](https://www.helloasso.com/associations/agit-he/evenements/stage-enfants-ados-vacances-de-toussaint)). |
| R08 | Garde-meubles étudiants l'été (Lille) | Panier faible (box d'environ 50 €/mois, 2019), aucun prix étudiant trouvé, et self-stockage national ([Économie Matin](https://www.economiematin.fr/?p=73847)). |
| R09 | Toiletteurs à domicile (Toulouse) | Aucun prix publié, aucune preuve de paiement trouvée, offre très clairsemée ([chien.com](https://www.chien.com/adresse/19-0-0-0-0-toiletteur-canin-16.php)). |
| R10 | Leads viager | Recherche faite : aucune preuve de prix des leads ni de commission d'apporteur en viager. |
| R11 | Conciergerie Airbnb à Bruxelles | Réglementation hostile (un hôte sur six enregistré, amendes jusqu'à 80 000 €) ([BX1](https://bx1.be/categories/news/pres-de-650-dossiers-ouverts-a-bruxelles-locations-airbnb/), [DH](https://www.dhnet.be/regions/bruxelles/2022/09/30/hotels-airbnb-et-hebergements-touristiques-a-bruxelles-procedures-assouplies-sanctions-augmentees-BRD2UHU4WVEUHPFNDTGMIRBDRE/)). |
| R12 | Conciergerie Airbnb à Lyon | Saturé (Toploc, GuestReady, Welkeys) et plafond de 90 nuits depuis 2026 ([GuestReady](https://www.guestready.com/?p=25436)). Repris sur La Rochelle et Annecy (T05). |
| R13 | Excursions dans le désert depuis Marrakech | Offre homogène au même prix, places de marché, risque d'arnaque perçu ([Routard](https://www.routard.com/forums/t/excursion-dans-le-desert-au-depart-de-marrakech/239227)). |
| R14 | Surf camps à Taghazout | Agrégateurs (BookSurfCamps, Hostelworld) et affiliation déjà en place ([The Surf Atlas](https://thesurfatlas.com/surfing-morocco/taghazout-surf-camps/)). |
| R15 | Déménagement à Genève | Déjà au catalogue (déménagement) et MOVU et HelloSafe tiennent la requête ([HelloSafe](https://hellosafe.ch/demenagement/geneve)). |
| R16 | Leads d'artisans à Abidjan | Allô Dépanne existe déjà ; capacité des artisans à payer un lead non prouvée ([AnnuaireCI](https://annuaireci.com/entreprises/allodepanne-abidjan-cote-divoire/)). |
| R17 | Soumissions de déneigement au Québec | Contrats signés avant l'hiver (fenêtre 2026 déjà passée) et concurrence non vérifiée ([Noovo](https://www.noovomoi.ca/style-et-maison/finances/deneigement-hausse-prix.html)). |
| R18 | Contrôle technique moto (leads ou prise de RDV) | Panier de 50 à 75 € non réglementé ; la vague 2026 (immatriculations 2020-2021) se termine le 31/12/2026, la suivante est diffuse ([France Carte Grise](https://www.francecartegrise.com/reglementation/controle-technique-moto-2026/)). |
| R19 | Leads DJ, traiteurs et wedding planners | Mariages.net tient le marché et facture 130 à 150 €/mois aux prestataires ([Trustpilot](https://at.trustpilot.com/review/mariage.net)). |
| R20 | Leads de gîtes de groupe en B2C | Les centrales (Gîtes de France, GreenGo) tiennent la requête ; repris en B2B (T03, T04). |

### Non validées faute de preuve (budget de recherche épuisé, à reprendre)

| # | Idée | Ce qui manque |
|---|---|---|
| N01 | Ménage de fin de séjour, Les Sables-d'Olonne | Prix prouvé (100 à 120 € par ménage, [Holidu](https://www.holidu.fr/d/50899945)) mais concurrence non vérifiée. |
| N02 | Cours particuliers (angle hors Superprof) | Aucune recherche faite : Superprof non vérifié. |
| N03 | Colocations par ville universitaire | Aucune recherche faite. |
| N04 | Jobs étudiants | Aucune recherche faite. |
| N05 | Permis moto et auto-écoles | Seul devispermis.fr a été vu (La Rochelle). Comparateurs nationaux non vérifiés. |
| N06 | Moniteurs de ski indépendants (B2B, même modèle que T01) | Aucune recherche par station. |
| N07 | Location de salles par département | Aucune recherche faite. |
| N08 | Duplication en Suisse romande (T07 ou T10) | Prix suisses non vérifiés. |
| N09 | Kayak et canoë (Ardèche, gorges du Tarn) | Aucune recherche faite. |
| N10 | Guides locaux | Aucune recherche faite (domination présumée de GetYourGuide et Viator, non vérifiée). |
