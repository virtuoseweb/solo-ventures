# 10 · Micro-SaaS verticaux pour des professions françaises mal outillées

Agent 10 · 22 octobre 2026 · famille : Micro-SaaS métiers (abonnement 15 à 79 €/mois) · IDs M01 à M05 · outil de recherche : Exa uniquement.

## Avertissement de méthode (à lire avant tout)

- **Objectif non atteint : 5 idées validées sur 22 visées, 68 rejets documentés.** Je n'ai pas complété la liste avec des idées non vérifiées. En 2026, la longue traîne des logiciels métiers français est saturée : plateformes multi-métiers (Bosseo, Stenko, MyTour, TePublico, Onatys Doc, Planisfaire, Yoyolo, Hunimalis, Organilog, Terraxia, Shifton), éditeurs en série qui publient un micro-SaaS par métier (par exemple Julien Jimenez : NettoiVitre, CommandeKit, AmapFlow, Houblia, Eauclara, Guichetia, BrocaReg) et logiciels gratuits (GlysOS, Shifton, Webreed, VPDive, Piscinis, Vidasso). Presque chaque métier testé a 3 à 10 logiciels, souvent avec une page dédiée.
- **Exa n'est pas google.fr.** Exa remonte surtout des pages descriptives et récentes. Un petit outil français mal référencé peut m'avoir échappé, ce qui joue contre les 5 validations. À l'inverse, tout concurrent trouvé par Exa existe vraiment. Avant d'investir, refaire les requêtes de chaque fiche sur google.fr et dans les stores.
- **Nombre de requêtes.** Chaque idée validée a reçu au moins 3 requêtes formulées différemment. Pour la plupart des rejets, 1 ou 2 requêtes ont suffi, parce qu'elles montraient déjà 3 acteurs ou plus, ou un outil gratuit. La règle des 3 requêtes s'applique seulement avant d'écrire « aucun concurrent ». Certaines formulations anciennes sont résumées de mémoire, c'est indiqué dans la fiche concernée.
- Toute estimation porte la mention « estim. ». Barème du score /50, repris du fichier 04 : demande prouvée /10, vide concurrentiel FR /10, coût et vitesse du premier euro /10, faisabilité solo /10, risque légal et dépendance plateforme (inversé) /10. Coûts communs : domaine estim. 10 €/an, Stripe sans frais fixe, Supabase et Vercel en offre gratuite pour un MVP (estim.).
- **Contre-vérification utile pour le catalogue.** L'idée S01 « Pension Pro » (fichier 04) affirme qu'il n'y a pas de solution française pour les pensions de chevaux. Mes requêtes en trouvent au moins dix : GlysOS (gratuit), Equimondo (dès 19 € HT), Gecurie (39 €), MyHorseBase (39 €), Horsora, Ecurios, Equestrions, Equionline, Horse Ledger, Epivet Breeder. **S01 est à requalifier en rejet (règles 1 et 2).**
- **Pas de doublon.** Le fichier 13 rejette des *sites de niche* grand public sur le gardiennage de camping-cars et l'entretien de tombes. M02 et M03 sont des logiciels vendus *aux professionnels* de ces métiers : le client et la concurrence ne sont pas les mêmes.
- **Ce qui distingue les 5 idées validées** : un flux de travail inhabituel que les outils génériques gèrent mal. Ce sont l'itinérance avec un dossier différent par commune (forains), le stockage saisonnier (gardiennage), le travail dans un lieu sans réseau avec une preuve photo (cimetières) et la location avec changement de taille (luthiers).

---

## Idées validées

### M01 · Dossier de place : conformité et candidatures pour forains, cirques et structures itinérantes
- Modèle · Payeur · Prix : SaaS web (PWA, mobile d'abord) · entreprise foraine (manège, stand, confiserie), cirque, loueur de structure itinérante · 19 €/mois ou 190 €/an, plus 9 €/mois par attraction supplémentaire.
- Cible / zone : France. **Taille** : environ 5 700 entreprises foraines et 50 400 forains selon la Fédération des forains de France ([source](https://federationdesforainsdefrance.fr/statistiques/les-entreprises-foraines-france-europe)) ; 35 000 fêtes foraines par an et 30 000 familles foraines selon une question écrite au Sénat ([source](https://www.senat.fr/questions/base/2019/qSEQ190510485.html)). Fonctions : coffre-fort des pièces avec date d'expiration (RC, contrôle technique du manège, immatriculation, carte de commerçant non sédentaire, extrait de registre CTS), dossier généré pour chaque commune, calendrier de tournée avec les dates limites de candidature, attestation de bon montage pré-remplie que le monteur signe.
- Preuve de demande : obligations réglementaires. Les manèges relèvent du décret n° 2008-1458 (contrôle technique, attestation de bon montage). Les communes demandent un dossier complet pour chaque fête : une quinzaine de pièces dans le règlement de fête foraine de Marguerittes (marguerittes.fr), règles de la préfecture du Var (var.gouv.fr), formulaire d'occupation du domaine public de Pessac (pessac.fr). Pour les chapiteaux, l'extrait du registre de sécurité doit parvenir au maire au moins un mois avant l'ouverture, avec l'attestation de bon montage (article CTS 31 : [source](https://static.rt-events.fr/document/reglementation-cts.pdf) ; [fiche de la ville de Tours](https://www.tours.fr/app/uploads/1/2025/11/Chapiteaux-tentes-et-structures-Guide-ERP-Fiche-16.pdf)). **Modèle étranger payant** : Kirmes-Tournee-Planer (Allemagne, schaustelleranfragen.de), 28,50 € HT par an, 2 200 fêtes référencées.
- Concurrence vérifiée : 4 requêtes Exa, dont 3 résumées de mémoire : « logiciel ou application pour forains, gestion administrative des fêtes foraines » / « dossier de demande de place fête foraine, application pour forain » / « planificateur de tournée Kirmes Schausteller » / « registre de sécurité numérique chapiteaux CTS logiciel » (exacte). Côté organisateurs et communes : Marktmeister Pro (Allemagne, page FR), openMarchéForain (Adullact), GEODP. Côté contrôle : Octav, et Véri-Scène, qui rédige ses rapports dans son logiciel interne Logi-Scène. Autres : Cojego (structures gonflables), Midway World (États-Unis, gratuit, en anglais), fetes-foraines.fr (annonces), une page « forain » du CRM générique TePublico, FleetCast (veille d'événements). → **Aucun outil français côté forain** pour préparer, envoyer et suivre les dossiers de place. Angle non servi.
- Légal : pas de statut réglementé pour l'éditeur. L'outil n'atteste rien : le responsable du montage signe l'attestation et les contrôles restent ceux des organismes agréés. RGPD : pièces d'identité, hébergement dans l'UE.
- Coût d'entrée : domaine 10 € + Stripe 0 € fixe + Supabase gratuit (estim.) = **≈ 10 €**.
- Mini business plan (estim.) : canaux : syndicats régionaux, groupes Facebook de forains, présence sur deux fêtes. Les candidatures se préparent l'hiver pour la saison suivante, donc un lancement en novembre tombe bien (estim.). M1 : 8 forains pilotes gratuits. M3 : 12 payants, MRR 228 €. M6 : 30 payants, MRR 570 €. M12 : 80 payants, MRR 1 520 €.
- Premier test 7 jours + seuil kill : landing et vidéo de 60 s « votre dossier de place en 5 minutes », 40 messages ou appels (syndicats, groupes), offre « je monte votre premier dossier ». Kill si moins de 5 forains envoient leurs pièces, ou moins de 2 prépaient l'année.
- Score /50 : **37** (demande 7, vide FR 9, coût 9, faisabilité 7, risque 5 : maturité numérique faible, dossiers différents selon les communes).

### M02 · Hivernage : gestion des gardiennages de camping-cars, caravanes et bateaux
- Modèle · Payeur · Prix : SaaS web avec espace client · exploitant de gardiennage (agriculteur avec hangar, camping, garage, port à sec) · 19 €/mois jusqu'à 50 places, 29 €/mois jusqu'à 150.
- Cible / zone : petits gardiennages français de moins de 100 places, en dessous de la taille visée par Stallingo. **Taille** : pas de statistique INSEE, car le métier n'a pas de code NAF propre. Un fichier commercial (baseemailspro) recense 343 établissements « gardiennage camping-car ». La place de marché MonHangar annonce plus de 3 000 emplacements ([source](https://monhangar.fr/prix-hivernage-camping-car/)). **Prix pratiqués** : 120 à 420 €/an pour un camping-car selon MonHangar ; 240 à 560 €/an à Vias ([source](https://gardiennage-caravane.com/tarifs)).
- Preuve de demande : Stallingo vend ce logiciel aux Pays-Bas et l'a traduit en français : 39 €/mois jusqu'à 150 véhicules, 89 € jusqu'à 500, 179 € sans limite ([source](https://stallingo.nl/fr)). Nautic Data inclut les contrats de gardiennage dans son offre pour ateliers nautiques, à 117 € HT/mois ([source](https://nauticdata.fr/tarifs-logiciel-nautisme/)).
- Concurrence vérifiée : « logiciel gestion gardiennage camping-car caravane » / « application hivernage bateaux caravanes gestion emplacements contrats » / « logiciel gestion gardiennage hivernage camping-cars caravanes bateaux emplacements contrats annuels France ». Résultats : Stallingo (néerlandais, paiement iDEAL et Bancontact, pour 100 à 1 200 véhicules), fmCaravan (Pays-Bas), Nautic Data et Captain Crews (bateaux), Galaxy Hotel (campings, contrats d'hivernage), Yoyolo et CRM-Loc (génériques), MonHangar (place de marché, pas un outil de gestion). → **Pas d'outil français natif pour le petit gardiennage.** Angle : moins de 100 places, prélèvement SEPA et carte, attestation de gardiennage pour l'assureur, état des lieux photo à l'entrée, créneaux de sortie le week-end, Factur-X (réception 2026, émission 2027). Risque : Stallingo peut descendre en gamme.
- Légal : contrat de dépôt (Code civil), modèle à faire relire. RGPD. Pas de réglementation propre à l'éditeur.
- Coût d'entrée : **≈ 10 €**.
- Mini business plan (estim.) : panier moyen 25 € (estim.). M1 : 3 pilotes. M3 : 6 payants, MRR 150 €. M6 : 15 payants, MRR 375 €. M12 : 40 payants, MRR 1 000 €.
- Premier test 7 jours + seuil kill : en pleine rentrée d'hivernage (octobre-novembre), appeler 40 gardiennages listés sur MonHangar et les annuaires. Kill si moins de 3 pilotes, ou si plus de la moitié utilisent déjà Stallingo.
- Score /50 : **35** (demande 7, vide FR 5, coût 9, faisabilité 8, risque 6).

### M03 · Gazonnier : fiche tombe, abonnements et compte rendu photo pour l'entretien de sépultures
- Modèle · Payeur · Prix : SaaS en PWA, utilisable hors ligne · auto-entrepreneur ou petite entreprise d'entretien de sépultures · 15 €/mois ou 150 €/an ; 29 €/mois pour une équipe.
- Cible / zone : France. **Taille** : l'INSEE n'a pas de donnée. 183 entrepreneurs individuels en activité ont un objet social qui mentionne le « nettoyage de tombes » (Pappers, octobre 2025, cité par [Ouest-France](https://www.ouest-france.fr/economie/commerce/video-il-y-a-une-vie-dans-les-cimetieres-cette-aide-soignante-se-lance-dans-le-nettoyage-de-tombes-720b1abb-0bb3-39e3-83b1-4b8b6e53e079)). Le chiffre réel est probablement plus élevé : le code APE 96.03Z est partagé avec les pompes funèbres. **Prix pratiqués** : 30 à 100 € la prestation, 200 à 400 € l'abonnement annuel (nubiz.fr) ; Stelnance 69 à 109 € la prestation, 739 à 1 529 € par an ([source](https://stelnance.fr/)). Fonctions : fiche tombe (cimetière, carré, allée, GPS, photo repère), formules d'abonnement (Rameaux, fête des mères, Toussaint), photos avant et après envoyées à la famille, mode hors ligne pour les cimetières sans réseau, page de commande avec paiement, facture de micro-entreprise.
- Preuve de demande : les deux réseaux nationaux ont fait développer leur propre outil. En Sa Mémoire a une PWA hors ligne avec cartographie des cimetières ([source](https://www.datasolution.fr/archives/en-sa-memoire-application-web-et-mobile-nouveau-defi/)). Entretien du Souvenir utilise un bot WhatsApp relié à Sellsy ([source](https://www.analy.fr/portfolio/eds-whatsapp-interventions)). Un business plan type prévoit 1 500 € pour « site internet + logiciel de tournées » ([source](https://ia-promethee.fr/exemple-business-plan-entretien-sepultures.html)). Modèles étrangers : MeisterOffice Grabpflege en Suisse ([source](https://meisteroffice.ch/fr/grabpflege)), Tending et Grave Angels Partner aux États-Unis.
- Concurrence vérifiée : « logiciel entreprise entretien de tombes sépultures abonnement rapport photo avant après » / « application pour auto-entrepreneur entretien de sépultures gestion clients tombes cimetières photos » / « créer son entreprise d'entretien de tombes micro-entreprise nombre de prestataires ». Résultats : Funéria (ERP de marbrerie qui inclut des contrats d'entretien, fait pour les pompes funèbres), MeisterOffice (suisse, factures QR suisses, listes de contrôle en allemand, gratuit pour l'instant), plateformes de mise en relation côté familles (Stelnance, EternalCare), outils internes des réseaux. → **Aucun SaaS français pour l'indépendant.**
- Légal : activité non réglementée tant qu'elle ne touche pas au service extérieur des pompes funèbres (legalplace.fr). Respect du règlement de chaque cimetière. RGPD pour les données des clients.
- Coût d'entrée : **≈ 10 €**.
- Mini business plan (estim.) : la Toussaint est le pic de l'année. M1 : 10 bêta-testeurs gratuits jusqu'à la Toussaint. M3 : 8 payants, MRR 120 €. M6 : 20 payants, MRR 300 €. M12 : 45 payants, MRR 675 €.
- Premier test 7 jours + seuil kill : avant la Toussaint 2026, envoyer 30 messages à des gazonniers trouvés sur Pappers, Google Maps et Facebook, avec le rapport photo automatique offert pour la Toussaint. Kill si moins de 8 inscrits actifs, ou si moins de 2 disent payer 15 €.
- Score /50 : **34** (demande 5, vide FR 8, coût 9, faisabilité 8, risque 4 : une plateforme comme Stelnance peut offrir un outil gratuit à ses prestataires ; marché petit).

### M04 · Location d'instruments pour luthiers et magasins de musique
- Modèle · Payeur · Prix : SaaS web avec page de location pour les parents · luthier, magasin de musique, réparateur d'instruments à vent · 25 €/mois jusqu'à 100 contrats, 45 €/mois au-delà.
- Cible / zone : France. **Taille** : environ 1 200 luthiers ([Ouest-France / ONISEP 2021](https://www.ouest-france.fr/education/orientation/fiches-metiers/formation-quatre-questions-sur-le-metier-de-luthier-ere-7128491)), dont environ 500 luthiers du quatuor ([Ouest-France 2026](https://www.ouest-france.fr/bretagne/rennes-35000/a-rennes-les-luthieres-maelle-annezo-et-louisa-schmitt-font-chanter-le-bois-en-le-transformant-en-violon-39ce4390-99ab-11f1-83c6-a529e8dc728d)). Le secteur des instruments compte 2 869 entreprises selon la [Philharmonie de Paris](https://metiers.philharmoniedeparis.fr/facteur-instrument-musique.aspx), et 2 800, dont 1 900 en métiers d'art, selon l'étude INMA et CSFI de 2023 (infoartisanat.artisanat.fr). Flux de travail : location mensuelle de 14 à 116 € (luthier-nancy.com, alticelli.fr, ypluthier.com), caution par chèque non encaissé, changement de taille chaque année pour les enfants (de 1/16 à 4/4), loyers déduits en cas d'achat, prélèvements.
- Preuve de demande : deux luthiers bordelais ont créé Musilok en 2019 pour leur propre parc, puis l'ont commercialisé avec l'assureur Verspieren. Il coûte un abonnement plus 149 € HT d'installation et fonctionne seulement sous Windows ([source](https://www.musilok.com/)). Aux États-Unis, Music Shop Suite gère la location par taille pour 49 $/mois ([source](https://musicshopsuite.com/violin-shop-luthier-software)).
- Concurrence vérifiée : « logiciel location d'instruments de musique luthier contrat location violon élève prélèvement mensuel » / « gestion parc location violons violoncelles luthier logiciel en ligne mandat SEPA échange de taille » / « suivi des locations d'instruments magasin de musique Excel gratuit ou application ». Résultats : Musilok (Windows), Service 9000 de Technic-Soft (GMAO et SAV multi-métiers avec une page musique qui couvre location et parc, prix non relevé) ([source](https://www.technic-soft.fr/logiciels-metiers/musique-instruments/)), Lasido et Belami (écoles de musique, prêt d'instruments), modèles de tableur en anglais. → 2 acteurs français, aucun avec une interface pour les familles. Angle : location en ligne par les parents (choix de taille, mandat SEPA signé en ligne), changement de taille sans nouveau contrat, compteur des loyers déductibles, rappel de révision annuelle, attestation pour l'assurance scolaire.
- Légal : mandat SEPA. Une location avec option d'achat peut relever du crédit à la consommation selon sa structure : faire valider le modèle de contrat. C'est le principal risque.
- Coût d'entrée : **≈ 10 €**, plus les frais SEPA à la transaction (GoCardless ou Stripe).
- Mini business plan (estim.) : le pic est à la rentrée de septembre. M1 : 3 pilotes. M3 : 6 payants, MRR 150 €. M6 : 15 payants, MRR 375 €. M12 : 35 payants, MRR 875 €.
- Premier test 7 jours + seuil kill : 30 appels à des luthiers du quatuor (annuaire du GLAAF, Google Maps). Kill si moins de 4 acceptent une démo, ou si la plupart sont satisfaits de Musilok.
- Score /50 : **32** (demande 6, vide FR 5, coût 9, faisabilité 7, risque 5).

### M05 · Officiant : espace couple et proches, brouillon de cérémonie (validation fragile)
- Modèle · Payeur · Prix : SaaS web avec brouillon rédigé par IA · officiant de cérémonie laïque indépendant · 15 €/mois ou 129 €/an.
- Cible / zone : France, Belgique, Suisse. **Taille** : plus de 2 500 officiants professionnels en 2026 (organiser-son-mariage.fr). Un site de recrutement en compte environ 3 300 en citant l'ICM et l'UPM, chiffre non vérifié à la source (sponta.io). Selon l'Assocem, un officiant célèbre 10 à 20 cérémonies par an, 73 % exercent en micro-entreprise et le prix moyen est de 1 540 € ([livre blanc](https://assocem.org/wp-content/uploads/2026/09/Livre-blanc-Officiant-de-ceremonie-2025.pdf)).
- Preuve de demande : IBDA a une offre dédiée aux officiants, avec un plan gratuit et un plan Pro à 49 €/mois ([source](https://ibda.fr/logiciel-officiant-ceremonie)). Aux États-Unis : Solemnly (gratuit, 25 $ pour activer les paiements), Officiantly, CeremonyDesk (9,99 à 24,99 $), OrdainedPro (39,95 $).
- Concurrence vérifiée : 3 requêtes, dont « application pour officiant de cérémonie laïque questionnaire couple écriture du discours déroulé ». Résultats : IBDA (France), WeddingPlan (tous les prestataires du mariage), TonMariage.fr (outil gratuit pour les couples : déroulé et fiche officiant), CérémonIA (IA pour les couples dont un proche officie), outils anglophones. → **Concurrence réelle.** L'angle restant est étroit : un questionnaire envoyé au couple *et* aux proches pour recueillir les anecdotes, un brouillon en français, le minutage et le livret, à 15 € au lieu de 49 €.
- Légal : aucun (la cérémonie n'a pas de valeur légale). RGPD : données intimes des couples. L'officiant relit tout contenu généré par IA.
- Coût d'entrée : **≈ 10 €**, plus l'API Claude à la consommation (estim. moins de 0,10 € par brouillon).
- Mini business plan (estim.) : les cérémonies se préparent de janvier à avril. M1 : 10 bêta-testeurs. M3 : 10 payants, MRR 150 €. M6 : 25 payants, MRR 375 €. M12 : 60 payants, MRR 900 €.
- Premier test 7 jours + seuil kill : contacter 40 officiants (annuaires Zankyou et Mariages.net, membres de l'Assocem). Kill si moins de 5 testent, ou si le plan gratuit d'IBDA leur suffit.
- Score /50 : **29** (demande 4, vide FR 3, coût 9, faisabilité 8, risque 5).

---

## Rejetées

Règles du brief : **r1** outil gratuit équivalent · **r2** au moins 3 acteurs français couvrant précisément la niche, sans angle non servi démontrable · **r3** aucune preuve de demande · **r4** statut réglementé ou interdiction · **r5** coût d'entrée supérieur à 200 €. **J** = rejet de jugement hors des cinq règles (cible trop petite, besoin absorbé par un outil voisin), signalé comme tel.

| # | Idée (métier) | Règle | Ce qui sort (prix relevés) | Sources (domaines vus via Exa) |
|---|---|---|---|---|
| 1 | Maréchal-ferrant (tournées, facturation) | r2 | SlyMaréchalerie 50 €/mois, Equimondo 19 €, Hippofact 9,90–74,90 €, Bosseo 19,90 €, Stenko, MyTour, Staff Maréchalerie | slymarechalerie.com, equimondo.fr/logiciel-de-gestion-marechal-ferrant.php, hippofact.com, bosseo.fr |
| 2 | Pisciniste (modèle Skimmer) | r1 + r2 | Piscinis gratuit, Shifton gratuit, PoolCenter 49 €, Clorly, Terraxia, InterFast, Lebin | piscinis.com, poolcenter.app/logiciel-pisciniste |
| 3 | Ramoneur (certificats décret 2023-641) | r2 | Ramio 39 €, Ramonia 79 €, OpenFire 30 €/utilisateur, Valideo 0–25 €, 7enligne, InterFast, MyTour, Planisfaire | ramio.fr/logiciel-ramoneur, 7enligne.fr, inter-fast.fr |
| 4 | Vidangeur ANC (bordereaux de matières de vidange) | r2 | Okapia OS, AssainPro, Vidang'o, Facilitime | okapia-os.com/logiciel-vidangeur, assainpro.fr |
| 5 | Taxidermiste | J | Pas d'outil FR, mais 130 à 150 professionnels seulement ; modèles américains Taxidermy Systems, MountChief | senat.fr/questions/base/2022/qSEQ220700645.html |
| 6 | Accordeur de pianos | r2 | Gazelle (localisé en FR), Piano Service App (FR, gratuit), KeyRoute 20 $, Cantus 47,95 $, PianoCal | onlinepianoatlas.com/piano-service-app/fr |
| 7 | Éleveur canin ou félin (registre, cessions) et pension | r1 + r2 | Webreed gratuit, Hunimalis, Affixe, Kookie Breeder, Son Espace Éleveur, Gestelv (4 000 éleveurs), Gespet | affixe.app |
| 8 | Club de plongée (fiche de sécurité) | r1 + r2 | VPDive gratuit, DivePilot 39 €, Mabadive, 6temic, Supadive, Kananas ; environ 2 500 clubs | vpdive.com |
| 9 | Mandataire judiciaire individuel (MJPM) | r2 | Filya, Majélis, Accel Gerancia dès 49 €, TutSpeed, Proxima 80–150 € | — |
| 10 | Tuteur familial | r1 + r2 | Tutello gratuit ou 12,90 €, Majélis Familial, Tutelle facile 30 €/an, Beny 5 € | tutello.fr |
| 11 | Organisateur de vide-greniers (registre) | r1 | Vidasso gratuit, Le Placier gratuit, Standly gratuit sous 30 exposants, Brocly, MyBrocante 40 €/an | vidasso.fr/logiciel-vide-grenier, mesoccasions.com/organisateurs |
| 12 | Coordonnateur SPS | r2 | Onatys Doc, GCSPS, Doksy | — |
| 13 | Thanatopracteur | r2 | MyThanato, ThanaSoft, ThanatoKit 49 €, Thanaplan, LogiFunus | — |
| 14 | Éleveur ovin ou caprin (registre d'élevage) | r2 | Troupeasy, Synel, Pilot'Élevage 8,25 €, Gismo, BAOBA, UBIQ | baoba.ag |
| 15 | Registre des EPI antichute (cordistes, élagueurs) | r1 + r2 | GearTracker gratuit jusqu'à 100 EPI, Registre-EPI, CertPilot, controle-reglementaire.fr, Substock, Trottr | geartracker.net/fr |
| 16 | Agent commercial multicartes | r2 | Concuerda, Kardinal, KepleR, AgentCom, SalesIro, Talos | — |
| 17 | Ostréiculteur | r2 | Oyster Flow, OstraOS, Hubi, Edulis, Ostregest | — |
| 18 | Club de tir | r2 | Cibléo, Dontshoot, Cerbère, Artemis, Narvik, MonClub | cibleo.app |
| 19 | Laveur de vitres | r2 | NettoiVitre 19 €, TradeYoke, Khosmos, Contractor+ | nettoivitre.com |
| 20 | Boulangerie (tournées, livraison aux pros) | r2 | CommandeKit, CERES, Cookee, Smart SELLER | — |
| 21 | Manifestations sportives sur la voie publique | r1 | Téléservice d'État gratuit | declaration-manifestations.gouv.fr |
| 22 | ACCA et piégeurs | r1 + r2 | Mes Chasses gratuit, Chasse Société moins de 3 €/chasseur/an, GestionChasse, E-FAUN, Huntrexia | chasse-societe.fr |
| 23 | Détective privé | r1 + r2 | B-r-i-e-f (plan gratuit, 30 agences), Onatys, CaseKrof, nQuest, TePublico | — |
| 24 | Exposant de marchés de créateurs | r2 | jegeremesmarches.com 4,90 €, ComptArtisan, TousAuMarché, Événements Créateurs, Im360 Expo | jegeremesmarches.com |
| 25 | Petits importateurs soumis au règlement EUDR | r2 | Konstata, TracaTerre, EUDRplot | — |
| 26 | Bois de chauffage | r2 | Planisfaire, Apinfor, Holzplaner24 (FR), Amos | — |
| 27 | Éleveur de volailles (biosécurité) | r2 | Gallinoo Pro, BAOBA, AvicPro, FarmManager, WeFeed | gallinoo.fr/pro |
| 28 | Artificier (déclarations CERFA 14098) | r2 | PyroDesk 29,90 €, Artifeu 190 €, PlanFeu gratuit | pyrodesk.com |
| 29 | Tatoueur (consentements, traçabilité) | r1 + r2 | KIPIK gratuit, Tattoomorrow, Skintrace, ConsentForm, Clic2Sign | — |
| 30 | AMAP | r1 + r2 | AmapJ gratuit (485 AMAP), Camap 7 €/an, AMAPress, AmapFlow 9 €, MonAmap | — |
| 31 | Microbrasserie (DRM, douanes) | r2 | Easybeer 19–99 €, BrewFactory, Grapify, Houblia (296 brasseries), AC LOG, Wavesoft | — |
| 32 | Facturation en Nouvelle-Calédonie et Polynésie (XPF) | r2 | NeoCompta, VOX, Ma Gestion NC, NeoFact, EazyBill, Lanika, ManaMoni, Fenua Compta | — |
| 33 | Autorisation de voirie pour artisans (AOT) | r2 | autorisation-voirie.fr 9,90 €, Kylak, Multani | autorisation-voirie.fr |
| 34 | Foreur de puits | r1 | Outils du BRGM gratuits (GesFor, DiaLog, DUPLOS) | brgm.fr |
| 35 | Commissaire enquêteur | r1 | registre-dematerialise.fr (payé par le porteur de projet), Publilégal, Grist OSP | registre-dematerialise.fr |
| 36 | Carnet sanitaire de piscine collective | r2 | Splashlog 99 €/an, Eauclara, My Pool Process, Aquatycia, AquaConform | — |
| 37 | Harmonie, chorale | r2 | NoteStand, Sostenutoo, WePlayIn.Band, ZoppaBox, Maestro | — |
| 38 | Guide de pêche, étang | r2 | Izidoor, Anolla, Activiteez, Fishing Booking, Catch Control | izidoor.io |
| 39 | Pompes funèbres | r1 + r2 | MENTOR gratuit, Yama-Soft dès 30 €, LogiFunus, Simplifia (1 200 PF), logicielfuneraire.com 110 €, Twist | — |
| 40 | Éleveur de NAC (registre) | r1 + r2 | ReptiNode gratuit, ZooExotic 1,50 €/animal/an, BDEND | — |
| 41 | Ressourcerie | r2 | GDR, TFshop, Okapia | — |
| 42 | Affouage (communes) | r1 | Grist (ANCT) gratuit, Berger-Levrault, JVS | — |
| 43 | Dossier de sécurité d'une fête associative | r1 | demarche.numerique.gouv.fr gratuit, Guichetia | — |
| 44 | Cordonnerie, retouche | r2 | Atch, Artizi, Trackin 19,99 €, SimpleCaisse, HoopoTrack, Hangers | — |
| 45 | Bonus réparation QualiRépar | r2 | Reparea, AlloRepair, Reparly, Donaa, Mon Atelier, ZIQY | — |
| 46 | Refuge pour animaux | r1 | Pawer gratuit, Vetly gratuit, Hygipet gratuit, Son Espace Refuge, Anigu | — |
| 47 | Constat d'état d'œuvres d'art | r2 | ArtReport, Horus 70–130 €/an, ARTreport | — |
| 48 | Food truck | r2 | Eno, Univents, FleetCast, Siouplaît, Nehos, Mon Food Truck, WikiFoodtruck | — |
| 49 | Ostéopathe animalier | r1 + r2 | Animalib gratuit jusqu'à 20 clients, OsteoPattes (bêta gratuite), Stenko, Hunimalis | — |
| 50 | Livre de police (brocanteurs, antiquaires, dépôts-vente) | r2 | LivreDePolice.com 19,90 € HT, Registeo, BrocaReg, Antiks, Vinto, e-inventaire, DEPOTVENTE.biz | livredepolice.com, registeo.fr, brocareg.com |
| 51 | Étalonnier, haras (saillies, juments en pension) | r1 + r2 | GlysOS gratuit, Horse Ledger, Equidéclic (Gynebase, Groomy), StudPulse, O-Haras, Equi-Web | glys.io/glysos/logiciel-haras, horse-ledger.com |
| 52 | Pareur bovin | r1 + r2 | Relevés de Prim'Holstein (gratuit pour les adhérents), Venotis Hoof Trimmer, Hoof Notes (Obione), VetIMPRESS, Hoof Supervisor (en français, Québec) | primholstein.com, venotis.fr |
| 53 | Atelier d'encadrement | r2 | Finkels, SimulArt (en français, 32,95 $/mois), Cube 43, TePublico, FramR | finkels.be, simulartstudio.com |
| 54 | Télépilote de drone (carnet de vol, MANEX) | r2 | AltiNest, Synaptiik, Dronops, Dronline, Clearance, DroneControl | altinest.fr, dronops.io |
| 55 | Dératisation (3D) | r2 | Organilog 3D 19 € HT, 3DPlus 49 € HT, Stann, Terraxia, Cadulis, XT-ERP | organilog-3d.com, 3dplus.app |
| 56 | Accueillant familial | r1 | CESU accueil familial (Urssaf) gratuit, qui produit le relevé mensuel | urssaf.fr |
| 57 | Surveillance de résidences secondaires | r2 | HomyTrust, Verifio, TidyClean, Check Easy (FR) ; Pruvek, Dwellwatch (États-Unis) | homytrust.fr, verifio.fr |
| 58 | Moniteur de ski indépendant | r2 | AirSportPro 19,90 €, Book'Adventure, Yoplanning, Activiteez, Izidoor, Bloowatch 59–149 €, GuideMate | airsportpro.fr/ski, bloowatch.com |
| 59 | Pépiniériste (passeport phytosanitaire) | r2 | mycorhize, La Graine (FlowOne), FermeGestion 0–9,90 € | mycorhize.com, fermegestion.fr |
| 60 | Prestataire d'éco-pâturage | J + r2 partielle | Vigie-Pâturage (120 à 1 500 €), 19.87 (outil Notion à achat unique), modules pâturage BAOBA et iBrebis ; cible d'environ 100 prestataires selon Animal & Cité | vigie-paturage.com, reussir.fr |
| 61 | Bateau-école | r2 | NauticAI, TePublico, Permolib 50–120 €, MonPermisPro | nauticai.fr, permolib.fr |
| 62 | Photographe scolaire | r1 + r2 | Scolaire.photo 0 €/mois, Lumys 6 %, PixFirst 3 %, souvenirs-scolaire 3,5 %, Loupio, Jingoo, Mexys | scolaire.photo, pixfirst.com |
| 63 | Coiffeuse en EHPAD | J + r2 partielle | Familizz (commande et paiement par les familles), Gestio (coiffure à domicile), Organilog EHPAD | familizz.com, gestio-app.fr |
| 64 | Déneigement privé | r1 + r2 | Shifton gratuit, Terraxia, Planfix ; Plannit, Flokon, Horizon (Québec, en français) | terraxia.fr, shifton.com |
| 65 | Contrôle des disconnecteurs | r1 + r2 | Digisco (Watts), DiscoNet, Docolab, Shifton (gratuit pour 1 ou 2 vérificateurs) | digisco.fr, disconet.fr, docolab.fr |
| 66 | Dégraissage des hottes de cuisine professionnelle | J | Aucun outil dédié trouvé, mais le besoin (certificat, rapport photo) est couvert par les logiciels de ramonage et d'intervention : InterFast, 7enligne, Ramio, MyTour | inter-fast.fr, 7enligne.fr |
| 67 | Pension de chevaux (modèle Barn Manager, déjà S01 au fichier 04) | r1 + r2 | GlysOS gratuit, Equimondo 19 € HT, Gecurie 39 €, MyHorseBase 39 €, Horsora, Ecurios, Equestrions, Equionline, Horse Ledger, Epivet | glys.io/glysos/logiciel-pension-cheval, equimondo.fr, gecurie.com |
| 68 | Courtier en vins de campagne | r2 | Bordereaux déjà échangés selon un protocole de place avec les ERP de négoce (MyMerch, SparkWine, ID200i, CERES, Red75) ; plateforme courtier.vin | mundata.fr/mymerch, courtier.vin |

## Pistes non instruites (sans verdict)

Distillateurs ambulants et bouilleurs de cru, entreprises de travaux forestiers et débardeurs, apiculteurs professionnels, biographes familiaux, fermes pédagogiques itinérantes, exploitants d'aires privées pour camping-cars. Vu le taux de saturation observé (68 rejets pour 5 validations), il faut s'attendre à des rejets pour la plupart.
