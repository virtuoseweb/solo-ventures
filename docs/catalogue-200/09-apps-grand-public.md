# 09 · Apps mobiles grand public (iOS et Android, marché francophone)

Agent « winner » · 21 octobre 2026 · famille : apps payantes grand public (paywall dur, essai long, abonnement ou passe), France, Belgique, Suisse, Québec, plus les outre-mer francophones.

## Avertissement de méthode (à lire avant tout)

- **Objectif non atteint : 6 idées validées sur 22 visées, 99 rejets documentés.** Je n'ai pas complété la liste avec des idées faibles. Après environ 130 requêtes Exa, les seules failles qui tiennent sont des examens hyper-locaux (Québec, Wallonie, Bruxelles, Nouvelle-Calédonie). Leur format exact n'est couvert par aucune app.
- **Le marché grand public est saturé en 2026.** Les gros revenus indépendants existent bien :
  - Prayer Lock, 20 000 $/mois ([source](https://stackstarts.com/how-mao-built-prayer-lock-20k-month/)) ;
  - QUITTR, Puff Count et HabitKit, avec des MRR à 5 ou 6 chiffres ([source](https://getappniche.com/guides/ios-app-success-stories)) ;
  - plusieurs apps vérifiées sur TrustMRR ([source](https://trustmrr.com/category/mobile-apps)).

  Mais pour chacune, la version française existe déjà, souvent produite à l'IA :
  - YouPray, Prayer Lock FR et PrayFocus pour la prière ;
  - Adieu Vape pour la vape ;
  - Omena pour la ménopause ;
  - Shotsy, traduit en français, pour le GLP-1.

  Les banques de questions gratuites et génériques couvrent déjà beaucoup d'examens canadiens et belges : ExamHub.ca, Canada Exam Prep, OpenExamPrep. C'est le premier motif de rejet de la seconde passe.
- **Exa n'est pas google.fr.** Le classement et la couverture des stores diffèrent. Un concurrent trouvé par Exa est un vrai concurrent. Une absence de concurrent ne prouve rien tant qu'elle n'a pas été vérifiée dans l'App Store et le Play Store du pays visé. Chaque fiche liste 3 requêtes formulées différemment, dont une de type store.
- **Notes et avis.** La note et le nombre d'avis ne sont donnés que lorsqu'ils figuraient dans la page lue. Sinon : « note non trouvée ».
- **Volumes.** Le nombre annuel de candidats n'a pas été trouvé pour G01, G02, G03, G05 et G06. Seule l'EUF (G04) a un volume officiel. Les business plans de ces 5 fiches reposent donc sur des hypothèses d'installs à vérifier pendant le test de 7 jours.
- **Estimations et conversions.**
  - Tout chiffre de plan porte la mention « estim. ».
  - Conversion de référence (benchmark RevenueCat 2026 repris de la famille 04) : paywall dur 10,7 %, freemium 2,1 %. Les plans retiennent 5 à 10 % des installs, par prudence.
  - Commission store : 15 % (programme petites entreprises).
  - Change : 1 $ ≈ 0,92 € (estim.), 1 $ CA ≈ 0,62 € (estim., à vérifier). La parité 1 000 XPF = 8,38 € est fixe.
- **Barème du score /50.** Cinq critères notés sur 10 :
  - demande prouvée ;
  - écart francophone (vide ou faiblesse des concurrents) ;
  - coût et vitesse du premier euro ;
  - faisabilité solo (Claude Code, Expo ou React Native, RevenueCat gratuit) ;
  - risque légal et plateforme (inversé).
- **Coûts communs.** Apple Developer 99 $/an ≈ 91 € ; Google Play 25 $ une fois ≈ 23 € ; domaine ≈ 10 €. Option moins chère pour le test : publier d'abord en PWA ou en web, puis passer aux stores.
- **Colonne `ca_m6_hyp_eur` du CSV.** C'est le CA brut du 6e mois, avant commission store. Pour G02, saisonnier, c'est le CA cumulé de la saison.
- **Idées déjà présentes dans le catalogue, non reproposées.** S02 à S08, A01, A04, A05, E01, E10, T09, C1 à C6, D1, A4, A5. Les pistes en attente de la famille 04 (concours catégorie C, garde alternée, code de la route, BAFA) n'ont pas été reprises.

---

## Idées validées

### G01 · CÉFRANC Prêt, tests de français du personnel de soutien scolaire (Québec)
- **Modèle · Payeur · Prix** : app iOS/Android avec paywall dur après un diagnostic gratuit de 10 questions. Payé par le candidat à un poste de soutien (secrétaire, agent de bureau, service de garde). Prix : passe de 60 jours à 39,99 $ CA (estim.).
- **Cible / zone** : candidats aux postes de soutien des centres de services scolaires du Québec qui exigent le CÉFRANC ou le SEL. Les tests 2, 4 et 6 sont des QCM ; les tests 5 et 7 sont des rédactions (note de service de 150 mots, lettre de 200 mots). Extension possible au SEL.
- **Preuve de demande** :
  - Le CSS des Draveurs exige la réussite du test : 70 % pour les secrétaires, 60 % pour les autres postes, document de juin 2026 ([source](https://www.cssd.gouv.qc.ca/application/files/9817/8051/1570/Test_de_francais_-_Soutien.pdf)).
  - Les guides officiels du CÉFRANC décrivent les formats : test 6 en 50 QCM, test 5 en note de 150 mots, test 7 en lettre de 200 mots ([source](https://cefranc.csspi.ca/guides.php)).
  - Préparation payante chez ALC : 195 $ CA par semaine, plus 150 $ d'inscription et 95 $ de matériel ([source](https://www.alc-cominternational.com/preparation-strategique-cefranc/)).
  - Le centre Pauline-Julien du CSSDM propose un cours TECFÉE-CÉFRANC-SEL ([source](https://centre-pauline-julien.cssdm.gouv.qc.ca/programmes/cours-specifiques/)).
- **Concurrence vérifiée** :
  - Requêtes :
    1. « préparation test CÉFRANC personnel de soutien secrétaire agent de bureau centre de services scolaires exercices en ligne »
    2. « application iPhone préparation test CÉFRANC personnel de soutien centre de services scolaires » (store)
    3. « test pratique gratuit CÉFRANC personnel de soutien agent de bureau grammaire 50 questions en ligne »
  - Ce qui sort :
    - grammaire.ca, site web qui couvre un tronc commun générique à 8 examens, prix non affiché ([source](https://grammaire.ca/)) ;
    - Pratique TECFÉE, app de 800+ questions pour 6 000+ utilisateurs, mais TECFÉE seulement, note non trouvée ([source](https://pratiquetecfee.com/)) ;
    - les exercices gratuits de la BDL et les guides PDF officiels.

    Aucune app n'existe pour les tests de soutien.
  - Verdict : faible concurrence.
  - Angle non servi : reproduire le format exact des tests 5, 6 et 7. Cela veut dire un QCM chronométré de 50 questions pour le test 6, et une correction IA de la note et de la lettre selon les critères des guides officiels.
- **Légal** :
  - Les guides CÉFRANC portent la mention « tous droits réservés ». Le contenu doit donc être original, avec un format imité mais aucune question copiée.
  - Loi 25 (Québec) sur les données personnelles : politique de confidentialité et hébergement documenté.
  - Pas de statut réglementé.
- **Coût d'entrée** : environ 144 € (Apple 91 + Google 23 + domaine 10 + API Claude pour la correction, 20 € estim.).
- **Mini business plan (estim.)** :
  - Hypothèses : acquisition par pages SEO « test CÉFRANC » et groupes Facebook d'emplois scolaires ; conversion de 6 % des installs (estim.) ; 40 $ CA par payant.
  - M1 : 50 installs → 3 payants → 120 $ CA (≈ 74 €).
  - M3 : 150 installs par mois → 9 payants → 360 $ CA (≈ 223 €).
  - M6 : 250 installs → 15 payants → 600 $ CA (≈ 372 € brut).
  - M12 : avec le module SEL, 400 installs → 24 payants → 960 $ CA (≈ 595 €).
- **Premier test 7 jours + seuil kill** :
  - Test : une page avec un diagnostic web gratuit de 30 questions et une prévente à 19,99 $ CA (Stripe), diffusée dans 5 groupes Facebook d'emploi en centres de services scolaires.
  - Kill si moins de 100 visites, moins de 15 e-mails ou aucune prévente.
- **Score /50** : **38** (demande 6, écart 8, coût 8, faisabilité 8, risque 8).

### G02 · Chasse Wallonie Prépa, examen théorique de chasse (Wallonie)
- **Modèle · Payeur · Prix** : app avec 30 questions gratuites puis achat unique par saison. Payé par le candidat chasseur. Prix : 34,99 € (estim.).
- **Cible / zone** : candidats à l'examen théorique wallon, Belgique francophone. Saison de vente : novembre à mars.
- **Preuve de demande** :
  - L'examen compte 60 QCM. Seuils : 9/15, 18/30 et 11/15 par branche, et 40/60 au total. Inscription jusqu'au 14/01/2027, sessions le 20/02 et le 13/03/2027. L'administration ne fournit aucun manuel ([source](https://www.wallonie.be/fr/demarches/sinscrire-et-passer-lexamen-de-chasse-en-wallonie)).
  - Accadia vend un cours à 399 € : 54 chapitres, 432 QCM, et précise qu'il n'y a qu'un examen par an ([source](https://accadia.be/cours/examen-de-chasse)).
  - Le RSHCB vend un kit avec un accès web SIEL, ouvert d'octobre à mai et à renouveler chaque année ([source](https://formation.chasse.be/ressources/siel)).
  - Des annales officielles corrigées sont publiées ([source](https://www.chasse.be/files/files/20240226-examen-de-chasse-questions-fr-1ere-session.pdf), [source](https://iodda.be/public/annexes/2994/document/fr)).
- **Concurrence vérifiée** :
  - Requêtes :
    1. « préparer examen de chasse Wallonie théorique questions application ou examen chasse canton Vaud Valais Fribourg »
    2. « application Android examen de chasse Wallonie questions théoriques entraînement » (store)
    3. « quiz gratuit examen de chasse Wallonie entraînement questions réglementation gibier armes en ligne »
  - Ce qui sort :
    - Accadia, web à 399 € ;
    - SIEL, web, inclus dans le kit RSHCB ;
    - examensimulator-jacht.be : 59 € pour 421 questions, mais pour l'examen flamand ([source](https://www.examensimulator-jacht.be/fr)) ;
    - Chassexam de la FNC, gratuit, 10 000+ téléchargements, mais pour le permis français ([source](https://play.google.com/store/apps/details?hl=fr&id=com.fnc.permischasse)).

    Aucune app mobile n'existe pour l'examen wallon. Note et avis non affichés pour Accadia et SIEL.
  - Verdict : concurrence web chère, aucune app mobile.
  - Angle non servi : une app mobile 10 fois moins chère qu'Accadia, avec répétition espacée, un mode « branche à seuil » et une mise à jour légale chaque année.
- **Légal** :
  - Vérifier les droits de réutilisation des annales du SPW et de la RSHCB. Par défaut, écrire des questions originales.
  - RGPD.
  - Pas de statut réglementé.
- **Coût d'entrée** : environ 124 € (Apple 91 + Google 23 + domaine 10 ; pas d'API).
- **Mini business plan (estim.)** :
  - Hypothèses : groupes Facebook de chasseurs wallons et SEO « examen de chasse Wallonie » ; conversion de 10 % des installs (estim.) ; publication mi-décembre 2026.
  - M1 (novembre) : construction de l'app et banque de 300 questions, 0 €.
  - M3 (janvier, pic des inscriptions) : 80 installs → 8 payants → 280 €.
  - M4-M5 (sessions de février et mars) : 120 installs → 12 payants → 420 €.
  - M6 (avril) : quasi nul. Cumul de la saison : 20 payants → 700 € brut.
  - M12 (saison 2, avec les annales 2027) : 30 payants → 1 050 € sur la saison.
- **Premier test 7 jours + seuil kill** :
  - Test : 20 questions gratuites en web et une prévente à 24,99 €, diffusées dans 5 groupes Facebook de chasse wallons.
  - Kill si moins de 30 e-mails ou aucune prévente.
- **Score /50** : **37** (demande 6, écart 8, coût 8, faisabilité 8, risque 7, à cause des droits sur les annales et de la saisonnalité).

### G03 · OQLF Simu, simulation orale et écrite de l'examen de français des ordres professionnels (Québec)
- **Modèle · Payeur · Prix** : abonnement avec paywall dur après une simulation gratuite. Payé par le professionnel formé hors du Québec, à qui son ordre demande de réussir l'examen. Prix : 29,99 $ CA par mois ou 69,99 $ CA pour 3 mois (estim.).
- **Cible / zone** : Québec, ordres professionnels (infirmières, ingénieurs, médecins). Interface bilingue, car une partie des candidats n'est pas francophone. Exemption pour 3 ans d'études en français : article 35 de la Charte, à vérifier.
- **Preuve de demande** :
  - L'examen est gratuit et comporte 4 activités, toutes à réussir dans la même séance. Une reprise n'est possible qu'après 3 mois, à Montréal ou Québec seulement ([source](https://www.quebec.ca/education/apprendre-le-francais/ordre-professionnel/examen)).
  - Le taux de réussite était de 39 % au 10 septembre 2019, en période de transition ([source](https://doi.org/10.71781/5342)).
  - Préparation payante : UdeM à 545 $ pour 33 h ([source](https://ecoledefrancais.umontreal.ca/formations/preparation-aux-examens-de-loqlf/)), Collège Canada à 465 $ CA pour 30 h ([source](https://ccsl.ca/fr/oqlf-preparation/)), cours de McGill ([source](https://www.mcgill.ca/continuingstudies/language-test-centre/oqlf-french-exam-preparation-course)).
- **Concurrence vérifiée** :
  - Requêtes :
    1. « préparation examen de français de l'OQLF ordre professionnel infirmière ingénieur immigrant application exercices »
    2. « application pratique examen OQLF étude de cas discussion de groupe simulation taux de réussite candidats ordres professionnels »
    3. « app Android examen de français OQLF infirmière ingénieur simulation orale entraînement App Store » (store)
  - Ce qui sort :
    - NursePrepQc : iOS, en anglais, pour les infirmières seulement, Premium à 4,99 $, aucune note affichée ([source](https://apps.apple.com/us/app/nurseprepqc/id6767641117)) ;
    - TestBuddy : page OQLF annoncée, pas encore en ligne ([source](https://testbuddy.ai/tests/oqlf-quebec)) ;
    - lecoursgratuit : 6 examens en format Word ([source](https://lecoursgratuit.com/examen-oqlf-quebec-corrige/)) ;
    - exemples officiels gratuits d'études de cas ([source](https://www.oqlf.gouv.qc.ca/francisation/ordres_prof/preparation-examen/etude-cas/)) ;
    - Vocalis, qui vise le TCF et le TEF, pas l'OQLF.
  - Verdict : faible concurrence.
  - Angle non servi : aucun outil ne fait passer la discussion de groupe ni l'entretien individuel en simulation orale IA, par profession et en français québécois.
- **Légal** :
  - Loi 25 : les enregistrements vocaux sont des données personnelles. Il faut un consentement explicite, une durée de conservation courte et des sous-traitants documentés.
  - Ne pas se présenter comme partenaire de l'OQLF.
- **Coût d'entrée** : environ 164 € (Apple 91 + Google 23 + domaine 10 + 40 € de tests d'API vocale, estim.).
- **Mini business plan (estim.)** :
  - Hypothèses : SEO « examen OQLF », groupes Facebook d'infirmières et d'ingénieurs immigrants ; conversion de 5 % ; 50 $ CA en moyenne par payant.
  - Coût vocal par minute à mesurer en semaine 1, et à plafonner par forfait.
  - M1 : 60 installs → 3 payants → 150 $ CA (≈ 93 €).
  - M3 : 150 installs → 8 payants → 400 $ CA (≈ 248 €).
  - M6 : 250 installs → 13 payants → 650 $ CA (≈ 403 € brut).
  - M12 : 400 installs → 20 payants → 1 000 $ CA (≈ 620 €).
- **Premier test 7 jours + seuil kill** :
  - Test : vendre à 15 $ CA une simulation orale de 15 minutes, menée par un prototype vocal, via une page et un agenda en ligne.
  - Kill si moins de 3 sessions payées en 7 jours.
- **Score /50** : **37** (demande 7, écart 9, coût 7, faisabilité 7, risque 7).

### G04 · EUF Coach, Épreuve uniforme de français des cégeps (Québec)
- **Modèle · Payeur · Prix** : app avec la correction d'un premier paragraphe gratuite, puis un passe ou un abonnement. Payé par l'étudiant de cégep ou ses parents. Prix : passe de session à 24,99 $ CA ou 9,99 $ CA par mois (estim.).
- **Cible / zone** : étudiants des cégeps du Québec, en priorité ceux qui ont échoué une première fois.
- **Preuve de demande** :
  - 42 663 passations en 2023-2024, pour un taux de réussite global de 82,8 % ([source](https://cdn-contenu.quebec.ca/cdn-contenu/adm/min/education/publications-adm/ES/Epreuve_uniforme/Rapport-EULE-francais-2023-2024.pdf)).
  - 4 591 échecs sur 36 591 étudiants à la première passation ([source](https://cdn-contenu.quebec.ca/cdn-contenu/adm/min/education/publications-adm/enseignement-superieur/Portrait-Echecs-EUF.pdf)).
  - Le taux de réussite est en baisse, de 87,9 % à 82,9 % ([source](https://www.journaldequebec.com/2026/02/13/des-cegepiens-en-arrachent-en-francais--le-taux-de-reussite-est-en-baisse-revele-la-nouvelle-edition-du-palmares-des-cegeps-du-journal)).
  - Centrétudes vend un cours de groupe à 490 $ et un diagnostic à 95 $ ([source](https://centretudes.com/preparation-a-lepreuve-uniforme-de-francais/)).
- **Concurrence vérifiée** :
  - Requêtes :
    1. « application préparation épreuve uniforme de français cégep EUF dissertation critique entraînement correction »
    2. « épreuve uniforme de français cégep préparation correction IA dissertation critique application payante »
    3. « application mobile iPhone Android préparation épreuve uniforme de français EUF cégep dissertation » (store)
  - Ce qui sort :
    - ARFQC : plateforme web québécoise de diagnostic IA (EUF, cégep, MEQ), payante après un premier diagnostic gratuit, note non trouvée ([source](https://arfqc.com/)) ;
    - ressources gratuites du CCDMD, qui interdit tout lien depuis une section payante ([source](https://ccdmd.qc.ca/ressources/se-preparer-a-lepreuve-uniforme-de-francais/)) ;
    - un manuel gratuit sous licence CC BY-NC-SA.

    Aucune app mobile dédiée n'a été trouvée.
  - Verdict : concurrence modérée. Un acteur IA existe sur le web.
  - Angle non servi : photographier sa dissertation manuscrite (ou coller un texte tapé ; le mode de passation de l'épreuve, papier ou ordinateur, reste à vérifier) et la faire corriger selon la grille officielle et la règle de 30 fautes par 900 mots. Ajouter des exercices quotidiens tirés des propres fautes de l'étudiant, pour les quelque 4 600 étudiants en échec à la première passation.
- **Légal** :
  - Loi 25.
  - Utiliser des extraits d'œuvres du domaine public.
  - Ne pas renvoyer vers le CCDMD depuis la partie payante.
  - Les étudiants ont surtout 17 ans et plus ; régler la classification d'âge en store.
- **Coût d'entrée** : environ 154 € (Apple 91 + Google 23 + domaine 10 + 30 € d'API vision et correction, estim.).
- **Mini business plan (estim.)** :
  - Hypothèses : TikTok et Instagram cégep, SEO « EUF dissertation critique » ; conversion de 5 % ; 25 $ CA par payant. Pics de vente avant les sessions (dates non vérifiées).
  - M1 : 150 installs → 8 payants → 200 $ CA (≈ 124 €).
  - M3 : 500 installs → 25 payants → 625 $ CA (≈ 388 €).
  - M6 : 800 installs → 40 payants → 1 000 $ CA (≈ 620 € brut).
  - M12 : 1 200 installs → 60 payants → 1 500 $ CA (≈ 930 €).
- **Premier test 7 jours + seuil kill** :
  - Test : correction web gratuite d'un paragraphe photographié, diffusée par 3 publications sur Reddit et TikTok côté cégep, avec une prévente du passe à 14,99 $ CA.
  - Kill si moins de 50 photos envoyées ou moins de 5 préventes.
- **Score /50** : **37** (demande 8, écart 6, coût 8, faisabilité 8, risque 7).

### G05 · BOSA Taaltest, test linguistique de néerlandais des articles 8 et 9 pour fonctionnaires francophones (Belgique)
- **Modèle · Payeur · Prix** : abonnement avec 3 jours d'essai. Payé par le fonctionnaire ou le candidat fédéral ou bruxellois. Prix : 9,99 € par mois ou 49 € pour 6 mois (estim.).
- **Cible / zone** : agents francophones de Bruxelles et des services fédéraux qui préparent l'épreuve linguistique de néerlandais du SPF BOSA.
- **Preuve de demande** :
  - Prime à la clé : l'allocation linguistique de l'article 9 §2 (connaissance « suffisante ») vaut 110 € à l'indice 138,01. Avec le coefficient de 1,8476 (avril 2022), cela fait environ 203 € par mois brut ([source](https://fedweb.belgium.be/fr/remuneration_et_avantages/allocation/allocation-linguistique)).
  - Le vademecum CPCL 2025 exige une connaissance élémentaire de la seconde langue pour les agents en contact avec le public ([source](https://vct-cpcl.be/sites/default/files/documenten/vade-mecum-examens-linguistiques-2025.pdf)).
  - Cours payants : Lerian-NTI, 30 h ([source](https://www.lerian-nti.be/fr/examen-du-selor-pour-le-neerlandais)), et CVO Semper ([source](https://www.cvosemper.be/fr/opleidingen/vakgebied/820/neerlandais-preparation-au-test-de-langue-travaillerpour-selor)).
- **Concurrence vérifiée** :
  - Requêtes :
    1. « préparation examen linguistique BOSA article 8 article 9 néerlandais fonctionnaire Bruxelles prime bilinguisme application »
    2. « s'entraîner test linguistique Selor néerlandais article 8 exemples questions application en ligne payant »
    3. « application iPhone BOSA test linguistique néerlandais article 8 entraînement compréhension à l'audition fonctionnaire » (store)
  - Ce qui sort :
    - EasySelor, qui prépare aux tests de raisonnement, pas aux tests de langue ([source](https://easyselor.be/fr)) ;
    - psychotechnique.be, avec des packs d'aptitude ([source](https://psychotechnique.be/travaillerpourbe-test-linguistique-informatise/)) ;
    - IGO Taaltrainer, centré sur le vocabulaire des magistrats ;
    - ERAP, une formation gratuite de 63 h pour les agents locaux bruxellois ([source](https://www.erap-gsob.brussels/catalogue-de-formation-fr/formation/524/preparation-aux-epreuves-linguistiques-du-spf-bosa-travaillerpourbe-neerlandais-niveau-b1/)).

    Aucune app n'a été trouvée pour l'épreuve de l'article 8.
  - Verdict : faible concurrence payante, mais il existe des formations gratuites en présentiel.
  - Angle non servi : un entraînement mobile quotidien au format de l'épreuve. Il comprendrait des audios écoutés une seule fois, des lectures de type presse et le vocabulaire administratif belge. C'est un complément aux cours ERAP, qu'on peut suivre dans le train.
- **Légal** :
  - RGPD.
  - Aucune affiliation avec BOSA ne doit être suggérée.
  - Pas de statut réglementé.
- **Coût d'entrée** : environ 144 € (Apple 91 + Google 23 + domaine 10 + 20 € de synthèse vocale néerlandaise, estim.).
- **Mini business plan (estim.)** :
  - Hypothèses : publications LinkedIn et SEO « test linguistique BOSA néerlandais » ; conversion de 6 % ; 9 € par mois et par payant actif.
  - M1 : 40 installs → 2 payants → 20 €.
  - M3 : 120 installs → 7 payants actifs → MRR 65 €.
  - M6 : 200 installs → 13 payants actifs → MRR 120 €.
  - M12 : 25 payants actifs → MRR 225 €.
  - Extension possible : le sens inverse (français pour néerlandophones), hors cible francophone.
- **Premier test 7 jours + seuil kill** :
  - Test : 10 exercices audio gratuits en web et une prévente du forfait de 6 mois à 39 €, diffusés par 3 publications LinkedIn et dans des groupes de fonctionnaires.
  - Kill si moins de 30 inscrits ou aucune prévente.
- **Score /50** : **36** (demande 7, écart 8, coût 8, faisabilité 6, risque 7). Le néerlandais doit être relu par un locuteur natif, et la concurrence gratuite des employeurs pèse.

### G06 · Code Calédonien, code de la route avec les questions spécifiques de Nouvelle-Calédonie
- **Modèle · Payeur · Prix** : achat unique après 20 questions gratuites. Payé par le candidat libre ou en auto-école. Prix : environ 2 500 XPF, soit environ 21 € (estim.).
- **Cible / zone** : Nouvelle-Calédonie (Nouméa et brousse).
- **Preuve de demande** :
  - 46 % de réussite au code au premier semestre 2022, et seulement 17 % chez les candidats libres. Les supports sont métropolitains alors que 5 questions sur 40 sont spécifiques à la Nouvelle-Calédonie, par exemple le kava ou les radiers ([source](https://la1ere.franceinfo.fr/nouvellecaledonie/le-code-de-la-route-un-examen-difficile-a-passer-en-nouvelle-caledonie-1318236.html)).
  - Les candidats libres sont admis ([source](https://dittt.gouv.nc/permis-de-conduire/demande-de-permis-de-conduire/examen-du-permis-de-conduire)).
  - Chrono64 vend des forfaits code de 28 000 à 38 000 XPF, et le code en ligne à 3 500 XPF par mois ([source](https://www.chrono64.nc/permis/code-de-la-route/)).
  - Un utilisateur a publié une fiche Quizlet sur le code calédonien ([source](https://quizlet.com/study-guides/code-de-la-route-en-nouvelle-caledonie-regles-vitesse-priori-65d44d44-5c32-4a3d-8dcb-1bcd2bb4ab27)).
- **Concurrence vérifiée** :
  - Requêtes :
    1. « application code de la route Nouvelle-Calédonie entraînement examen théorique »
    2. « code de la route calédonien en ligne tests spécifiques Nouvelle-Calédonie application mobile auto-école Nouméa »
    3. « application Android iPhone code de la route Nouvelle-Calédonie questions spécifiques calédoniennes kava radiers » (store)
  - Ce qui sort : les auto-écoles utilisent des outils métropolitains (Pass Rousseau, Prépacode). Aucune app calédonienne n'a été trouvée, et la note des outils métropolitains n'a pas été relevée.
  - Verdict : vide local.
  - Angle non servi : une banque de questions propre à la Nouvelle-Calédonie, couvrant les radiers, le kava, les vitesses locales et les priorités locales. Elle compléterait l'app métropolitaine, sans la remplacer.
- **Légal** :
  - Questions originales.
  - Le code de la route calédonien est public (Juridoc, DITTT, [réglementation](https://dittt.gouv.nc/permis-de-conduire/reglementation)).
  - Les données personnelles relèvent du régime applicable en Nouvelle-Calédonie, à vérifier.
- **Coût d'entrée** : environ 124 € (Apple 91 + Google 23 + domaine 10).
- **Mini business plan (estim.)** :
  - Hypothèses : groupes Facebook calédoniens et SEO local ; conversion de 10 % ; marché petit et non quantifié.
  - M1 : 40 installs → 4 payants → 84 €.
  - M3 : 100 installs par mois → 10 payants → 210 € par mois.
  - M6 : plateau → 210 € par mois.
  - M12 : 250 € par mois avec une licence pour auto-écoles, à tester.
- **Premier test 7 jours + seuil kill** :
  - Test : 20 questions calédoniennes gratuites en web et une prévente à 1 500 XPF, diffusées dans 3 groupes Facebook calédoniens et auprès de 2 auto-écoles.
  - Kill si moins de 40 inscrits ou moins de 3 préventes.
- **Score /50** : **38** (demande 5, écart 9, coût 8, faisabilité 8, risque 8). Le marché est petit mais vide, et le premier euro arrive vite.

---

## Rejetées (99)

Rappel des motifs :
1. Équivalent gratuit.
2. Au moins 3 acteurs francophones installés sur la niche exacte, sans angle démontrable.
3. Pas de preuve de paiement ou de recherche.
4. Statut réglementé inatteignable.
5. Coût d'entrée supérieur à 200 €.

### Seconde passe, sources vérifiées (44)

| # | Idée | Motif | Concurrents relevés (note / avis si trouvés) | Source |
|---|---|---|---|---|
| R01 | Compteur de télétravail frontalier France-Suisse | 1 | Compteur complet gratuit d'AdminLanding ; Frontalier Pratique gratuit ; Crossmate ; FrontalierComply (B2B) | [AdminLanding](https://www.adminlanding.com/compteur-teletravail-frontalier) |
| R02 | Examens de métiers CCQ (Québec) | 2 | ExamCCQ, PrépaVolt, Metierium, Prof-RBQ, Formation Électriciens (8 500+ utilisateurs) | [ExamCCQ](https://examccq.com/) |
| R03 | Compteur de jours pour snowbirds québécois | 1 | Snowbirds US Day Tracker gratuit, 4,8/5 sur 163 notes ; calculateur RAMQ gratuit ; Snowbird Days ; iReside à 44,99 $/an ; Day31 | [fiche](https://mwm.ai/fr/apps/snowbirds-us-day-tracker/1455792679) |
| R04 | Théorie de plongée FFESSM | 1 et 2 | QuizDive (2 000+ questions), Microbulles gratuit, RevisionMF2 | [QuizDive](https://quiz-dive.app/) |
| R05 | Carnet de rucher et apiculture | 1 et 2 | Api'Track entièrement gratuit, HexaBees, BeePerf, Beekube, 3Bee, APIGO, ApiNote | [Api'Track](https://api-track.fr/gestion-ruchers-elevage) |
| R06 | Registre d'élevage de reptiles | 2 | ReptiNode, ReptiTrack, SquamaTracker, TerraTrack, Sauria | [ReptiNode](https://reptinode.fr/) |
| R07 | Scrabble duplicate | 1 et 2 | DupliJeu de la FFSc (10 000+ téléchargements), Duel de mots gratuit | [Play Store](https://play.google.com/store/apps/details?hl=fr&id=fr.ffsc.duplijeu) |
| R08 | Suisse allemand pour francophones | 2 | uTalk (app classique 1,6/5 sur 7 notes), LanguageFast (en français), Speeku, Grüezi, rede.chat | [Speeku](https://www.speeku.com/swiss-german/) |
| R09 | Français québécois pour nouveaux arrivants | 2 | Calliope, Talkparty, uTalk, Loquala, VieauQc gratuit | [Loquala](https://loquala.com/quebec/) |
| R10 | Frais réels et indemnités kilométriques | 1 | Simulateur officiel, Driversnote, Velvio | [economie.gouv.fr](https://www.economie.gouv.fr/particuliers/impots-et-fiscalite/gerer-mon-impot-sur-le-revenu/impot-sur-le-revenu-tout-savoir-sur-le-bareme-des-frais-kilometriques) |
| R11 | Examen d'admission en ingénieur civil (Belgique) | 2 | prepa-polytech.be, Student Academy, prépas universitaires de 5 à 35 € | [prepa-polytech](https://prepa-polytech.be/) |
| R12 | Test d'aptitude aux études de médecine EMS/AMS en français (Suisse) | 1 | NCWiki gratuit, Les Coachs AMS, matériel officiel gratuit | [NCWiki](https://www.nc-wiki.ch/fr/) |
| R13 | Examens AMF en assurance de dommages (Québec) | 2 | examen-amf.ca (2 000+ questions) et autres | [examen-amf](https://examen-amf.ca/programme/) |
| R14 | Examen de courtier OACIQ | 2 | ITAG, RealtyLicence | [RealtyLicence](https://realtylicence.com/fr/examen-oaciq) |
| R15 | Examen taxi et VTC à Bruxelles | 3 | Examen supprimé en 2023 | [Kyvium](https://kyvium.be/fr/blog/devenir-chauffeur-vtc-bruxelles) |
| R16 | Examen taxi et VTC à Genève | 2 | levtcgenevois à 250 CHF (1 219 questions), Amev à 300 CHF avec app | [levtcgenevois](https://levtcgenevois.com/) |
| R17 | Compteur de 24 h de travail pour étudiants étrangers (Canada) | 1 | Hours Cap (en français et en anglais), outils gratuits de freeusertools | [Hours Cap](https://nextlayertechnology.net/hours-cap) |
| R18 | Attestation SaNa de pêche (Suisse) | 1 | E-learning officiel et catalogue de questions gratuit | [formation-pecheurs.ch](https://www.formation-pecheurs.ch/examen-de-controle) |
| R19 | Permis bateau suisse | 2 | Bootstheorie A+D à 19,95 CHF (en français), app-bootstheorie (en français), BoatDriver, navapp VKS | [app-bootstheorie](https://www.app-bootstheorie.ch/fr) |
| R20 | Diplôme de cafetier genevois | 2 | E-learning SCRHG à 600 CHF (1 500 questions), HEM, patente-restaurant | [SCRHG](https://scrhg.ch/formations) |
| R21 | Code de la route en Polynésie | 3 | Candidats libres suspendus | [service-public.pf](https://www.service-public.pf/dtt/faq/) |
| R22 | Capacité de transport léger de marchandises | 1 et 2 | QCM gratuit, WonderLearn à 20 €/an, formation obligatoire de 105 h | [QCM](https://travail-industrie.com/nos-formations-en-ligne/quizz/qcm-capacite-transport-leger-marchandises) |
| R23 | Agent de gardiennage (Belgique) | 3 | Formation obligatoire de 139 h ; OpenExamPrep gratuit | [OpenExamPrep](https://open-exam-prep.com/practice/be-bewakingsagent-algemeen) |
| R24 | Test des valeurs québécoises (immigration) | 1 | Guide officiel gratuit ; évaluation à livre ouvert ; 50 questions gratuites chez MDPL | [quebec.ca](https://www.quebec.ca/immigration/obtenir-attestation-valeurs/evaluation-en-ligne-attestation-valeurs) |
| R25 | Permis d'agent de sécurité BSP (Québec) | 1 | Canada Exam Prep gratuit (180 questions), ExamHub | [Canada Exam Prep](https://canadaexamprep.com/fr/practice/ca-qc-bsp-security) |
| R26 | Cours canadien de sécurité dans le maniement des armes à feu (CCSMAF/PPA) | 1 | Canada Exam Prep gratuit, ExamHub, FQT | [Canada Exam Prep](https://canadaexamprep.com/fr/practice/ca-cfsc-pal) |
| R27 | Test de perception des risques au permis belge | 2 | Permis Online (100 000+ inscrits), TraficTest | [Permis Online](https://permis.online/perception/formation-perception/) |
| R28 | Tests d'aptitude Basic-Check et Multicheck pour apprentis (Suisse) | 1 et 2 | Démo officielle gratuite, studypeak, ApprentiPrep | [gateway.one](https://www.gateway.one/fr-CH/basic-check-demo.html) |
| R29 | Garde partagée de nounou | 2 | Nounoupay, PaieNounou, Mon Pajemploi (officiel), AssMat Paie | [Nounoupay](https://nounoupay.com/) |
| R30 | Questions écrites du permis poids lourd | 2 | Examen Permis Poids Lourd, 4,6/5 sur 2 900 notes | [App Store](https://apps.apple.com/fr/app/examen-permis-poids-lourd/id1457810171) |
| R31 | Examen infirmier OIIQ | 2 | Inf. de poche, 4,3/5 sur 133 notes, de 24,99 à 99,99 $ ; Nursio ; FocusInfoExa ; oiiqprep | [App Store](https://apps.apple.com/ca/app/inf-de-poche/id1502842597?l=fr-CA) |
| R32 | CE1D (Belgique) | 1 et 2 | edukia, ReviseUp, ce1dsciences gratuit (50 000+ élèves), Khan Academy | [ce1dsciences](https://www.ce1dsciences.be/) |
| R33 | DAEU | 2 et 3 | Préparation universitaire obligatoire ; Sonate à 1 270 € ; CNED | [Lyon 3](https://www.univ-lyon3.fr/daeu-diplome-dacces-aux-etudes-universitaires-option-a-a-distance) |
| R34 | Code de la route expliqué en arabe | 2 | TARIQ à 9,99 €, MADE ECIM, PolyCode (10 000+ téléchargements), Code Auto, Koody | [TARIQ](https://www.tariq-group.com/application) |
| R35 | Code de la route en LSF | 5 | Examen officiel en LSF depuis 2025 ; environ 4 000 candidats sourds par an ; production vidéo en LSF au-delà de 200 € | [Abilitis](https://www.abilitis.fr/2025/07/04/code-de-la-route-desormais-accessible-en-lsf/) |
| R36 | Apprentissage du kabyle | 1 et 2 | Lmed Taqbaylit gratuit, 4,7/5 sur 40 notes iOS ; Tasuqilt, 5,0/5 sur 522 notes ; Dialect ; Targumi | [Play Store](https://play.google.com/store/apps/details?id=com.mycompany.tasukilt&hl=fr) |
| R37 | Langues africaines pour la diaspora | 2 | Jossmo, Afrilangues (10 000+ téléchargements), Sheerpa, Kreyolang, Solola, Minoko | [Jossmo](https://www.jossmo.com/) |
| R38 | Permis bateau belge | 2 | Ecolenautique, Funnautic (1 000+ questions) | [Funnautic](https://www.funnautic.be/question-examen-permis-bateau-belgique) |
| R39 | Permis SAAQ classe 1 | 1 | ExamHub gratuit (150 questions), DriveIQ, formation PESR obligatoire | [ExamHub](https://examhub.ca/fr/quiz/saaq-classe-1) |
| R40 | TECFÉE | 2 | App Pratique TECFÉE (6 000+ utilisateurs), Neurodidacte à 197 $, grammaire.ca | [Pratique TECFÉE](https://pratiquetecfee.com/) |
| R41 | Examens d'admission au secondaire privé (Québec) | 1 et 2 | ExamenAdmission.com gratuit et illimité ; apps Cap Secondaire et « Réussir l'examen d'entrée » ; PDF gratuit de TutorAide ; Tutorat Pro ; SOSprof | [ExamenAdmission](https://examenadmission.com/) |
| R42 | Permis de chasser français | 1 | Chassexam, app officielle et gratuite de la FNC (10 000+ téléchargements) | [Play Store](https://play.google.com/store/apps/details?hl=fr&id=com.fnc.permischasse) |
| R43 | Compteur de télétravail frontalier Luxembourg | 2, hors cible | Telework Tracker | [Telework Tracker](https://teleworktracker.app/) |
| R44 | Examen professionnel de l'Ordre des ingénieurs du Québec | 1 et 3 | Guide d'étude officiel gratuit ; formation obligatoire de 30 h incluse dans le programme d'ingénieur junior (CPI) ; environ 100 QCM, seuil de 60 % | [OIQ](https://www.oiq.qc.ca/futurs-membres/les-examens/examens-professionnels/) |

### Première passe (55)

Les URL ont été relues dans le journal de recherche. Les notes et nombres d'avis ne sont donnés que s'ils avaient été relevés ; sinon, revérifier avant de les citer.

| # | Idée | Motif | Concurrents relevés | Source |
|---|---|---|---|---|
| R45 | Préparation au TCF et au TEF Canada | 2 | TCF Express, Prépa TCF Canada Québec, TCF TEF Canada Quiz, tcftefprep, Canatef | [App Store](https://apps.apple.com/fr/app/tcf-express/id6749838186) |
| R46 | Examen de chasse suisse (romand) | 1 et 2 | App officielle CSF à 17 CHF, 3,5/5 sur 28 notes ; Jagd Lern-App ; passeverytest gratuit | [chasserensuisse.ch](https://chasserensuisse.ch/app/) |
| R47 | Jury central CESS (Fédération Wallonie-Bruxelles) | 1 | Cours gratuits à distance de CapCESS ; ressources officielles de Cesslibre | [CapCESS](https://capcess.be/jury-central/cours-gratuits-distance) |
| R48 | Cours ICAF de chasse (Québec) | 1 | Manuel officiel ; examen de pratique de huntersguide | [huntersguide](https://huntersguide.ca/examen-pratique-chasse-quebec/) |
| R49 | CAP pâtissier | 2 | formationscap, cap-patissier-distance, Nathan, patisserie-online, fiches de courscappatissier | [formationscap](https://www.formationscap.com/cours-cap-patisserie) |
| R50 | CAP cuisine | 2 | caplibcuisine, Artesane | [caplibcuisine](https://www.caplibcuisine.fr/) |
| R51 | CAP boulanger | 2 | Boulangerie pas à pas, formationscap, Exoboulange | [pasapas](https://www.boulangerie-pasapas.com/formations/cap-boulanger-maison/) |
| R52 | ACACED | 1 et 2 | QCM gratuits de zoopro, acaced-facile, quiz-acaced, youschool, maformationanimal | [zoopro](https://www.zoopro.fr/qcm-gratuits-quiz-preparer-acaced-3/) |
| R53 | BNSSA | 1 | QCM gratuits de nageur-sauveteur.com, certoly et sauveteur-aquatique ; app BNSSASwim | [nageur-sauveteur](https://www.nageur-sauveteur.com/qcm-bnssa-ligne) |
| R54 | Galops FFE | 1 et 2 | Chevaloo, quiz de petit-galop, pack Equirider | [petit-galop](https://www.petit-galop.fr/quiz/) |
| R55 | Certificat de radioamateur | 1 et 3 | App d'examen radioamateur ; ANFR | [Play Store](https://play.google.com/store/apps/details?hl=en_US&id=dev.favier.exam1radioamateur) |
| R56 | Théorie ULM | 2 | ulm-theorique.com, aerotheorie, Opaline, espace-formation-ulm | [ulm-theorique](https://www.ulm-theorique.com/) |
| R57 | Permis SAAQ classe 5 | 2 | Quiz SAAQ, 4,9/5 sur environ 20 000 notes ; apps « Examen théorique SAAQ » ; test officiel de la SAAQ | [Quiz SAAQ](https://quizsaaq.ca/?lang=fr) |
| R58 | Permis B belge | 1 et 2 | iThéorie, Permis Free, go-permis gratuit, questions gratuites de toutpourmonpermis | [go-permis](https://go-permis.be/examen-theorique-belge-gratuit) |
| R59 | Test de naturalisation suisse | 2 | testdenaturalisation.ch, naturalisation-switzerland, tests cantonaux officiels | [testdenaturalisation](https://www.testdenaturalisation.ch/fr) |
| R60 | Examen de citoyenneté canadienne | 1 et 2 | ExamHub gratuit, CitizenPass gratuit, Oathly, CitoyenCA, guide IRCC gratuit | [ExamHub](https://examhub.ca/fr/quiz/citizenship) |
| R61 | Examen d'entrée en médecine (Belgique) | 2 | Student Academy, PrépaMed, Prép Médecine, RéussirMédecine, questions officielles gratuites | [Student Academy](https://studentacademy.be/examen-concours-entree-medecine-ou-dentisterie/) |
| R62 | CEB (Belgique) | 1 et 2 | exercices-ceb.be, ReviseUp, PasseCEB | [exercices-ceb](https://exercices-ceb.be/) |
| R63 | ETM moto | 2 | motoetm, Codecodoc moto, Via Learn moto, Pass Rousseau moto | [motoetm](https://motoetm.com/) |
| R64 | SSIAP | 2 | SSIAP 1 QCM, 3,9/5 sur 65 notes ; 250 QCM SSIAP 1 ; certifssiap ; ssiap.pro | [App Store](https://apps.apple.com/fr/app/ssiap-1-qcm-cas-pratiques/id1552699645) |
| R65 | Test fide (Suisse) | 2 | fidepractice, exam-fide, pretaparler, proactif | [fidepractice](https://fidepractice.ch/fr/) |
| R66 | Apprentissage de la LSF | 2 | Pause LSF, 4,8/5 sur environ 3 500 notes ; LSF Reviz ; Signerz | [Pause LSF](https://www.pauselsf.fr/) |
| R67 | Darija pour francophones | 2 | Traducteur Darija, darija.pro, Dialect, Build Baraka | [Dialect](https://www.mydialect.io/apprendre-le-darija) |
| R68 | Diversification alimentaire du bébé | 2 | App Cuisinez pour bébé, « Diversification bébé recettes » | [Cuisinez pour bébé](https://www.cuisinez-pour-bebe.fr/application-mobile/) |
| R69 | Conduite accompagnée | 1 et 2 | My ECF, 4,7/5 sur environ 4 200 notes ; Coach AAC | [App Store](https://apps.apple.com/fr/app/my-ecf/id950330893) |
| R70 | Sommeil du bébé | 2 | Napper, 4,9/5 sur environ 5 200 notes | [App Store](https://apps.apple.com/fr/app/napper-horaires-de-sommeil/id1491340863) |
| R71 | Fluence de lecture | 1 et 2 | Fluence (Hatier), Maître Charlemagne, calculateur facilecture, textes gratuits de parlermoinsvite | [facilecture](https://www.facilecture.fr/outils/calculateur-fluence-lecture/) |
| R72 | Mémorisation de poésies | 1 | Outil gratuit d'outilspourlaclasse, Edukaido, Poemship, Répétir | [outilspourlaclasse](https://outilspourlaclasse.fr/jeux-francais/memorisation-poesie) |
| R73 | Écriture cursive | 2 | J'écris en cursive, 4,5/5 sur environ 670 notes ; Lescapadou ; Kaligo ; Ludigenie | [App Store](https://apps.apple.com/fr/app/j%C3%A9cris-en-cursive-lettres/id1412628587) |
| R74 | Histoires du soir générées par IA | 2 | Skazka, Talu Story, Mes histoires du soir | [Skazka](https://skazka.ai/fr/histoires-audio) |
| R75 | Suivi des injections de GLP-1 | 2 | Shotsy, 4,8/5 sur environ 33 000 notes ; Phaze ; Glapp ; MyTherapy | [Shotsy](https://shotsyapp.com/fr/glp-1-tracker/) |
| R76 | Suivi de la ménopause | 2 | Omena, 4,8/5 sur environ 3 300 notes ; 1001 Ménopause ; Getmenotracker | [Omena](https://www.omena.app/) |
| R77 | Arrêt du porno | 1 et 2 | HoldX, Quitzilla, Resethive gratuit, QUITTR | [App Store](https://apps.apple.com/fr/app/holdx-votre-vie-sans-porno/id6740415414) |
| R78 | Verrouillage du téléphone par la prière | 2 | YouPray, 4,9/5 sur environ 4 500 notes ; Prayer Lock FR ; PrayFocus ; PrayShield ; Sacred Scrolls | [Prayer Lock FR](https://prayer-lock.com/fr/) |
| R79 | Arrêt de la vape | 2 | Puff Count, 4,5/5 sur 168 notes ; Adieu Vape ; Vapeless | [App Store](https://apps.apple.com/fr/app/puff-count-arr%C3%AAter-de-vape/id1488580640) |
| R80 | Rupture amoureuse et « no contact » | 1 et 2 | No Contact, 4,5/5 sur 372 notes ; No Contact AI en français ; compteur gratuit de Ghostedyou | [No Contact AI](https://nocontactai.app/fr) |
| R81 | Gestion de concours de pétanque | 2 | Pétanque Manager, Bouleo, Tournois Pétanque App, Visual Pétanque | [Pétanque Manager](https://www.petanque-manager.com/fr/) |
| R82 | Entretien de piscine | 2 | Poolistry, Simple Pool, Pool-Dex, Poolfu, Clinipool, Poolskey | [Poolfu](https://poolfu.app/fr/) |
| R83 | Carte de territoire de chasse | 2 | MesChasses, HuntGrid | [MesChasses](https://meschasses.com/features/cartographie-cadastre-chasse/) |
| R84 | Suivi de ski | 2 | Slopes, 4,7/5 sur environ 4 900 notes ; Skitude ; Skill.ski | [App Store](https://apps.apple.com/fr/app/slopes-ski-snowboard/id643351983) |
| R85 | Chemins de Compostelle | 2 | Buen Camino (environ 17 600 avis), Camino app, CaminoGo, Via Compostela | [Play Store](https://play.google.com/store/apps/details?hl=fr&id=com.editorialbuencamino.buencamino) |
| R86 | Déclaration de pêche de loisir en mer | 1 | RecFishing, app officielle et gratuite | [DIRM](https://www.dirm.memn.developpement-durable.gouv.fr/l-application-recfishing-est-disponible-a1335.html) |
| R87 | Pêche à pied (mailles et zones) | 1 | Carte interactive gratuite de pecheapied-responsable, ARS | [carte](https://www.pecheapied-responsable.fr/fr/carte-interactive) |
| R88 | Apprentissage des partitions de chorale | 2 | ChoirMate, Choirzone, ressources de chorales | [ChoirMate](https://www.choirmate.com/fr/church-choir-app) |
| R89 | Passage de grades au judo | 1 et 2 | App Judo révision, Dojosystem, référentiel FFJudo gratuit | [Dojosystem](https://www.dojosystem.fr/courses/passage-ceinture-noire-judo/) |
| R90 | Collection de capsules de champagne | 3 | Répertoires papier, projet open source | [répertoire](https://www.bourseducollectionneur.com/product/repertoire-des-plaques-de-muselets-du-champagne-additif/) |
| R91 | Classement de tennis et padel | 1 | Ten'Up officiel, 4,6/5 sur environ 88 000 notes ; simulateurs de classement padel gratuits | [App Store](https://apps.apple.com/fr/app/tenup/id1457871907) |
| R92 | Carnet de tir sportif | 1 | carnetdetir.fr ; dématérialisation FFTir officielle | [carnetdetir](https://carnetdetir.fr/) |
| R93 | Alertes TGV Max | 1 | Apps d'alerte TGVmax, bots open source | [fiche](https://allbestapps.fr/android/tgvmax-alert) |
| R94 | Alertes de logement Crous | 1 et 2 | alertecrous, alerte-logement-crous, CrousAlerte, Telegram, outils open source | [alertecrous](https://alertecrous.com/) |
| R95 | Déchiffrement d'écritures anciennes (paléographie) | 1 | Transkribus (offre gratuite) | [Transkribus](https://www.transkribus.org/fr/paleographie) |
| R96 | Tutelle familiale (comptes de gestion) | 1 et 2 | Tutello (ressource ANCT), Majelis, Proxima | [ANCT](https://lesbases.anct.gouv.fr/ressources/l-application-tutello-fr-l-outils-pour-les-aidants) |
| R97 | Compteur des 120 nuits en location meublée | 1 | Outils gratuits de myhomeit, groume et 120jours.fr | [myhomeit](https://www.myhomeit.fr/outil-compteur-120-nuits) |
| R98 | Estimation d'antiquités par IA | 2 | Antique Value, apps « Identifier antiquité valeur » | [Antique Value](https://antiquevalue.co/fr/) |
| R99 | Journal de bruits de voisinage | 1 et 2 | Noise Log, NoiseProof, Noise Diary (Royaume-Uni) | [Noise Log](https://noise-log.gbapps.company/index.html) |

---

## Incertitudes principales

- Exa n'est pas google.fr. Les absences de concurrents (G02, G05, G06, et l'absence d'app mobile pour G01 et G04) doivent être vérifiées directement dans l'App Store et le Play Store du pays.
- Le nombre annuel de candidats n'est pas sourcé pour le CÉFRANC, la chasse wallonne, l'OQLF, BOSA et le code calédonien.
- Qualité de la correction IA (G01, G03, G04) : elle doit être validée sur des copies réelles avant toute promesse de résultat.
- Les droits de réutilisation des annales officielles (SPW, CÉFRANC) ne sont pas vérifiés. Par défaut, écrire un contenu original.
- Le coût de la voix IA (G03) et de la synthèse vocale néerlandaise (G05) par utilisateur n'est pas mesuré.
