# 04 · Apps mobiles, micro-SaaS et outils web payants (marché francophone)

Agent 4/8 · 22 octobre 2026 · famille : apps freemium/paywall, micro-SaaS, outils web payants.

## Avertissement de méthode (à lire avant tout)

- **Objectif non atteint : 8 idées validées sur 28 visées, 14 rejets.** Le budget de recherche web
  (200 requêtes partagées entre les 8 agents) a été épuisé après 33 requêtes de cet agent, et la
  récupération directe de pages (WebFetch) échouait en DNS. Je n'ai pas complété la liste avec des
  idées non vérifiées.
- **Les 8 validations sont provisoires.** L'étape « 1 recherche store » de la méthode n'a été faite
  que pour le permis bateau. Pour toutes les autres idées, la concurrence vient d'**une** recherche web
  (agrégateurs Capterra/GetApp, articles). Avant d'investir, faire la recherche App Store / Play Store
  indiquée dans chaque bloc.
- Toute estimation porte la mention « estim. ». Taux de conversion repris des benchmarks RevenueCat 2026
  fournis dans le brief (paywall dur 10,7 %, freemium 2,1 %). Change USD→EUR : estim. 1 $ ≈ 0,92 €.
- Barème du score /50 : demande prouvée /10, vide concurrentiel FR /10, coût et vitesse du premier euro /10,
  faisabilité solo avec Claude Code + Vercel /10, risque légal et dépendance plateforme (inversé) /10.
- Postes de coût communs (sans les outils déjà payés : Claude Code Max, Vercel Pro) : domaine .fr
  estim. 8 à 12 €/an ; Stripe sans frais fixes (commission par paiement) ; base Supabase en offre gratuite
  pour un MVP (estim., à vérifier sur les limites actuelles) ; Apple Developer 99 $/an (≈ 91 €) ;
  Google Play 25 $ une fois (≈ 23 €) ; API Claude pour les wrappers IA, en consommation.
- Une section « Pistes en attente de vérification » liste les idées non instruites, sans verdict :
  elles ne sont ni validées ni rejetées.

---

## Idées validées (provisoires)

### S01 · Pension Pro — gestion d'écurie de propriétaires (pensions de chevaux)
- Modèle · Payeur · Prix : SaaS web (PWA) · gérant d'écurie de pension ou de centre équestre · 29 €/mois ou 290 €/an (sous le bas de fourchette de 40 € observé), essai de 30 jours.
- Cible / zone : écuries de pension et petits centres équestres, France entière, surtout en zones rurales et périurbaines. Fonctions : fiche cheval, soins et maréchal refacturés, facture mensuelle au propriétaire, portail propriétaire.
- Preuve de demande ou de revenu : les logiciels américains se vendent : Barn Manager dès 10 $/mois ([source](https://www.capterra.fr/software/164823/barnmanager)), EquestFile dès 29,95 $ ([source](https://www.getapp.fr/software/2057860/equestfile)). Un éditeur français indique qu'un SaaS équestre spécialisé coûte 40 à 150 € HT/mois et que le sur-mesure se justifie quand le centre « combine pensions haut de gamme, soins refacturés » ([source](https://kolonell.com/fr/blog/meilleur-logiciel-gestion-centre-equestre-rennes-saas-equestres-logiciels-club-mesure-2026)).
- Concurrence vérifiée : web « logiciel gestion pension chevaux écurie propriétaires facturation » et « application gestion écurie française pensionnaires » → seulement des outils anglophones (Barn Manager, disponible au Canada et aux États-Unis seulement, en anglais ; Stable Secretary, Breeders App) et du sur-mesure → **pas de solution française dédiée aux pensions trouvée**. Store : non fait (à faire : « gestion écurie », « pension cheval »). Les logiciels de club (réservation de reprises) existent mais traitent un autre besoin.
- Légal : RGPD (données des propriétaires, facturation) : registre des traitements, hébergement UE, DPA Stripe. Factures conformes (mentions, TVA ; la TVA équestre est un sujet spécifique, à faire valider par un comptable). Pas de statut réglementé.
- Coût d'entrée : domaine 12 € + Stripe 0 € fixe + Supabase gratuit (estim.) = **≈ 12 €**.
- Mini business plan (estim.) : hypothèses : 300 visites/mois en SEO et groupes Facebook équestres dès M3, 3 % d'essais, 40 % de conversion après l'essai, 29 €/mois. M1 : 5 écuries testeuses gratuites, 0 €. M3 : 4 payants, MRR 116 €. M6 : 12 payants, MRR 348 €. M12 : 30 payants, MRR 870 €.
- Premier test 7 jours + seuil kill : page d'attente + annonce dans 5 groupes Facebook « gérants d'écurie » + 20 appels à des pensions. Kill si moins de 5 gérants acceptent une démo, ou aucun ne dit payer au moins 20 €/mois.
- Score /50 : **38** (demande 7, vide FR 9, coût 9, faisabilité 8, risque 5 : cycle d'adoption lent, gérants peu outillés).

### S02 · Studio — gestion des élèves pour professeurs de musique indépendants
- Modèle · Payeur · Prix : SaaS web + PWA · professeur indépendant (auto-entrepreneur) · 9,90 €/mois ou 89 €/an ; plan « école » à 4 € par professeur supplémentaire.
- Cible / zone : professeurs de musique à domicile ou en studio (piano, guitare, chant), francophones (France, Belgique, Suisse, Québec). Planning, absences et reports, facturation conforme auto-entrepreneur, paiements, suivi de travail de l'élève.
- Preuve de demande ou de revenu : My Music Staff, logiciel pensé « pour les enseignants privés et les studios », 4,8/5 sur 761 avis Capterra ([source](https://www.getapp.fr/software/1974051/my-music-staff)), facturé environ 14,95 à 16,95 $/mois selon les agrégateurs ([source](https://www.capterra.com.au/software/148451/my-music-staff)). Au Royaume-Uni, 9,95 £/mois plus 2,95 £ par professeur ([source](https://musicteachermagazine.co.uk/content/other/my-music-staff-app)).
- Concurrence vérifiée : web « logiciel gestion élèves professeur de musique indépendant planning facturation » → My Music Staff, TeacherZone, Teachworks (anglophones), Elvis et Auboutdufil (orientés écoles, prix sur demande) ([source](https://www.appvizer.fr/education/ecole-musique)) → **niche « indépendant francophone, facture conforme » non servie de façon visible**. My Music Staff a une page en français : il faut vérifier sa localisation (factures FR, TVA) avant de lancer. Store : non fait.
- Légal : RGPD, avec des élèves mineurs (consentement parental, minimisation). Factures auto-entrepreneur (mention « TVA non applicable, art. 293 B du CGI »). L'avance immédiate du crédit d'impôt (services à la personne) serait un plus mais demande une habilitation : non instruite.
- Coût d'entrée : domaine 10 € = **≈ 10 €** (PWA, pas de store au départ).
- Mini business plan (estim.) : 500 visites/mois en SEO (« facture cours de piano », « logiciel prof de musique ») à M6, 4 % d'essais, 35 % de conversion. M1 : 10 professeurs bêta. M3 : 8 payants, MRR 79 €. M6 : 25 payants, MRR 248 €. M12 : 70 payants, MRR 693 €.
- Premier test 7 jours + seuil kill : landing en français + publication dans 3 groupes de professeurs de musique + 30 messages directs. Kill si moins de 15 inscriptions sur liste d'attente, ou si My Music Staff s'avère déjà localisé pour la France.
- Score /50 : **37** (demande 8, vide FR 6, coût 9, faisabilité 9, risque 5).

### S03 · Attest'Chaudière — attestation d'entretien sur mobile pour chauffagistes indépendants
- Modèle · Payeur · Prix : app mobile (Expo) + back-office web · chauffagiste artisan · 14,90 €/mois ou 149 €/an. L'attestation PDF signée est envoyée au client sur place, avec rappel automatique de l'entretien annuel suivant.
- Cible / zone : chauffagistes et plombiers-chauffagistes indépendants (non adhérents FFB), France entière ; argument commercial : le rappel annuel crée du chiffre d'affaires récurrent.
- Preuve de demande ou de revenu : l'attestation est obligatoire et doit être remise sous 15 jours après la visite ([source](https://www.capeb.fr/actualites/rappel-les-attestations-dentretien-sont-obligatoires-pour-les-systemes-de-chauffage)). La FFB a mis des attestations en PDF remplissable dans l'app de l'UMGCCP, **réservée aux adhérents** ([source](https://www.ffbatiment.fr/actualites-batiment/actualite/attestations-entretien-chaudiere-pac)). Un logiciel commercial dédié (Check Heat, sur PDA) existait dès 2010 ([source](https://www.batiproduits.com/fiche/produits/logiciel-d-edition-automatique-d-attestations-d-e-p69101533.html)). **Revenus d'un acteur : non trouvés.**
- Concurrence vérifiée : web « application attestation entretien chaudière chauffagiste logiciel » → outil FFB réservé aux adhérents, Check Heat ancien (disponibilité à vérifier) → verdict : vide pour les non-adhérents, mais les logiciels de devis et de facturation du bâtiment (non vérifiés ici) peuvent intégrer la fonction. Store : non fait, **prioritaire** (« attestation entretien chaudière »).
- Légal : contenu de l'attestation fixé par arrêté (le modèle doit suivre la réglementation en vigueur, à relire avant développement). RGPD : clients particuliers, rappels par SMS ou e-mail fondés sur l'intérêt légitime ou le contrat.
- Coût d'entrée : Apple 99 $ (≈ 91 €) + Google 25 $ (≈ 23 €) + domaine 10 € = **≈ 124 €**.
- Mini business plan (estim.) : canal : groupes Facebook d'artisans, partenariats avec des négoces de chauffage. M1 : 10 testeurs. M3 : 10 payants, MRR 149 €. M6 : 30 payants, MRR 447 €. M12 : 80 payants, MRR 1 192 €.
- Premier test 7 jours + seuil kill : maquette cliquable + 25 appels à des chauffagistes CAPEB. Kill si moins de 5 se disent prêts à payer 10 €/mois ou plus, ou si la recherche store révèle une app gratuite équivalente.
- Score /50 : **36** (demande 7, vide FR 7, coût 7, faisabilité 8, risque 7).

### S04 · VTC Prépa — QCM de l'examen taxi / VTC (T3P)
- Modèle · Payeur · Prix : app mobile à paywall dur · candidat · 9,99 €/semaine ou 29,99 € pour 3 mois (accès jusqu'à l'examen), essai de 3 jours.
- Cible / zone : candidats aux examens taxi et VTC organisés par les CMA, en Île-de-France, en région PACA et dans les métropoles.
- Preuve de demande ou de revenu : examen à notes éliminatoires (moins de 6/20 en sécurité routière, moins de 4/20 en anglais éliminent même avec 10 de moyenne) ([source](https://travail-industrie.com/nos-formations/formation-preparer-examen-taxi-vtc-t3p/module/2/chapitre/3)). Statistiques d'admissibilité publiées par la CMA Normandie ; un tableau lu indique environ 41 % d'admissibles VTC, sur une session dont l'année n'est pas clairement indiquée ([source](https://cma-normandie.fr/wp-content/uploads/2026/06/GLOBAL-Statistiques-admissibilite-2017-26-MAI-2026.pdf)). Une app sur abonnement existe déjà, ce qui prouve un modèle payant ([source](https://apps.apple.com/us/app/id1572185213)). **Volume national de candidats : non trouvé.**
- Concurrence vérifiée : web « application QCM examen VTC taxi T3P révision » → une app datée de 2021 (abonnement), des centres de formation payants → verdict : peu d'offre mobile récente. Store : non fait.
- Légal : pas de statut ; ne pas se présenter comme centre agréé ; questions rédigées soi-même, sans copier les annales protégées.
- Coût d'entrée : Apple ≈ 91 € + Google ≈ 23 € + RevenueCat gratuit en dessous de son seuil de revenu (à vérifier) = **≈ 114 €**.
- Mini business plan (estim.) : 800 installs/mois à M6 via TikTok et groupes de chauffeurs, paywall dur à 10,7 % (benchmark), panier moyen 25 €. M1 : 150 installs, 16 payants, 400 €. M3 : 400 installs, 43 payants, 1 075 €/mois. M6 : 800 installs, 86 payants, 2 150 €/mois. M12 : 1 000 installs, 107 payants, 2 675 €/mois. Revenu non récurrent : il faut acquérir en continu.
- Premier test 7 jours + seuil kill : landing avec 20 QCM gratuits + prévente à 19 € via Stripe, promue dans 5 groupes de chauffeurs VTC. Kill si moins de 10 préventes sur 300 visites.
- Score /50 : **35** (demande 7, vide FR 7, coût 8, faisabilité 8, risque 5 : programme qui change, acquisition payante).

### S05 · AEPE Révise — révision du CAP Accompagnant éducatif petite enfance
- Modèle · Payeur · Prix : app mobile freemium, puis paywall dur sur les examens blancs · candidat (souvent en reconversion ou candidat libre) · 24,99 € par session ou 6,99 €/mois.
- Cible / zone : candidats libres au CAP AEPE et futures assistantes maternelles, France entière.
- Preuve de demande ou de revenu : les éditeurs vendent des préparations avec QCM : Foucher « tout-en-un » avec plus de 200 QCM interactifs ([source](https://www.editions-foucher.fr/node/36773)), Vuibert avec plus de 200 QCM ([source](https://www.livres-medicaux.com/petite-enfance-cap-bep/60960-cap-accompagnant-educatif-petite-enfance-2025-2026.html)). **Effectifs de candidats : non obtenus** (la page de résultats CAP 2024 de la DEPP n'a pas pu être lue).
- Concurrence vérifiée : web « application révision CAP AEPE petite enfance QCM » → 30 QCM gratuits sur un site de formation, et la mention qu'il « n'existe pas de QCM national » ([source](https://travail-industrie.com/nos-formations-en-ligne/quizz/qcm-cap-aepe)), des manuels papier → **aucune app dédiée trouvée**. Store : non fait.
- Légal : contenu original (pas de reprise des manuels) ; référentiel public (arrêté du 30 novembre 2020 modifié le 2 mai 2025).
- Coût d'entrée : Apple ≈ 91 € + Google ≈ 23 € = **≈ 114 €** ; génération et relecture du contenu avec Claude (inclus dans Max).
- Mini business plan (estim.) : 500 installs/mois à M6 (groupes Facebook de candidates, relais petite enfance), conversion 5 % (entre freemium et paywall dur), 20 € de panier moyen. M1 : 100 installs, 5 payants, 100 €. M3 : 300 installs, 15 payants, 300 €/mois. M6 : 500 installs, 25 payants, 500 €/mois. M12 : 700 installs, 35 payants, 700 €/mois. Pics de ventes avant les sessions de mai et juin.
- Premier test 7 jours + seuil kill : quiz web gratuit de 40 questions avec capture d'e-mail, publié dans 5 groupes. Kill si moins de 100 quiz terminés ou moins de 3 % de clics sur l'offre payante.
- Score /50 : **33** (demande 6, vide FR 8, coût 8, faisabilité 8, risque 3 : volume non prouvé, saisonnalité).

### S06 · RDV par WhatsApp — agent de prise de rendez-vous clé en main pour artisans et instituts
- Modèle · Payeur · Prix : service productisé, puis abonnement · coiffeur, barbier, esthéticienne, garagiste · installation 149 € + 29 €/mois (API WhatsApp Cloud + agenda Google + rappels).
- Cible / zone : commerces de proximité sans logiciel de réservation, surtout ceux dont la clientèle écrit déjà sur WhatsApp (barbiers, onglerie, DOM-TOM). Inspiré des mini-programmes WeChat et des usages LINE au Japon : réserver dans la messagerie.
- Preuve de demande ou de revenu : offres de freelances vendues entre 171 $ et 686 $ pour cette mise en place ([source](https://comeup.com/fr/service/517908/automatiser-la-prise-de-rendez-vous-sur-whatsapp-avec-un-agent-ia)) ; un indépendant spécialisé coiffeurs et instituts à 200 €/jour ([source](https://www.malt.fr/profile/ludovickauvaetupu)). **Nombre de ventes réelles : non vérifié.**
- Concurrence vérifiée : web « chatbot WhatsApp prise de rendez-vous artisan coiffeur » → freelances, Flozic (no-code, offre gratuite), guides n8n DIY ([source](https://wassenger.com/blog/fr/systeme-de-reservation-de-rendez-vous-ia-whatsapp-guide-complet-n8n)) → verdict : pas de produit français clé en main par métier ; outils no-code gratuits mais pas « fait pour vous ». Risque frontal : Planity et les logiciels de salon (non vérifiés ici). Store : sans objet.
- Légal : RGPD (numéros de clients, sous-traitant Meta) ; respect de la politique WhatsApp Business ; consentement aux rappels.
- Coût d'entrée : numéro dédié (estim. 0 à 5 €) + domaine 10 € + coûts Meta à l'usage (les messages de service sont annoncés gratuits par Meta, à vérifier dans la grille en vigueur) = **≈ 15 €**.
- Mini business plan (estim.) : prospection locale via l'agence existante. M1 : 2 installations, 298 € + MRR 58 €. M3 : 6 clients, MRR 174 € (+ installations). M6 : 15 clients, MRR 435 €. M12 : 35 clients, MRR 1 015 €.
- Premier test 7 jours + seuil kill : démo vidéo + 30 visites en porte-à-porte de barbiers et instituts. Kill si moins de 2 installations payées sous 14 jours.
- Score /50 : **34** (demande 6, vide FR 6, coût 9, faisabilité 8, risque 5 : dépendance à Meta).

### S07 · Cahier de liaison numérique pour assistantes maternelles
- Modèle · Payeur · Prix : app mobile freemium · assistante maternelle (les parents ont un accès gratuit) · 3,99 €/mois ou 34,99 €/an (aligné sur la médiane RevenueCat de 34,80 $).
- Cible / zone : assistantes maternelles agréées, France entière. Journal du jour (repas, siestes, activités, photos), heures d'arrivée et de départ, export du relevé mensuel d'heures.
- Preuve de demande ou de revenu : une assistante maternelle a créé MuMy, cahier de liaison numérique, et s'y consacre à plein temps depuis 2023, ce qui prouve un besoin ressenti par le métier ([source](https://gambin.co/blog/fiche-de-liaison-assistante-maternelle/)). **Tarif et revenus de MuMy : non trouvés.**
- Concurrence vérifiée : web « application cahier de liaison assistante maternelle » → MuMy ; Klassroom (pensé pour l'école) → verdict : un seul acteur de niche identifié, positionnement à vérifier. Store : non fait, **indispensable** (les apps de crèches ou de gestion d'assistante maternelle peuvent couvrir le besoin).
- Légal : données d'enfants mineurs : consentement parental, minimisation, hébergement UE, pas de reconnaissance faciale. **Exclure du produit les champs de santé** (allergies, traitements), qui relèvent des données sensibles de l'article 9 du RGPD, ou les limiter à un pictogramme sans détail, pour rester hors du périmètre exclu.
- Coût d'entrée : Apple ≈ 91 € + Google ≈ 23 € = **≈ 114 €**.
- Mini business plan (estim.) : 400 installs/mois à M6 (groupes Facebook d'assistantes maternelles, relais petite enfance), freemium 2,1 % (benchmark). M1 : 100 installs, 2 payants. M3 : 250 installs/mois, 10 payants cumulés, MRR 40 €. M6 : 35 payants, MRR 140 €. M12 : 100 payants, MRR 400 €.
- Premier test 7 jours + seuil kill : sondage et liste d'attente dans 5 groupes. Kill si moins de 50 inscrites ou si un concurrent gratuit installé apparaît dans les stores.
- Score /50 : **30** (demande 6, vide FR 5, coût 8, faisabilité 8, risque 3 : petit panier, sensibilité des données d'enfants).

### S08 · Marge Seconde Main — suivi de stock et de marge pour revendeurs Vinted, sans automatisation
- Modèle · Payeur · Prix : SaaS web (PWA) · revendeur d'occasion semi-pro · 7,99 €/mois. Stock, prix d'achat, marge nette après frais, export comptable micro-entreprise, aide à la vérification DAC7. **Aucun bot ni repost**, pour rester conforme aux CGU.
- Cible / zone : revendeurs Vinted et Leboncoin en France et en Belgique.
- Preuve de demande ou de revenu : les revendeurs paient des outils : Vintedge en trois formules à 12,99, 29,99 et 59,99 € TTC/mois ([source](https://friptadium.com/blogs/actualites/vintedge-avis-prix-outil-vinted)) ; aux États-Unis, Vendoo de 12,49 à 49,99 $/mois ([source](https://blog.vendoo.co/vendoo-pricing-explained-and-why-its-worth-the-investment)).
- Concurrence vérifiée : web « outil crosspost annonces Vinted Leboncoin » → Vintedge, Vintex, Clemz, Resell Pro, Margeo (comparatif publié par Margeo lui-même) ([source](https://margeoapp.com/blog/comparatif-applications-crosslisting-france-2026)) → verdict : marché occupé, **angle restant = conformité et comptabilité sans risque de bannissement** (Crosslist a cessé d'accepter de nouveaux comptes Vinted après des suspensions, [source](https://crosslist.com/blog/vinted-cross-listing)). Margeo semble proche de cet angle : à vérifier avant de lancer. Store : non fait.
- Légal : RGPD léger ; ne pas donner de conseil fiscal personnalisé (rester sur l'export et les rappels de seuils publics).
- Coût d'entrée : domaine 10 € = **≈ 10 €**.
- Mini business plan (estim.) : 1 000 visites/mois via TikTok et YouTube de revendeurs, 2 % d'essais, 40 % de conversion. M1 : 0 €. M3 : 6 payants, MRR 48 €. M6 : 20 payants, MRR 160 €. M12 : 50 payants, MRR 400 €.
- Premier test 7 jours + seuil kill : tableur gratuit « calcul de marge Vinted » en lead magnet, avec liste d'attente pour la version web. Kill si moins de 150 téléchargements ou si Margeo couvre déjà l'export comptable à un prix inférieur.
- Score /50 : **29** (demande 8, vide FR 3, coût 9, faisabilité 9, risque 0 : concurrence forte et dépendance aux plateformes).

---

## Rejetées (14)

| # | Idée | Raison (1 ligne) | Source |
|---|---|---|---|
| R01 | App de révision du permis bateau côtier | Au moins 7 apps déjà en store, dont des gratuites complètes (Code Marine, plus de 400 questions) et une app d'école à 5,99 € | [App Store](https://apps.apple.com/fr/app/bato/6649152218) · [Code Marine](https://mwm.ai/apps/code-marine-permis-bateau/6756659478) |
| R02 | Planning de rendez-vous pour toiletteurs canins | Koalendar gratuit à vie, Easybel 30 à 54 €/mois, Groomsoft, Vagaro, SimplyBook gratuit | [comparatif](https://anolla.com/fr/meilleur-logiciel-de-toilettage-canin) · [Koalendar](https://koalendar.com/fr/logiciel-prise-rendez-vous-pour/toilettage-animalier) |
| R03 | Livret d'accueil digital pour locations saisonnières | Marché pris (Mon Livret d'Accueil avec IA et 15 langues, Smoobu, Welkeys) | [source](https://lespepitestech.com/startup-de-la-french-tech/mon-livret-daccueil) |
| R04 | Wrapper IA de réponse aux avis Google pour restaurants | Une dizaine d'outils (ReviewReply, Revplies, Nelova) et Google teste une réponse IA native | [source](https://fr.custplace.com/business/reponses-automatiques-aux-avis-google-business-profile/) |
| R05 | Crosslisting automatisé Vinted et Leboncoin | Contraire aux CGU, pas d'API ; Crosslist a arrêté Vinted après des suspensions | [source](https://crosslist.com/blog/vinted-cross-listing) |
| R06 | Logiciel pour syndic bénévole | Offre payante installée et peu chère (Copriciel dès 120 €/an, Simply Syndic de l'ARC, Syndic24) | [ARC](https://arc-copro.fr/sites/default/files/pieces-jointes/2026/03/Prestations%20et%20outils%20SNP_2026.pdf) |
| R07 | QCM d'entraînement à l'examen civique 2026 | Équivalent gratuit officiel (QCM data.gouv sur les questions du ministère) et sites gratuits | [data.gouv](https://www.data.gouv.fr/reuses/qcmexamencivique) |
| R08 | App de pêche : réglementation et parcours par département | Outils gratuits des fédérations (Génération Pêche, GEOPECHE) ; données éclatées par département | [source](https://www.peche63.com/sites/default/files/Newsletter-FD63-Mai2020.pdf) |
| R09 | Générateur de DUERP pour TPE | Outil public gratuit OiRA (INRS) [connaissance antérieure, non revérifiée ce jour] et DUERP de freelances autour de 74 $ | [Comeup](https://comeup.com/en/service/523525/rediger-votre-duerp-conforme-au-code-du-travail-par-un-expert-hse) |
| R10 | Registre de sécurité ERP pour petits commerces | Acteur SaaS installé (Lootibox), réglementation lourde, aucune preuve que les petits ERP paient | [source](https://lespepitestech.com/blog/2026/02/10/registre-de-securite-dematerialise-pourquoi-et-comment-passer-au-numerique) |
| R11 | Registre d'élevage et suivi des ruches pour apiculteurs | Apitracer Lite gratuit jusqu'à 100 ruches couvre les amateurs ; prix de la version Pro inconnu | [source](https://www.reussir.fr/apiculture/une-application-pour-organiser-son-travail) |
| R12 | Livre de police numérique (brocanteurs, dépôts-vente) | Légalité du format électronique non confirmée (une réponse parlementaire juge la saisie informatique insuffisante) et certification NF203 probablement au-dessus de 200 € (non chiffrée) | [AN](https://questions.assemblee-nationale.fr/dyn/13/questions/QANR5L13QE19690.pdf) · [NF203](https://infocert.org/en/nf203-livre-de-police/) |
| R13 | Cueillette de champignons (identification) | Responsabilité en cas d'intoxication : exclusion de principe du brief | — |
| R14 | Outil de dossier de location | DossierFacile, service public gratuit (cité dans le brief) [non revérifié ce jour] | — |

---

## Pistes en attente de vérification (non comptées)

Ces pistes n'ont reçu aucune recherche, faute de budget. Elles ne sont ni validées ni rejetées.
À instruire en priorité (signal fort d'un modèle étranger ou d'une obligation légale) :

1. **Logiciel de tournées pour piscinistes** (modèle américain Skimmer) : à vérifier, concurrence FR inconnue.
2. **Certificat de ramonage numérique + rappels** pour ramoneurs : même mécanique que S03.
3. **Bordereau de suivi des vidanges** pour vidangeurs agréés d'assainissement non collectif : obligation légale, outil inconnu.
4. **Facturation de cours particuliers avec avance immédiate du crédit d'impôt** : habilitation URSSAF à étudier.
5. **Planning de garde alternée et dépenses partagées** : 2houses à vérifier.
6. **Gestion des déposants** en dépôt-vente de vêtements pour enfants.
7. **Gestion de société de chasse (ACCA)** et carnet de battues numérique : aucun logiciel trouvé, demande payante non prouvée.
8. **Concours de catégorie C** (gardien de la paix, ATSEM, adjoint administratif) : QCM sur mobile.
9. **Wrapper IA d'annonces immobilières pour agents indépendants.**
10. Pistes du brief non instruites : gestion de gîtes, planning d'auto-école, AMAP, clubs sportifs, tontine, calendrier des déchets, rappels de CT, carnet de santé du chien ou du cheval, potager, généalogie, code de la route, BAFA, descriptions Vinted, menus traduits, CV par métier, planning de saisonniers. Plusieurs ont probablement un leader gratuit (AMAP, clubs, généalogie, code de la route, calendrier des déchets, planning de saisonniers), mais je ne l'ai pas vérifié ce jour et je ne les ai donc pas rejetées.
