# 01 · Génération de leads et de demandes de devis pour artisans et services à domicile (particuliers, FR, par département ou par ville)

Agent 1/8 · rédigé le 22 octobre 2026. Hors rénovation énergétique et hors items déjà au catalogue (ANC/vidange, ramonage, élagage, OLD, frelons, désamiantage, punaises/dératisation, clôture/portail, IRVE copro, piscine, eau de pluie, débarras/succession, déménagement senior).

## Statut et limites, à lire en premier

- **28 idées validées, 34 rejets tracés.**
- **Outils :** environ 50 requêtes. La plupart sont passées par le moteur Exa : il renvoie les pages et des extraits, et non une page Google classée. Quelques-unes sont passées par WebSearch, géolocalisé aux États-Unis et peu exploitable pour une SERP française. Le verdict « Concurrence vérifiée » décrit donc **les pages qui remontent** sur la requête d'achat locale. Ce n'est pas un relevé de positions google.fr. **Avant de construire, il faut le refaire sur google.fr en navigation privée**, depuis la ville visée.
- **Chiffres :** tout chiffre sans lien est marqué « estim. ». Les prix des services viennent des pages citées (tarifs affichés par des professionnels ou des guides de prix). Ce sont des prix publics, pas des prix de transaction.
- **Prix du lead (repère commun, sourcé) :** BAT LEADS affiche un lead travaux partagé à partir de 25 € HT, un exclusif à partir de 75 € HT, et 35 € HT pour la serrurerie ou les PAC ([bat-lead.fr](https://bat-lead.fr/prix-lead-travaux)). HelloArtisan affiche 39 € HT le contact et 69 € HT le rendez-vous ([comparatif bat-lead.fr](https://bat-lead.fr/plateforme-artisan)). TravauxBTP vend le lead de 14 à 20 € ([travauxbtp.fr](https://www.travauxbtp.fr/tarifs-pro)). Dans les plans ci-dessous, le prix retenu par idée est **estim.** et se situe dans cette fourchette.

### Modèle type, commun aux 28 idées

1. Un site Astro par niche et par zone, déployé sur Vercel Pro (déjà payé). Il contient une page par ville ou par commune visée, un estimateur de prix sourcé, une FAQ réglementaire et un formulaire de qualification (photos, surface, délai).
2. Un formulaire qui **nomme l'acheteur** : « Votre demande sera transmise à [Entreprise X, SIRET], et seulement à elle ». La case de consentement n'est pas précochée. La mention RGPD précise la finalité, la durée de conservation et les droits.
3. La vente du lead se fait à l'unité, par virement ou Stripe, à 1 à 3 artisans locaux recrutés **par e-mail ou par téléphone B2B**. La prospection B2B vers des professionnels n'est pas visée par le régime de consentement préalable du démarchage des consommateurs. Les numéros figurent par ailleurs sur leurs fiches publiques. Variante : un forfait mensuel par zone exclusive, une fois le volume prouvé.
4. **Aucun appel sortant vers les particuliers.** Depuis le 11/08/2026, le démarchage téléphonique d'un consommateur exige son consentement préalable. Les leads sont donc entrants uniquement. Le rappel se fait par l'artisan, sur demande explicite du particulier.

### Hypothèses communes aux business plans (toutes estim.)

- Le coût d'entrée type est d'environ 160 à 190 €. Il comprend un domaine .fr (environ 10 € la première année, estim.), un test Google Ads de 120 à 150 € sur 7 à 14 jours, et 0 à 30 € d'outils (numéro virtuel ou crédit d'e-mails). Hébergement et code : 0 € de plus.
- Sur les requêtes de niche locales : CPC de 1 à 3 € (estim.), taux de conversion du formulaire de 5 à 10 % (estim.). Le SEO local d'un site neuf démarre lentement : quelques dizaines de visites par mois à M1, quelques centaines par ville et par niche à M6 si la concurrence est faible (estim.).
- Taux de leads effectivement vendus : 50 à 70 % des leads reçus (estim.). Les autres sont hors zone, doublons ou non qualifiés.
- « CA M6 » dans le CSV = **CA mensuel** visé au 6e mois.

### Grille de score (/50)

Cinq critères notés sur 10 : demande prouvée, faiblesse de la concurrence locale, sécurité légale, rapidité et faible coût du test, valeur du lead pour l'acheteur.

---

## Idées validées

### L01 · Dépigeonnage de balcons et de façades (pics, filets)
- Modèle · Payeur · Prix : lead partagé à 1 ou 2 poseurs anti-volatiles ; payé par l'entreprise de dépigeonnage ; 25 à 35 € HT le lead (estim.).
- Zone prioritaire : petite couronne parisienne (92, 94, 93) plutôt que Paris intra-muros. C'est la plus forte densité de balcons et de copropriétés. Paris intra-muros est déjà travaillé (voir concurrence). Lyon, Marseille et Lille sont à tester ensuite, sans vérification à ce stade.
- Preuve de demande : un balcon standard est affiché de 150 à 350 €, une façade de 800 à 2 500 € [allonuisibleexpress.fr](https://allonuisibleexpress.fr/services/depigeonnage/). Un balcon particulier à Courbevoie : 650 € TTC [pigeon-and-co.fr](https://pigeon-and-co.fr/prix/).
- Concurrence vérifiée : requête « dépigeonnage devis Paris particulier prix ». Ressortent un site générateur de leads déjà positionné (sos-nettoyage-extreme.fr, demande « transmise à un professionnel référencé »), des entreprises IDF (Défi Clean, B-Dératisation, Allo Nuisible Express, Alpitec) et des pages ville d'un réseau (nuisibles-service-idf.fr). Verdict : **jouable hors Paris intra-muros**, par ville de petite couronne. Pas de géant national.
- Légal : le pigeon biset n'est pas protégé, seules les méthodes non létales sont posées. Le devis est obligatoire en dératisation et désinsectisation (arrêté du 24/01/2017). Il faut l'accord du syndic pour poser un filet en copropriété.
- Coût d'entrée : 175 € (domaine 10, Ads 150, numéro virtuel 15).
- Mini business plan : M1 300 visites (Ads), 15 leads, 9 vendus × 30 € = 270 €. M3 SEO sur 12 villes, 400 visites, 25 leads, 300 €/mois. M6 800 visites, 50 leads, 30 vendus = 900 €/mois. M12 1 500 visites, 90 leads, 1 600 €/mois (estim.).
- Premier test 7 jours + seuil kill : 1 page 92 et 1 page 94, 150 € d'Ads, 2 poseurs prévenus. Kill si moins de 8 leads ou si aucun acheteur n'accepte 25 €.
- Score /50 : 36.

### L02 · Taupier (piégeage mécanique des taupes)
- Modèle · Payeur · Prix : lead exclusif par canton à un taupier ; payé par le taupier ; 20 à 30 € (estim.). Variante : abonnement mensuel de zone de 50 à 100 € (estim.).
- Zone prioritaire : Seine-Maritime, Eure, Calvados, Manche, Bretagne. Ce sont des sols riches et humides, avec beaucoup de pelouses et de maisons individuelles. Les acteurs sont des artisans isolés aux sites faibles.
- Preuve de demande : forfait trimestriel à partir de 240 € TTC [normandie-taupes.fr](http://normandie-taupes.fr/tarifs/) ; à partir de 210 € avec garantie 3 mois [antifrelons76.fr](https://www.antifrelons76.fr/services/piegeage-taupes) ; Yoojo affiche environ 41 € l'intervention simple [yoojo.fr](https://yoojo.fr/jardinage/guides/taupier-tarif-534).
- Concurrence vérifiée : requêtes « taupier devis Calvados prix » et « taupier professionnel tarif Normandie ». Ressortent des sites d'artisans d'une page (Normandie Taupes, Destruct'Insectes, taupier.info), un guide Yoojo, et des fiches Maps avec peu d'avis. Aucun annuaire fort. Verdict : **ouvert**.
- Légal : le piégeage mécanique est libre chez soi. Les appâts et produits sont réglementés (Certibiocide pour un usage professionnel). Rien de bloquant.
- Coût d'entrée : 160 € (domaine 10, Ads 130, outils 20).
- Mini business plan : M1 200 visites, 12 leads, 8 × 25 € = 200 €. M3 300 €/mois. M6 15 cantons, 40 leads vendus = 1 000 €/mois. M12 1 400 €/mois (estim.). Saisonnalité : automne et printemps forts, été faible.
- Premier test 7 jours + seuil kill : 3 pages (Rouen, Caen, Évreux), 130 € d'Ads. Kill si moins de 6 leads ou si moins de 2 taupiers acceptent de payer.
- Score /50 : 37.

### L03 · Chenilles processionnaires (échenillage, écopièges, Btk)
- Modèle · Payeur · Prix : lead partagé (2 acheteurs) ; payé par l'élagueur ou le désinsectiseur ; 20 à 30 € (estim.).
- Zone prioritaire : Gironde, Landes, Var, Bouches-du-Rhône, Vaucluse, Hérault, Haute-Garonne (forte présence de pins), puis Île-de-France pour le chêne. **Le calendrier tombe bien** : d'octobre à décembre, traitement préventif Btk et nids visibles en hiver.
- Preuve de demande : échenillage à 90 € + 10 €/nid [anti-chenilles.fr](https://www.anti-chenilles.fr/traitement-et-tarifs/echenillage/) ; de 89 à 199 € le nid en IDF [allonuisibleexpress.fr](https://allonuisibleexpress.fr/prix-intervention-nuisibles/chenilles-processionnaires/) ; écopiège à partir de 120 € [provence-chenilles-processionnaires.fr](https://www.provence-chenilles-processionnaires.fr/tarifs-chenilles-processionnaires).
- Concurrence vérifiée : requêtes « chenilles processionnaires traitement devis Gironde particulier » et « enlèvement nid chenilles prix particulier ». Ressortent des artisans régionaux (Provence, Lyon, Bouches-du-Rhône, 31, 87), des PDF de mairies et de FDGDON, et Rentokil. Aucun agrégateur local en Gironde. Verdict : **ouvert dans le Sud-Ouest**.
- Légal : des arrêtés municipaux ou préfectoraux peuvent imposer la lutte, ce qui crée la demande. Les traitements biocides relèvent de professionnels Certibiocide. Les campagnes collectives gratuites de certaines communes sont un substitut possible, à vérifier commune par commune.
- Coût d'entrée : 165 € (domaine 10, Ads 140, outils 15).
- Mini business plan : M1 250 visites, 15 leads, 10 × 25 € = 250 €. M3 (janvier, pic des nids) 500 €/mois. M6 (avril, fin de procession) 350 €/mois. M12 600 €/mois de moyenne lissée (estim.).
- Premier test 7 jours + seuil kill : pages Bordeaux Métropole et bassin d'Arcachon, 140 € d'Ads. Kill si moins de 8 leads.
- Score /50 : 35.

### L04 · Contrat d'entretien de micro-station d'épuration
- Modèle · Payeur · Prix : lead « contrat annuel » vendu à un mainteneur ANC indépendant ; 30 à 50 € (estim.), justifié par un contrat récurrent de 120 à 280 €/an.
- Zone prioritaire : Vendée, Charente, Charente-Maritime, Maine-et-Loire, Bretagne rurale. Forte part d'ANC et de micro-stations récentes. Éviter les Vosges : le SDANC 88 y propose un entretien public à partir de 90 € HT.
- Preuve de demande : de 150 à 370 € par an selon la région [vidangeur-agree.fr](https://vidangeur-agree.fr/blog/microstation-entretien-annuel/) ; contrats de 120 à 363 € TTC/an [ec-environnement.fr (PDF)](https://ec-environnement.fr/wp-content/uploads/2023/10/contrat-de-service-microstation-tricel-novo-ec-environnement-moutiers-2023.pdf) ; de 120 à 250 €/an en Charente [vinsonneau.com](https://vinsonneau.com/blog/entretien-micro-station-epuration-charente-guide).
- Concurrence vérifiée : requêtes « entretien micro-station devis Vendée prix contrat » et « contrat entretien micro-station prix annuel SPANC ». Ressortent des forums (forumconstruire), un annuaire générique (obat), des PDF BOAMP sans rapport, des réseaux de fabricants (Tricel) et un SAV national (sav-micro-station.fr). En Vendée, aucun acteur local ne domine. Verdict : **ouvert**. À distinguer de la vidange, déjà au catalogue : ici l'acheteur est le mainteneur et la valeur vient du contrat.
- Légal : l'obligation de résultat et l'entretien selon le guide du fabricant découlent de l'arrêté du 07/09/2009 modifié. Certains fabricants exigent leur réseau pour maintenir la garantie : à afficher.
- Coût d'entrée : 170 € (domaine 10, Ads 140, outils 20).
- Mini business plan : M1 150 visites, 8 leads, 5 × 40 € = 200 €. M3 400 €/mois. M6 20 leads vendus = 800 €/mois. M12 1 200 €/mois (estim.).
- Premier test 7 jours + seuil kill : pages Vendée et Charente, 140 € d'Ads. Kill si moins de 5 leads ou si aucun mainteneur ne paie 30 €.
- Score /50 : 36.

### L05 · Traitement de la mérule (diagnostic + devis)
- Modèle · Payeur · Prix : lead exclusif à une entreprise CTB-A+ ; 80 à 150 € (estim.). Les chantiers vont de 3 500 à plus de 20 000 €.
- Zone prioritaire : Finistère, Morbihan, Côtes-d'Armor (arrêté mérule en Finistère, bâti ancien en pierre, climat humide). Ensuite Hauts-de-France (Nord, Pas-de-Calais). **Attention** : l'article 3 de l'arrêté du Finistère du 15/07/2020 a été annulé par le TA de Rennes, et un nouveau projet était en cours en 2023. La version en vigueur n'a pas été vérifiée [délibération Quimper (PDF)](https://archives.quimper.bzh/medias/customer_2/Actes/VQ/Deliberations/2023_12_07/D%C3%A9lib%C3%A9ration%20n%C2%B047%20(07.12.2023).pdf).
- Preuve de demande : de 3 500 à 6 000 € pour un traitement localisé, de 80 à 200 €/m² [tytek.fr](https://tytek.fr/traitement-merule/morbihan/) ; charpente de 4 000 à 20 000 € [qualite.bzh](https://www.qualite.bzh/merule/morbihan/).
- Concurrence vérifiée : requête « traitement mérule devis Finistère Morbihan ». Ressortent 4 ou 5 spécialistes régionaux (TDO, BZH Qualité, Tytek, BTR29), et aucun agrégateur. Verdict : **concurrence d'entreprises, pas de générateur de leads** ; la vente de leads à des entreprises plus petites ou hors zone reste jouable.
- Légal : le notaire doit informer l'acquéreur en zone d'arrêté (loi ALUR). Le diagnostic n'est pas réglementé, mais le traitement exige des biocides professionnels. Pas d'obstacle.
- Coût d'entrée : 180 € (domaine 10, Ads 150, outils 20).
- Mini business plan : M1 150 visites, 4 leads, 3 × 100 € = 300 €. M3 600 €/mois. M6 10 leads vendus = 1 000 €/mois. M12 1 500 €/mois (estim.).
- Premier test 7 jours + seuil kill : pages Brest, Quimper et Lorient, 150 € d'Ads, CPC probablement élevé. Kill si moins de 3 leads, ou si aucun acheteur n'accepte au moins 60 €.
- Score /50 : 35.

### L06 · Traitement anti-termites (curatif, appâts, barrière)
- Modèle · Payeur · Prix : lead exclusif ; 50 à 90 € (estim.).
- Zone prioritaire : Gironde, Landes, Charente-Maritime, Lot-et-Garonne, qui figurent parmi les départements fortement infestés [french-property.com](https://french-property.com/news/french_property/termites_map_of_france).
- Preuve de demande : devis de 2 450 € rapporté pour une injection en rez-de-chaussée lors d'une vente [forumconstruire](https://www.forumconstruire.com/construire/topic-211723.php). Déclaration en mairie obligatoire en cas de découverte (même source).
- Concurrence vérifiée : requêtes « traitement termites devis Landes particulier prix » et « traitement anti-termites devis Gironde Landes ». Ressortent un réseau fort (France Termites Capricornes, 3 500 chantiers par an selon son site), une dizaine d'artisans girondins bien notés sur Maps, et travaux.com avec des pages communes vides. Verdict : **concurrencé**, jouable par commune fine (bassin d'Arcachon, Médoc, Libournais), score réduit.
- Légal : arrêtés préfectoraux de zones termites ; état parasitaire obligatoire à la vente dans ces zones. Le traitement exige des biocides professionnels. Pas d'obstacle pour un intermédiaire.
- Coût d'entrée : 180 € (domaine 10, Ads 150, outils 20).
- Mini business plan : M1 4 leads × 70 € = 280 €. M3 500 €/mois. M6 12 leads = 840 €/mois. M12 1 200 €/mois (estim.).
- Premier test 7 jours + seuil kill : pages par commune du bassin d'Arcachon et du Médoc. Kill si moins de 4 leads.
- Score /50 : 31.

### L07 · Étude de sol G1 obligatoire pour vendre un terrain en zone argileuse
- Modèle · Payeur · Prix : lead vendeur de terrain vendu à un bureau d'études géotechniques ; 50 à 80 € (estim.) pour une mission de 700 à 1 500 €.
- Zone prioritaire : départements à aléa retrait-gonflement moyen ou fort, et à forte activité de terrains à bâtir : Haute-Garonne, Tarn-et-Garonne, Gers, Gironde, Indre-et-Loire, Seine-et-Marne. La nouvelle carte du 01/07/2026 classe 55 % du territoire en exposition moyenne ou forte, contre 48 % auparavant [geo2mo.com](https://geo2mo.com/etude-de-sol/g1).
- Preuve de demande : obligation pour le vendeur (art. L132-5 du CCH, loi ELAN), coût moyen de 1 010 € TTC selon la FFB [expertgeotechnique.com](https://www.expertgeotechnique.com/missions-geotechnique/g1/etude-sol-pour-vendre-terrain/) ; obligation rappelée par le [ministère (PDF)](https://www.ecologie.gouv.fr/sites/default/files/documents/construire_en_terrain_argileux_reglementation_et_bonnes_pratiques.pdf).
- Concurrence vérifiée : requête « étude géotechnique G1 vente terrain obligatoire devis prix ». Ressortent des sites nationaux de bureaux d'études et de générateurs de leads (geo2mo, geo-study, expertgeotechnique), l'INC et le ministère. Il existe peu de pages par département. Verdict : **nationalement occupé, localement faible**. Angle : une page par département et par commune, avec la carte Géorisques intégrée.
- Légal : aucune activité réglementée côté intermédiaire. Le bureau d'études doit être assuré ; afficher son nom.
- Coût d'entrée : 175 € (domaine 10, Ads 150, outils 15).
- Mini business plan : M1 3 leads × 60 € = 180 €. M3 480 €/mois. M6 15 leads = 900 €/mois. M12 1 300 €/mois (estim.).
- Premier test 7 jours + seuil kill : 2 départements (31, 33), Ads sur « étude de sol vente terrain + département ». Kill si moins de 3 leads.
- Score /50 : 36.

### L08 · Expertise fissures après sécheresse (expert bâtiment indépendant)
- Modèle · Payeur · Prix : lead exclusif vendu à un expert bâtiment local ; 50 à 80 € (estim.) pour une mission de 500 à 2 000 €.
- Zone prioritaire : communes ayant un arrêté CatNat sécheresse récent (base GASPAR), dans le Gers, le Tarn-et-Garonne, l'Indre, le Cher, le Lot-et-Garonne et la Haute-Garonne. Le délai de 30 jours après publication de l'arrêté crée une urgence datée.
- Preuve de demande : de 800 à 2 000 € TTC chez les cabinets traditionnels [expertgo.fr](https://www.expertgo.fr/prix-expertise-fissures) ; de 700 à 1 500 € pour une expertise complète [novagrund.fr](https://www.novagrund.fr/expertise-fissure-maison) ; franchise légale sécheresse de 1 520 € [global-expertises.fr](https://global-expertises.fr/expertise-fissures).
- Concurrence vérifiée : requête « expert fissures maison sécheresse catastrophe naturelle expertise particulier prix ». Ressortent des plateformes nationales (ExpertGo à 590 €, Novagrund, Global Expertises en télérelevé à 490 €). Verdict : **concurrence nationale réelle**. Angle local : une page par commune avec l'arrêté CatNat, le délai et la liste d'experts du département.
- Légal : « expert bâtiment » n'est pas un titre réglementé. Ne pas se présenter comme expert judiciaire.
- Coût d'entrée : 175 €.
- Mini business plan : M1 4 leads × 60 € = 240 €. M3 450 €/mois. M6 (après une vague d'arrêtés) 12 leads = 720 €/mois. M12 900 €/mois, irrégulier (estim.).
- Premier test 7 jours + seuil kill : 10 communes ayant un arrêté de 2026, Ads ciblées. Kill si moins de 3 leads.
- Score /50 : 31.

### L09 · Reprise en sous-œuvre (micropieux, résine) des maisons fissurées
- Modèle · Payeur · Prix : lead exclusif qualifié, avec une G5 ou une expertise en main ; 100 à 200 € (estim.) pour des chantiers de 10 000 à 40 000 €.
- Zone prioritaire : mêmes zones RGA que L08 (Occitanie, Centre-Val de Loire, Nouvelle-Aquitaine). Synergie : les leads L08 et L07 alimentent L09.
- Preuve de demande : la plupart des chantiers vont de 10 000 à 40 000 € [expertgeotechnique.com](https://www.expertgeotechnique.com/renforcement-sol/reprise-sous-oeuvre/) ; de 15 000 à 30 000 € en moyenne pour la résine [solprobtp.fr](https://www.solprobtp.fr/resine-expansive/garanties-normes/) ; une entreprise des Landes et du Pays basque produit du contenu sur le sujet [adlconstructions.fr](https://www.adlconstructions.fr/guides/prix-reprise-en-sous-oeuvre/).
- Concurrence vérifiée : requête « injection résine fissures sécheresse prix reprise en sous-œuvre devis ». Ressortent des guides nationaux (travaux.com, expertgeotechnique) et des applicateurs (Solpro, ADL). Pas de page locale forte relevée. Verdict : **ouvert localement**, avec un ticket très élevé.
- Légal : la pression commerciale sur des sinistrés est un risque. Afficher l'indépendance, recommander une G5 avant devis, aucun démarchage.
- Coût d'entrée : 180 €.
- Mini business plan : M1 2 leads × 150 € = 300 €. M3 600 €/mois. M6 8 leads = 1 200 €/mois. M12 1 800 €/mois (estim.).
- Premier test 7 jours + seuil kill : Ads « micropieux / résine + département ». Kill si moins de 2 leads, ou si aucun applicateur n'accepte au moins 100 €.
- Score /50 : 36.

### L10 · Dégazage et neutralisation de cuve à fioul (avant vente ou à l'abandon)
- Modèle · Payeur · Prix : lead exclusif vendu à un dégazeur ou à une entreprise de vidange ; 40 à 70 € (estim.) pour des chantiers de 500 à 3 000 €.
- Zone prioritaire : départements à fort parc fioul et rural (Grand Est, Bourgogne-Franche-Comté, Normandie, Bretagne, Hauts-de-France). Ces zones n'ont pas été vérifiées une par une.
- Preuve de demande : neutralisation obligatoire à l'abandon (art. 28 de l'arrêté du 01/07/2004) ; le notaire exige le certificat ; de 1 500 à 3 000 € pour un dégazage avec comblement [pap.fr](https://www.pap.fr/vendeur/diagnostics-immobiliers/attention-vous-devez-enlever-ou-neutraliser-votre-cuve-a-fioul-avant-de-vendre/a25615) ; de 500 à 1 000 € pour la neutralisation seule [veolia.fr](https://assainissement-et-maintenance.veolia.fr/conseils/combien-coute-la-neutralisation-d-une-cuve-a-fioul).
- Concurrence vérifiée : requête « neutralisation cuve fioul enterrée dégazage prix particulier obligation ». Ressortent GRDF, PAP, la CAPEB, Veolia et une entreprise du 49 (AMA). Il existe peu de pages locales de devis. Verdict : **ouvert, mais Veolia est présent nationalement**.
- Légal : **à positionner « avant vente / abandon », pas « changement de chauffage »**. La prime MaPrimeRénov' dépose de cuve relève de la rénovation énergétique, exclue. Ne pas l'utiliser comme argument et ne faire aucun démarchage.
- Coût d'entrée : 170 €.
- Mini business plan : M1 3 leads × 50 € = 150 €. M3 400 €/mois. M6 12 leads = 600 €/mois. M12 900 €/mois (estim.).
- Premier test 7 jours + seuil kill : 2 départements, Ads « dégazage cuve fioul + ville ». Kill si moins de 3 leads.
- Score /50 : 33.

### L11 · Travaux de mise en conformité du branchement d'assainissement (après contrôle à la vente)
- Modèle · Payeur · Prix : lead vendu à un plombier-terrassier ou à un spécialiste caméra et chemisage ; 40 à 60 € (estim.).
- Zone prioritaire : **Montpellier Méditerranée Métropole**, où le contrôle de conformité est obligatoire à la vente depuis le 01/01/2026, avec 2 ans pour la mise en conformité [Régie des eaux 3M (PDF)](https://regiedeseaux.montpellier3m.fr/medias/pdf/reglement-service-assainissement-2025.pdf) ; les territoires d'Île-de-France visés par service-public ; Aubenas ; le Pays des Écrins.
- Preuve de demande : en IDF, travaux obligatoires sous 2 ans après une non-conformité [service-public.gouv.fr F31685](https://www.service-public.gouv.fr/particuliers/vosdroits/F31685) ; FAQ de la régie de Montpellier [regiedeseaux3m.fr](https://conformite-assainissement-individuel.regiedeseaux3m.fr/faq).
- Concurrence vérifiée : requête « mise en conformité branchement assainissement travaux après contrôle non conforme devis Montpellier ». Ressortent deux entreprises locales (Ets Farah, Chemisage Évacuation), un site générique ANC et le règlement. Verdict : **ouvert et récent**, c'est l'obligation de 2026 qui crée la demande.
- Légal : **le contrôle est réalisé par le service public**. On ne vend que les travaux. Ne pas imiter la Régie : nom, visuels et ton clairement privés.
- Coût d'entrée : 165 €.
- Mini business plan : M1 4 leads × 50 € = 200 €. M3 500 €/mois. M6 15 leads = 750 €/mois. M12 1 000 €/mois (estim.).
- Premier test 7 jours + seuil kill : 5 pages de communes de la métropole, 140 € d'Ads « non conforme assainissement vente Montpellier ». Kill si moins de 4 leads.
- Score /50 : 38.

### L12 · Raccordement obligatoire au tout-à-l'égout (nouveaux réseaux, délai de 2 ans)
- Modèle · Payeur · Prix : lead vendu à un terrassier ou plombier ; 40 à 60 € (estim.) pour une partie privative de 2 000 à 6 000 €. Option : mise hors service de l'ancienne fosse (art. L1331-5 du CSP).
- Zone prioritaire : les communes où un réseau neuf a été mis en service depuis moins de 2 ans. Liste à construire depuis les avis de travaux BOAMP et les bulletins municipaux (sourcing manuel, non fait ici).
- Preuve de demande : raccordement obligatoire sous 2 ans à compter de la mise en service, partie privée à la charge du propriétaire [service-public.gouv.fr F447](https://www.service-public.gouv.fr/particuliers/vosdroits/F447) ; de 2 000 à 6 000 € pour un raccordement standard [travaux.com](https://www.travaux.com/construction-renovation-maison/articles/viabiliser-un-terrain-guide-des-demarches-a-realiser).
- Concurrence vérifiée : requête « raccordement tout-à-l'égout obligatoire délai 2 ans nouveau réseau prix ». Ressortent service-public, des pages de collectivités (Grand Albigeois) et des PDF. Aucun site de devis par commune relevé. Verdict : **ouvert**, mais le volume par commune est petit.
- Légal : pas d'obstacle. La collectivité réalise parfois la partie publique : le préciser.
- Coût d'entrée : 160 €.
- Mini business plan : M1 2 leads × 50 € = 100 €. M3 300 €/mois. M6 10 leads = 500 €/mois. M12 700 €/mois (estim.).
- Premier test 7 jours + seuil kill : 3 communes à réseau neuf identifiées, pages et Ads locales. Kill si moins de 2 leads.
- Score /50 : 32.

### L13 · Fouine, martre et loir dans les combles (éviction et colmatage)
- Modèle · Payeur · Prix : lead partagé ; 25 à 35 € (estim.) pour une intervention de 120 à 450 €.
- Zone prioritaire : Bas-Rhin, Haut-Rhin, Moselle, Vosges, Doubs (bâti ancien, forêts). La saison est bonne : automne et hiver, quand les animaux sont dans les combles.
- Preuve de demande : éviction à partir de 119 € TTC [est-nuisibles.fr](https://est-nuisibles.fr/deratisation/fouines/) ; fouine à 160 € [alsace-nuisibles.fr](https://alsace-nuisibles.fr/tarification/) ; de 150 à 450 € selon l'ancienneté [solution-nuisible.fr](https://solution-nuisible.fr/entreprise-deratisation-fouine-traitement/).
- Concurrence vérifiée : requête « fouine dans les combles intervention professionnel prix Alsace Lorraine ». Ressortent 4 entreprises alsaciennes et un réseau national de mise en relation (solution-nuisible.fr). Verdict : **moyen**. Le réseau national prouve que des acheteurs paient. La Lorraine est moins couverte que l'Alsace.
- Légal : la fouine peut être classée ESOD selon le département et le piégeage est réservé aux piégeurs agréés. Le loir et le lérot doivent être vérifiés espèce par espèce. Afficher les méthodes autorisées.
- Coût d'entrée : 165 €.
- Mini business plan : M1 10 leads, 7 × 30 € = 210 €. M3 400 €/mois. M6 25 leads = 750 €/mois. M12 900 €/mois (estim.).
- Premier test 7 jours + seuil kill : pages Metz, Nancy et Épinal, 140 € d'Ads. Kill si moins de 6 leads.
- Score /50 : 33.

### L14 · Démoustication du jardin (moustique tigre)
- Modèle · Payeur · Prix : lead partagé ; 25 à 35 € (estim.) pour une intervention de 150 à 450 €, ou un contrat de saison de 480 à 950 €.
- Zone prioritaire : Bouches-du-Rhône, Var, Hérault, Gard, Rhône, Gironde, Haute-Garonne. **La saison va d'avril à octobre** : on construit le SEO maintenant et on lance les Ads en avril 2027.
- Preuve de demande : de 180 à 280 € pour un jardin standard [sanalia.fr](https://www.sanalia.fr/desinsectisation/moustiques/) ; contrat annuel de 480 à 950 € [invazio.fr](https://invazio.fr/actu/2026-08-08-geo-prix-demoustication-moustique-tigre-france-2026-tarifs-pro/) ; Lyon à partir de 199 € [nuisiguard.com](https://www.nuisiguard.com/services/moustiques/lyon).
- Concurrence vérifiée : requête « traitement moustique tigre jardin particulier entreprise prix ». Ressortent des entreprises nationales ou régionales (Sanalia, Genostique, Nuisi'Guard), un réseau (solution-nuisible) et un média (Invazio). Verdict : **moyen**. Les pages par commune du Var et de l'Hérault sont peu travaillées (constat sur un échantillon).
- Légal : biocides adulticides réservés aux professionnels Certibiocide. Mentionner le Bti et la prévention des gîtes. L'ARS mène des actions publiques autour des cas de dengue, ce qui n'en fait pas un substitut pour le confort du jardin.
- Coût d'entrée : 160 €.
- Mini business plan : M1 (octobre) 0 € (SEO). M3 0 €. M6 (avril) 20 leads × 30 € = 600 €. M12 (octobre 2027) 500 €/mois de moyenne de saison (estim.).
- Premier test 7 jours + seuil kill : en avril 2027, 3 villes du Var, 140 € d'Ads. Kill si moins de 8 leads. Aujourd'hui, test sans coût : indexation des pages uniquement.
- Score /50 : 30.

### L15 · Pergola et carport aluminium (devis local)
- Modèle · Payeur · Prix : lead exclusif vendu à un installateur indépendant ; 50 à 80 € (estim.) pour des tickets de 1 200 à 12 000 €.
- Zone prioritaire : Hérault et Gard (2 700 h de soleil, besoin d'ombre) ; Gironde pour le carport.
- Preuve de demande : de 2 000 à 6 000 € pour une pergola simple, jusqu'à 12 000 € [e-local.fr](https://e-local.fr/34/montpellier/pergola/) ; carport à partir de 1 200 € [e-local.fr Bordeaux](https://e-local.fr/33/bordeaux/carport/) ; Clôture Arès affiche une pergola bioclimatique à partir de 2 777 € HT [cloture-ares.fr](https://www.cloture-ares.fr/agences/montpellier-nimes/pergola-aluminium/).
- Concurrence vérifiée : requêtes « pergola bioclimatique devis Montpellier installateur prix » et « carport aluminium pose devis Bordeaux ». Ressortent 2 générateurs de leads (e-local, multi-métiers et générique ; pergolaverandafrance.fr), des franchises (Akena), des installateurs locaux et Les Menuisiers de France. Verdict : **concurrencé**. Jouable avec un estimateur réellement utile (règles PLU, ABF de l'Écusson, vent). Score réduit.
- Légal : déclaration préalable ou permis selon la surface ; secteur ABF. Les ventes d'aménagements extérieurs connaissent un démarchage agressif : rester sur l'entrant.
- Coût d'entrée : 180 €.
- Mini business plan : M1 (basse saison) 2 leads × 60 € = 120 €. M3 300 €/mois. M6 (avril) 15 leads = 900 €/mois. M12 600 €/mois (estim.).
- Premier test 7 jours + seuil kill : estimateur pergola sur l'Hérault, 150 € d'Ads. Kill si CPL > 40 € et aucun acheteur à 50 €.
- Score /50 : 28.

### L16 · Nettoyage après décès et syndrome de Diogène
- Modèle · Payeur · Prix : lead exclusif vendu à une entreprise de nettoyage extrême Certibiocide ; 60 à 100 € (estim.) pour des chantiers de 500 à 8 000 €.
- Zone prioritaire : métropoles (Marseille, Lyon, Toulouse, Lille, Nice). Grande densité de logements et de bailleurs.
- Preuve de demande : de 500 à 8 000 € selon l'état [coupdepropre.fr](https://www.coupdepropre.fr/nettoyage-apres-syndrome-de-diogene-marseille-insalubrite-desinfection-decontamination.asp) ; l'offre locale cible CCAS, mandataires et notaires [massiv-clean-nettoyage.fr](https://massiv-clean-nettoyage.fr/).
- Concurrence vérifiée : requête « nettoyage après décès logement syndrome de Diogène entreprise devis Marseille ». Ressortent 4 entreprises locales (Diogène Service, Massiv'Clean, Coup de Propre), des fiches Maps et un réseau national (nettoyage-apres-deces-france.com). Verdict : **moyen**. Distinct du débarras (au catalogue) : le métier est la désinfection et le biorisque.
- Légal : sujet sensible. Ton sobre, aucun ciblage d'une personne, aucun achat de données de décès, aucune sollicitation de familles.
- Coût d'entrée : 175 €.
- Mini business plan : M1 3 leads × 80 € = 240 €. M3 500 €/mois. M6 10 leads = 800 €/mois. M12 1 000 €/mois (estim.).
- Premier test 7 jours + seuil kill : Lyon et Toulouse (Marseille est plus servi), 150 € d'Ads. Kill si moins de 3 leads.
- Score /50 : 32.

### L17 · Forage et puits domestique (création, rebouchage des forages abandonnés)
- Modèle · Payeur · Prix : lead exclusif vendu à un foreur ; 50 à 80 € (estim.) pour des chantiers de 1 500 à 4 500 € (de 90 à 150 €/m).
- Zone prioritaire : Gironde (bassin d'Arcachon, Médoc), Landes, Charente-Maritime (sols sableux, arrosage). Le pic va du printemps à l'été : à préparer dès maintenant.
- Preuve de demande : de 90 à 150 € le mètre foré [sourcier-gironde.fr](https://www.sourcier-gironde.fr/) et [sourciergironde.fr](https://www.sourciergironde.fr/arnaque-forage) ; déclaration DUPLOS obligatoire [service-public F172](https://www.service-public.gouv.fr/particuliers/vosdroits/F172).
- Concurrence vérifiée : requête « forage puits domestique particulier prix devis foreur Gironde ». Ressortent service-public, la préfecture, un sourcier bénévole, et une page qui dénonce des foreurs malhonnêtes. Aucun site de devis structuré. Verdict : **ouvert**, mais le **risque réputationnel** vient des foreurs low-cost : sélectionner des acheteurs qui respectent la DUPLOS et le PVC alimentaire.
- Légal : déclaration au moins 1 mois avant les travaux ; analyse de l'eau si elle sert à la consommation humaine. Les restrictions sécheresse peuvent viser les prélèvements : à afficher.
- Coût d'entrée : 165 €.
- Mini business plan : M1 2 leads × 60 € = 120 €. M3 240 €/mois. M6 (avril) 12 leads = 720 €/mois. M12 500 €/mois (estim.).
- Premier test 7 jours + seuil kill : pages Arcachon et Médoc avec un guide DUPLOS. Kill si moins de 2 leads.
- Score /50 : 32.

### L18 · Étude de sol et de filière ANC (construction neuve ou réhabilitation)
- Modèle · Payeur · Prix : lead vendu à un bureau d'études ANC indépendant ; 40 à 60 € (estim.) pour une étude de 400 à 1 000 €.
- Zone prioritaire : Gard (Alès Agglo l'exige), Drôme et Ardèche (Valence Romans Agglo l'exige avant permis), Bretagne, Dordogne.
- Preuve de demande : étude obligatoire avant l'avis SPANC et le permis [Valence Romans Agglo](https://www.valenceromansagglo.fr/pratique/eaux/assainissement/assainissement-non-collectif/) ; « étude de définition de filière » exigée [SPANC Alès (PDF)](https://www.ales.fr/wp-content/uploads/2023/07/SPANC-mode-emploi-2023.pdf) ; de 400 à 1 000 € [expertgeotechnique.com](https://www.expertgeotechnique.com/prix-etude-sol/prix-etude-assainissement/).
- Concurrence vérifiée : requête « étude de sol filière assainissement non collectif prix bureau d'études ». Ressortent des pages de SPANC, un fabricant (Tricel) et un guide national. Aucun site local de devis. Verdict : **ouvert**. Le SPANC refuse une étude faite par l'installateur, ce qui crée la demande d'un bureau indépendant.
- Légal : pas d'obstacle. Ne pas se présenter comme le SPANC.
- Coût d'entrée : 160 €.
- Mini business plan : M1 3 leads × 50 € = 150 €. M3 350 €/mois. M6 12 leads = 600 €/mois. M12 800 €/mois (estim.).
- Premier test 7 jours + seuil kill : pages Gard et Drôme, 130 € d'Ads. Kill si moins de 3 leads.
- Score /50 : 35.

### L19 · Traitement préventif du charançon rouge du palmier (lutte obligatoire)
- Modèle · Payeur · Prix : lead vendu à un applicateur agréé ; 15 à 25 € (estim.). Le ticket est bas (environ 80 €/palmier/an), mais **récurrent chaque année** ; variante : commission sur le contrat.
- Zone prioritaire : les communes de l'annexe 2 de l'arrêté Occitanie (Agde, Sète, Lattes, Pérols, Castelnau-le-Lez, Perpignan, Saint-Cyprien, Le Grau-du-Roi…) [DRAAF Occitanie (PDF)](https://draaf.occitanie.agriculture.gouv.fr/IMG/pdf/2025_ap_crp_sral_vd.pdf), puis le Var et les Alpes-Maritimes (arrêté PACA du 13/01/2026) [DRAAF PACA](https://draaf.paca.agriculture.gouv.fr/arrete-prefectoral-du-13-janvier-2026-relatif-a-la-lutte-contre-rhynchophorus-a4687.html).
- Preuve de demande : traitement annuel par injection obligatoire dans ces communes ; prix négocié de 80,40 €/palmier/an par Estérel Côte d'Azur Agglomération, avec 5 500 palmiers suivis [esterelcotedazur-agglo.fr](https://esterelcotedazur-agglo.fr/environnement/lutter_contre_les_nuisibles/sauver-les-palmier-du-charancon-rouge-plan-arecap/).
- Concurrence vérifiée : requête « charançon rouge du palmier traitement obligatoire particulier prix injection Var Hérault ». Ressortent la DRAAF, l'ANSES et l'agglo. Aucune page de devis privée relevée. Verdict : **ouvert hors du territoire d'Estérel**, où le plan public fixe déjà le prix (substitut).
- Légal : traitement réservé à des applicateurs agréés (produits phytopharmaceutiques) ; déclaration du bilan annuel à la DRAAF par l'applicateur. Arrêté Occitanie valable jusqu'au 01/11/2027 : **risque de fin d'obligation**.
- Coût d'entrée : 150 € (domaine 10, Ads 120, outils 20).
- Mini business plan : M1 10 leads × 20 € = 200 €. M3 300 €/mois. M6 (printemps) 30 leads = 600 €/mois. M12 400 €/mois (estim.).
- Premier test 7 jours + seuil kill : 5 communes de l'Hérault, 120 € d'Ads. Kill si moins de 6 leads ou si aucun applicateur n'est trouvé.
- Score /50 : 33.

### L20 · Expert d'assuré (contre-expertise après incendie, dégât des eaux, CatNat)
- Modèle · Payeur · Prix : apport d'affaires à un cabinet d'expertise d'assuré ; 100 à 200 € par mandat signé, ou 10 % des honoraires (estim.). Les honoraires vont de 5 à 10 % de l'indemnité.
- Zone prioritaire : les départements touchés par un événement récent (inondations, grêle, sécheresse) et les métropoles pour les incendies. La zone est dynamique, à suivre via les arrêtés CatNat.
- Preuve de demande : barème indicatif de 9 % jusqu'à 25 000 € [expertdassure.com](https://expertdassure.com/tarifs-expert-habitation-dommages-logement.html) ; cabinet facturant 5 % HT au résultat [dr-experts.fr](https://dr-experts.fr/faq) ; une contre-expertise coûte au moins 800 € [service-public F3075](https://www.service-public.gouv.fr/particuliers/vosdroits/F3075).
- Concurrence vérifiée : requête « expert d'assuré sinistre incendie dégât des eaux honoraires pourcentage particulier ». Ressortent des cabinets nationaux, un média (France Épargne) et service-public. Pas de page locale forte relevée. Verdict : **moyen**.
- Légal : **ce n'est pas de l'intermédiation en assurance** : on ne vend aucun contrat, donc pas d'ORIAS à ce titre. Le cabinet doit être nommé. Vérifier que la rémunération d'un apporteur est acceptée par le cabinet (déontologie de la profession, non vérifiée).
- Coût d'entrée : 180 €.
- Mini business plan : M1 1 mandat × 150 € = 150 €. M3 450 €/mois. M6 5 mandats = 750 €/mois. M12 1 200 €/mois, irrégulier (estim.).
- Premier test 7 jours + seuil kill : page sur l'événement le plus récent, 150 € d'Ads. Kill si moins de 3 demandes qualifiées (sinistre au-dessus de 10 000 €).
- Score /50 : 30.

### L21 · Assistance à la réception de maison neuve (CCMI, VEFA)
- Modèle · Payeur · Prix : lead vendu à un expert bâtiment local ; 40 à 60 € (estim.) pour une mission de 490 à 1 600 €.
- Zone prioritaire : départements à forte construction de maisons individuelles (Gironde, Haute-Garonne, Loire-Atlantique, Vendée, Hérault) ; non vérifié par des données.
- Preuve de demande : de 400 à 1 600 € TTC [expertgo.fr](https://www.expertgo.fr/prix-assistance-reception-chantier) ; réception à partir de 700 € [ccebi.fr](https://ccebi.fr/expert-assistance-reception-maison-ccmi/) ; 720 € jusqu'à 75 m² [checkmy-house.fr](https://checkmy-house.fr/assistance-ccmi/).
- Concurrence vérifiée : requête « assistance réception maison neuve expert CCMI prix ». Ressortent des plateformes nationales (ExpertGo, Check my House) et des cabinets. Verdict : **concurrence nationale**. Jouable par lotissement ou par commune et via les groupes de futurs propriétaires. Score bas.
- Légal : le délai de 8 jours pour émettre des réserves en CCMI crée une urgence. Pas d'obstacle.
- Coût d'entrée : 170 €.
- Mini business plan : M1 2 leads × 50 € = 100 €. M3 300 €/mois. M6 10 leads = 500 €/mois. M12 700 €/mois (estim.).
- Premier test 7 jours + seuil kill : Ads « réception maison neuve + département ». Kill si moins de 3 leads.
- Score /50 : 27.

### L22 · Mur de soutènement (réfection ou reconstruction)
- Modèle · Payeur · Prix : lead exclusif vendu à un maçon ou terrassier ; 50 à 80 € (estim.) pour des chantiers de 3 000 à 12 000 €.
- Zone prioritaire : terrains en pente : Lyon et ses balmes, Alpes-Maritimes et Var (restanques), Ardèche, Pays basque. La Ville de Lyon a un service dédié aux balmes [lyon.fr](https://www.lyon.fr/vie-pratique/logement-et-urbanisme/le-ravalement-de-facade).
- Preuve de demande : de 150 à 600 €/m², de 3 000 à 12 000 € pour 10 m × 2 m [travaux.com](https://www.travaux.com/construction-renovation-maison/guide-des-prix/mur-de-soutenement) ; devis réels de 4 500 à 8 400 € [contactartisan.com](https://devis.contactartisan.com/devis/reconstruction-mur-de-soutenement.html) ; la pathologie est documentée par l'AQC [qualiteconstruction.com](https://qualiteconstruction.com/ressource/fiches-pathologie-batiment/effondrement-murs-soutenement-maconnerie/).
- Concurrence vérifiée : requête « mur de soutènement effondré reconstruction devis prix maçon particulier ». Ressortent des guides nationaux (travaux.com, ClubArtisans, contactartisan) et l'AQC. Pas de page locale par ville relevée. Verdict : **national générique, local ouvert**.
- Légal : la responsabilité du propriétaire et les litiges de voisinage sont fréquents. Un ouvrage de plus de 2 m demande une étude : le mentionner.
- Coût d'entrée : 170 €.
- Mini business plan : M1 3 leads × 60 € = 180 €. M3 400 €/mois. M6 12 leads = 720 €/mois. M12 1 000 €/mois (estim.).
- Premier test 7 jours + seuil kill : Lyon Ouest et Alpes-Maritimes, 150 € d'Ads. Kill si moins de 3 leads.
- Score /50 : 33.

### L23 · Viabilisation de terrain à bâtir (tranchées et raccordements privatifs)
- Modèle · Payeur · Prix : lead vendu à un terrassier VRD ; 50 à 80 € (estim.) pour des chantiers de 5 000 à 15 000 €.
- Zone prioritaire : départements à forte vente de terrains à bâtir (Vendée, Loire-Atlantique, Gironde, Haute-Garonne, Hérault) ; non vérifié par des données.
- Preuve de demande : de 5 000 à 15 000 € en moyenne [afedim.fr](https://www.afedim.fr/fr/actualites-et-conseils/combien-coute-la-viabilisation-d-un-terrain.html) ; détail par réseau [travaux.com](https://www.travaux.com/construction-renovation-maison/guide-des-prix/prix-viabilisation-electrique).
- Concurrence vérifiée : requête « viabilisation terrain à bâtir prix devis terrassier raccordement ». Ressortent des guides nationaux (travaux.com, Afedim, Angelotti). Pas de page locale relevée. Verdict : **local ouvert**.
- Légal : Enedis et le service de l'eau réalisent la partie publique. On ne vend que la partie privée et les tranchées.
- Coût d'entrée : 170 €.
- Mini business plan : M1 2 leads × 60 € = 120 €. M3 360 €/mois. M6 10 leads = 600 €/mois. M12 900 €/mois (estim.). Synergies avec L07, L12, L18 et L27.
- Premier test 7 jours + seuil kill : Vendée et Loire-Atlantique. Kill si moins de 2 leads.
- Score /50 : 32.

### L24 · Drainage périphérique de maison (cave humide, sol argileux)
- Modèle · Payeur · Prix : lead exclusif vendu à un terrassier ; 50 à 80 € (estim.) pour des chantiers de 4 800 à 20 000 €.
- Zone prioritaire : bassins argileux et maisons à sous-sol (Île-de-France Est, Hauts-de-France, Centre). Non vérifié commune par commune.
- Preuve de demande : de 160 à 400 €/ml, de 8 000 à 20 000 € pour 4 côtés [travaux.com](https://www.travaux.com/plomberie/guide-des-prix/prix-de-linstallation-dun-drainage) ; de 220 à 410 €/ml [habitatpresto.com](https://www.habitatpresto.com/mag/isolation/humidite-etancheite/drainage-maison).
- Concurrence vérifiée : requête « drainage périphérique maison humidité cave prix devis terrassier ». Ressortent travaux.com, Habitatpresto, Ootravaux et un spécialiste de l'humidité (Humidians). Verdict : **concurrencé par les plateformes** sur la requête générique, local ouvert. **Le secteur de l'« humidité » est sujet au démarchage** : n'acheter que des terrassiers, jamais des vendeurs de « traitements miracles ».
- Légal : rejet pluvial soumis à autorisation ; ne pas relier au réseau d'eaux usées.
- Coût d'entrée : 175 €.
- Mini business plan : M1 2 leads × 60 € = 120 €. M3 360 €/mois. M6 10 leads = 600 €/mois. M12 800 €/mois (estim.).
- Premier test 7 jours + seuil kill : 2 villes du 77 et du 59. Kill si moins de 3 leads.
- Score /50 : 29.

### L25 · Réduction de la vulnérabilité aux inondations (batardeaux, clapets, zone refuge, subventionnés à 80 %)
- Modèle · Payeur · Prix : lead vendu à un installateur de protections anti-inondation ou à une entreprise générale ; 60 à 100 € (estim.) pour des chantiers de 2 000 à 45 000 €.
- Zone prioritaire : communes sous PPRI prescriptif ou PAPI labellisé : Haute-Garonne (téléprocédure DDT31), Seine-Maritime, Var, Gard, Aude, Pas-de-Calais.
- Preuve de demande : le Fonds Barnier finance 80 % des travaux imposés par un PPRI ou identifiés par un diagnostic PAPI, jusqu'à 36 000 € par bien [ecologie.gouv.fr](https://www.ecologie.gouv.fr/politiques-publiques/financement-prevention-risques-naturels-hydrauliques) ; démarche en ligne de la [DDT31](https://demarche.numerique.gouv.fr/commencer/ddt31-demande-de-subvention-fprnm-rvpapi-travaux-d).
- Concurrence vérifiée : requête « batardeau anti-inondation maison particulier subvention Fonds Barnier diagnostic PPRI ». Ressortent uniquement le ministère, la DDT et la préfecture : **aucun site privé de devis**. Verdict : **ouvert**.
- Légal : le diagnostic PAPI est porté par la collectivité. Ne pas le vendre ni l'imiter. Aucun travail ne doit commencer avant le dépôt du dossier, sous peine de perdre la subvention : l'afficher. Ce n'est pas de la rénovation énergétique.
- Coût d'entrée : 170 €.
- Mini business plan : M1 2 leads × 80 € = 160 €. M3 400 €/mois. M6 10 leads = 800 €/mois. M12 1 000 €/mois (estim.).
- Premier test 7 jours + seuil kill : 3 communes du 31 en PAPI, 140 € d'Ads « subvention batardeau / fonds Barnier + ville ». Kill si moins de 2 leads.
- Score /50 : 36.

### L26 · Mesure acoustique de bruit de voisinage (PAC, climatisation, piscine)
- Modèle · Payeur · Prix : lead vendu à un bureau d'études acoustiques ; 40 à 60 € (estim.) pour une mission de 300 à 800 €.
- Zone prioritaire : zones pavillonnaires denses du Sud (Hérault, Bouches-du-Rhône, Gironde, Haute-Garonne), où les unités extérieures se multiplient. Non vérifié par des données.
- Preuve de demande : de 300 à 800 € pour un rapport NF S31-010 [appartement-hipa.fr](https://www.appartement-hipa.fr/peut-mesurer-bruit-pompe-chaleur/) ; offres dédiées aux particuliers [decibel-acoustique.fr](https://www.decibel-acoustique.fr/etude-ou-expertise/particuliers/expertise-acoustique-bruit-pompe-a-chaleur), [mixout.fr](https://mixout.fr/bruit-pompe-a-chaleur-voisin/).
- Concurrence vérifiée : requête « mesure acoustique bruit de voisinage pompe à chaleur voisin acousticien prix ». Ressortent 3 bureaux d'études et un blog. Pas d'agrégateur. Verdict : **ouvert**.
- Légal : **on ne vend ni PAC ni climatiseur**. Il s'agit d'une expertise de litige, hors du champ PAC exclu, mais l'angle reste proche : à valider par l'orchestrateur. Pas de démarchage.
- Coût d'entrée : 165 €.
- Mini business plan : M1 2 leads × 50 € = 100 €. M3 300 €/mois. M6 (été, bruit de la clim) 12 leads = 600 €/mois. M12 450 €/mois (estim.).
- Premier test 7 jours + seuil kill : en juin 2027, Ads sur Montpellier et Toulouse. Aujourd'hui, SEO seulement. Kill si moins de 3 leads en 7 jours d'été.
- Score /50 : 30.

### L27 · Infiltration des eaux pluviales à la parcelle (puits, tranchée), imposée par le PLU
- Modèle · Payeur · Prix : lead vendu à un terrassier ; 30 à 50 € (estim.) pour des ouvrages de 1 500 à 5 000 €.
- Zone prioritaire : Nantes Métropole (gestion à la parcelle obligatoire au-delà de 40 m²) [indre44.fr](https://www.indre44.fr/permis-de-construire-et-autorisations-durbanisme/) ; Montpellier 3M (40 premiers mm infiltrés) [guide Hérault (PDF)](https://www.herault.gouv.fr/contenu/telechargement/11766/69972/file/2026_Guide_Eaux-Pluviales.pdf) ; Terres Touloises ; Tarnos.
- Preuve de demande : puits de 2 m × 2 m pour environ 1 500 € ; infiltration imposée par le règlement [CC Terres Touloises (PDF)](https://www.terrestouloises.com/wp-content/uploads/2020/03/0-guideeauxpluvialesCC2T2020.pdf).
- Concurrence vérifiée : requête « puits d'infiltration eaux pluviales obligatoire PLU permis de construire prix particulier ». Ressortent uniquement des pages de collectivités et des PDF. **Aucune offre privée**. Verdict : **ouvert**. Distinct de la récupération d'eau de pluie (au catalogue).
- Légal : pas d'obstacle. Une étude de perméabilité est parfois exigée (renvoi vers L18 ou un bureau d'études).
- Coût d'entrée : 160 €.
- Mini business plan : M1 2 leads × 40 € = 80 €. M3 240 €/mois. M6 10 leads = 400 €/mois. M12 600 €/mois (estim.).
- Premier test 7 jours + seuil kill : 4 communes de Nantes Métropole. Kill si moins de 2 leads.
- Score /50 : 31.

### L28 · Ouverture de mur porteur (étude BET + maçon)
- Modèle · Payeur · Prix : lead « bundle » vendu à un maçon qui travaille avec un BET, ou à un BET structure ; 50 à 80 € (estim.) pour une étude de 600 à 2 500 € HT plus les travaux.
- Zone prioritaire : Lyon et Villeurbanne, la petite couronne parisienne (appartements anciens à décloisonner), Bordeaux.
- Preuve de demande : étude structure de 900 à 1 500 € HT avec visite [civigo.fr](https://civigo.fr/expertises/bet-structures/ouverture-mur-porteur/) ; offres de maçons locaux à Lyon [cheroise-batiment.com](https://www.cheroise-batiment.com/ouverture-mur-porteur-pose-ipn/).
- Concurrence vérifiée : requête « ouverture mur porteur devis Lyon prix bureau d'études IPN ». Ressortent 2 maçons locaux et 3 BET (Civigo, BE-T, Arch2L). Pas d'agrégateur dominant. Verdict : **moyen, ouvert**.
- Légal : accord de l'AG de copropriété (travaux affectant les parties communes) ; décennale du maçon.
- Coût d'entrée : 175 €.
- Mini business plan : M1 3 leads × 60 € = 180 €. M3 420 €/mois. M6 12 leads = 720 €/mois. M12 1 000 €/mois (estim.).
- Premier test 7 jours + seuil kill : Lyon et Villeurbanne, 150 € d'Ads. Kill si moins de 3 leads.
- Score /50 : 32.

---

## Rejetées

| Idée | Raison (1 ligne) | Source |
|---|---|---|
| Radon (mesure, zone 3) | Un dosimètre coûte 25 € en DIY, analyse comprise. Des collectivités prêtent des détecteurs gratuitement. Aucune obligation pour le particulier. | [neosfair.com](https://www.neosfair.com/mesure-radon/particuliers/), [ARS Bretagne](https://www.bretagne.ars.sante.fr/le-radon) |
| Démoussage et nettoyage de toiture | Secteur emblématique du démarchage abusif (UFC, préfecture du Calvados) : acheteurs à risque, image toxique. | [calvados.gouv.fr](https://www.calvados.gouv.fr/Actions-de-l-Etat/Alimentation.-consommation.-tourisme-et-commerce/Consommation.-tourisme-et-commerce/La-protection-du-consommateur-quelques-reglementations/Demarchage-a-domicile-prevention-des-degradations-du-batiment) |
| Traitement de charpente (capricornes, vrillettes) hors zone termites | Même alerte préfectorale. Aucune cartographie officielle, donc aucune obligation pour ancrer la demande. | idem Calvados |
| Adoucisseur d'eau | Arnaques récurrentes (« adoucisseur à 1 € », Sun Water). Aucune aide. Image toxique. | [prix-travaux.fr](https://www.prix-travaux.fr/prix-adoucisseur-eau/) |
| Enrobé d'allée et goudronnage | Réseaux d'escroquerie des « bitumeurs irlandais » signalés par la gendarmerie : risque d'acheteurs malhonnêtes. | [france3-regions](https://france3-regions.franceinfo.fr/grand-est/ardennes/charleville-mezieres/tout-ce-qu-il-faut-savoir-sur-l-escroquerie-dite-des-bitumeurs-irlandais-3106258.html) |
| Dépannage de volets roulants | Requête locale verrouillée par Somfy Assistance (dès 95 €, 250 installateurs) et des réseaux de dépannage du type « intervention en 45 min ». | [somfy.fr](https://www.somfy.fr/produits/volets-roulants/reparation/reparation-volet-roulant-lyon) |
| Store banne (réparation, rentoilage) | Pages ville déjà tenues par des réseaux de mise en relation (store-banne-direct, Store 2000) et par des storistes établis. | [store-banne-direct.fr](https://www.store-banne-direct.fr/installation-reparation-store-banne/toulouse-31100/) |
| Montage d'abri de jardin | Ticket bas (320 à 800 €), déjà couvert par e-local, Axeo et les services des enseignes. | [e-local.fr](https://e-local.fr/service/abris-de-jardin/) |
| Nettoyage de gouttières | Ticket de 90 à 240 €, SAP et plateformes (mesjardiniers), proche des arnaques à la toiture. | [gozeco.fr](https://services.gozeco.fr/prix/nettoyage-gouttieres.html) |
| Entretien de chaudière gaz ou fioul | Ticket de 95 à 150 €, artisans très nombreux et contrats de grands réseaux : lead à quelques euros, non rentable. | [cm-energie.fr](https://cm-energie.fr/entretien-de-chaudiere-gaz-a-lille/) |
| Nettoyage de panneaux photovoltaïques | Famille « solaire » exclue par le brief. Ticket de 150 à 350 €. | [upsolaire.fr](https://upsolaire.fr/nettoyage-panneaux-solaires/) |
| Recherche de fuite non destructive | Demande réelle (convention IRSI), mais SERP occupée par des réseaux nationaux et des dépanneurs 24/7, proches du débouchage d'urgence exclu. | [alber-pro.com](https://alber-pro.com/prestations/degat-des-eaux/) |
| Dessouchage et rognage | Mêmes acheteurs que l'élagage, déjà au catalogue (Serpe, élagueurs bordelais) : doublon. | [bordeaux.serpe.fr](https://www.bordeaux.serpe.fr/la-serpe-en-gironde/dessouchage-a-bordeaux) |
| Abattage d'arbres dangereux | Doublon de l'élagage du catalogue. | même source |
| Portail automatique | Doublon de « clôture / portail » au catalogue. | — |
| Goélands (stérilisation d'œufs, filets) | Espèce protégée. Les villes (Le Havre) stérilisent gratuitement : substitut public gratuit. | [actu.fr](https://actu.fr/normandie/le-havre_76351/au-havre-comment-faire-si-vous-reperez-un-nid-de-goeland-sur-votre-toit_62387742.html) |
| Broyage de déchets verts à domicile | Service public gratuit (Bordeaux Métropole) ou à 30 € l'heure (Pays de Fayence) : substitut public. | [bordeaux-metropole.fr](https://www.bordeaux-metropole.fr/a-votre-service/services-aux-particuliers/dechets/je-reduis-je-reutilise/je-broie) |
| Vidéosurveillance de particulier | Kits DIY de 100 à 400 €, grandes enseignes en abonnement et installateurs déjà positionnés : lead à faible valeur. | [adone-informatique.fr](https://www.adone-informatique.fr/videosurveillance-marseille/particulier/) |
| Gazon synthétique | Le fabricant Azurio capte déjà les demandes de pose et les distribue à 1 700 installateurs partenaires. | [azurio-gazon.fr](https://azurio-gazon.fr/service-pose/gazon-synthetique-montpellier/) |
| Insonorisation des riverains d'aéroports (aide TNSA) | Les travaux portent sur les menuiseries et l'isolation de toiture (famille isolation exclue). Le parcours est géré par l'exploitant et ses AMO (Espace 9 à Nantes). | [service-public F1702](https://www.service-public.gouv.fr/particuliers/vosdroits/F1702), [nantes.aeroport.fr](https://www.nantes.aeroport.fr/fr/aide-insonorisation) |
| Bornage par géomètre-expert | Profession à monopole réglementé : la rémunération d'un apporteur d'affaires n'est pas vérifiée sous l'angle déontologique. Ticket de 500 à 2 000 €, mais risque juridique. | [service-public F3037](https://www.service-public.gouv.fr/particuliers/vosdroits/F3037) |
| Travaux pour le « permis de louer » | Travaux multi-métiers, souvent de décence énergétique (exclue) ; demande diffuse, sans métier acheteur clair. | [service-public F34210](https://www.service-public.gouv.fr/particuliers/vosdroits/F34210) |
| Ravalement obligatoire (Paris, Lyon, Nantes) | Depuis 2017, le ravalement entraîne souvent une obligation d'isolation (famille exclue). Décision de syndic, secteur exposé au démarchage. | [lyon.fr](https://www.lyon.fr/vie-pratique/logement-et-urbanisme/le-ravalement-de-facade) |
| Guêpes | Doublon des « frelons » au catalogue (mêmes désinsectiseurs). | — |
| Expertise avant achat immobilier | Requête occupée par des acteurs nationaux (ExpertGo, Opengroupe, AMO Paris). Le segment expert bâtiment est déjà couvert par L08 et L21. | [opengroupe.fr](https://www.opengroupe.fr/prix-expertise-maison-avant-achat) |
| Fourmis charpentières (Alpes) | Ticket d'environ 150 € ; traité par les désinsectiseurs généralistes. Niche trop étroite. | [lrpro-tec.fr](https://lrpro-tec.fr/desinsectisation/traitement-anti-fourmi-aix-les-bains/) |
| Pompe et poste de relevage | Pages tenues par des réseaux « 24/7 » de pompage et d'hydrocurage, proches du débouchage d'urgence exclu. | [idf-pompage.fr](https://www.idf-pompage.fr/prestations/nettoyage-entretien-pompe-relevage.html) |
| Diagnostics électricité, gaz, plomb (CREP) avant vente ou location | Diagnostiqueurs certifiés, marché tenu par des comparateurs de diagnostics. Hors cœur artisan. Non revérifié en SERP. | — (raisonnement, non sourcé) |
| Légionelle chez le particulier | Pas d'obligation chez le particulier, demande marginale. Non revérifié. | — (raisonnement) |
| Toiture végétalisée | Marché de niche du neuf ou du tertiaire, pas de demande B2C locale identifiable. Non revérifié. | — (raisonnement) |
| Clôture électrique | Usage agricole et équestre, en plus d'un doublon partiel de « clôture ». | — |
| Insert, poêle, tubage de cheminée | Relève de la rénovation énergétique (MaPrimeRénov') et chevauche le ramonage du catalogue. | — |
| Hydrocurage préventif des canalisations | Même écosystème que le débouchage d'urgence exclu. | — |
| Contrôle de raccordement à la vente (le contrôle lui-même) | Réalisé par le service public (SPAC, régies), donc rien à vendre. Seuls les travaux sont retenus (L11). | [service-public F31685](https://www.service-public.gouv.fr/particuliers/vosdroits/F31685) |

## Prochaines vérifications recommandées (avant de construire)

1. Refaire la requête d'achat de chaque idée sur google.fr, en navigation privée, depuis la ville visée. Noter le Pack local, les annonces et les 10 premiers résultats.
2. Pour chaque idée, appeler 3 acheteurs potentiels **avant** de construire le site et obtenir un « oui à X € le lead » écrit.
3. L05 : vérifier l'arrêté mérule du Finistère en vigueur. L19 : surveiller l'échéance du 01/11/2027. L20 : vérifier la déontologie des experts d'assurés sur l'apport d'affaires.
