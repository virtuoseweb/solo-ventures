# Brief commun aux agents (recherche et vérification)

Date : 22 octobre 2026. Langue : français.

**Client :** un solopreneur français, développeur web et IA (Claude Code, Vercel Pro, agence web). Il veut des business **niches, à vrai besoin, non saturés**, réalisables seul.

**Contraintes :**
- Coût d'entrée ≤ 200 € (comptes stores, domaines, API, tests d'ads).
- Retour sur investissement le plus sûr possible.

## Outil de recherche
- Le quota WebSearch de la session est **épuisé** : utilise **uniquement** `mcp__Exa__web_search_exa`. Charge-le d'abord avec ToolSearch `select:mcp__Exa__web_search_exa,mcp__Exa__web_fetch_exa`.
- Lis une page précise avec `mcp__Exa__web_fetch_exa`.
- Formule des requêtes en français, comme un acheteur français (« application pour … », « logiciel … artisan », « meilleur … 2026 »).
- Exa n'est pas google.fr : signale-le dans les incertitudes. Mais **un concurrent trouvé par Exa est un vrai concurrent**.

## Leçon à appliquer
Une idée avait été validée avec la mention « aucune solution française ». Une seule recherche Exa a trouvé 5 logiciels français qui la couvrent (gestion d'écurie de pension). **Ne jamais écrire « aucun concurrent » sans au moins 3 requêtes formulées différemment** : nom du métier + « logiciel », « application », « gratuit », « outil en ligne ».

## Règles de rejet (une suffit)
1. Un outil **gratuit** équivalent existe, public (service-public, ministère, CAF…) ou privé.
2. **Au moins 3 acteurs français installés** couvrent déjà précisément la niche, sans angle non servi démontrable.
3. **Aucune preuve** que des gens paient ou cherchent : pas de concurrent payant, de modèle étranger avec revenus, de communauté active, ni d'obligation légale.
4. Statut réglementé inatteignable, ou interdiction : rénovation énergétique, CPF, assurance et crédit sans ORIAS, conseil juridique, dispositif médical.
5. Coût d'entrée > 200 €, stock compris.

**Un concurrent payant isolé et peu visible n'est pas un motif de rejet : c'est une preuve de demande.**

## Fiche d'une idée validée (format markdown)
```
### <ID> · <Nom>
- Modèle · Payeur · Prix : …
- Cible / zone : … (villes, départements, secteurs quand c'est utile, et pourquoi)
- Preuve de demande : … [source](url)
- Concurrence vérifiée : 3 requêtes « … » / « … » / « … » → ce qui sort → verdict et angle non servi
- Légal : …
- Coût d'entrée : … € (détail)
- Mini business plan : M1 / M3 / M6 / M12 (trafic ou installs → payants → CA ou MRR), hypothèses explicites, « estim. » sur toute estimation
- Premier test 7 jours + seuil kill : …
- Score /50 : …
```

## CSV
En-tête exact :

`id,famille,nom,modele,zone,payeur,prix,cout_entree_eur,delai_premier_euro_jours,ca_m6_hyp_eur,concurrence,preuve_url,score`

Mets entre guillemets les champs qui contiennent des virgules.

## Interdits
- Utiliser git.
- Modifier les fichiers des autres agents.
- Inventer des chiffres.

## Calibrage v2 (22/10/2026, après la première contre-vérification)
La première passe a tué 129 idées sur 143. Les rejets pour gratuit équivalent, ticket trop faible ou fiche fausse sont justes. En revanche, la règle 2 a parfois été appliquée à la simple **existence** d'un concurrent. Règles précisées :

- **Tue (R1)** : un outil gratuit ou public couvre **le même besoin au même niveau**. Un modèle basique gratuit ne tue pas un produit nettement plus complet **si des ventes payantes du produit complet sont constatées**.
- **Tue (R2)** : un acteur **spécialisé** sur cette niche exacte et cette zone exacte est déjà bien en place (site dédié, contenu complet, avis), **et** aucune faiblesse documentée n'est exploitable. Ne tuent pas à eux seuls :
  - les **généralistes nationaux** (Habitatpresto, Travaux.com, 123devis, StarOfService, AlloVoisins, Hellopro, Malt, Fiverr), puisque notre angle est le lead exclusif local, ou le produit spécialisé ;
  - un concurrent isolé, récent ou peu visible : c'est une **preuve de demande**.
- **Faiblesse exploitable documentée** : mauvais avis (note < 4 ou plaintes récurrentes), prix nettement plus élevé, pas de version française, fonction clé absente, site daté ou lent, zone non couverte. Il faut une URL de preuve.
- **Tue (R6) : ticket trop faible.** Le prix du lead ou la marge doit rester inférieur à environ 20 % du ticket client. Un service doit dégager au moins 30 €/h de travail humain.
- **Tue (R7) : dépendance fatale.** Le modèle est interdit par les CGU de la plateforme dont il dépend (ex. lien de parrainage interdit sur des pages indexées).
