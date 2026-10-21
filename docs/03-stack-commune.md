# Stack commune : une usine, plusieurs business

Règle : **une nouvelle niche = un fichier de config + du contenu, jamais un nouveau code**. Le temps IA sert à produire et relire du contenu exact, pas à recoder.

## Monorepo proposé
```
apps/
  lead-sites/        # Astro : un build par (niche × département) via variables d'env
  hub-facturation/   # V01 Astro + îlots React (diagnostic, comparateur)
  checkin/           # V03 Next.js ou Astro SSR + Vercel Cron + webhooks SMS
  convertisseur/     # V04 Next.js + file d'attente d'extraction
packages/
  lead-engine/       # simulateur de devis générique, consentement, routage vers l'acheteur
  seo-kit/           # pages programmatiques, JSON-LD, sitemap, maillage interne
  legal-kit/         # mentions légales, CGU/CGV, page « fonctionnement du classement », bandeau affiliation
  data/              # communes INSEE, départements, métiers, programmes d'affiliation (JSON versionnés)
niches/
  assainissement.json, elagage.json, ramonage.json, old.json, frelons.json …
```

## Briques et coûts
| Besoin | Choix | Coût |
|---|---|---|
| Hébergement | Vercel Pro (déjà payé), 1 projet par venture, domaines multiples sur `lead-sites` | 0 € en plus |
| Base de données | Neon ou Supabase (offre gratuite au départ) | 0–25 €/mois |
| Formulaires → acheteur | Webhook → e-mail (Resend) + SMS (Brevo / OVH) à l'artisan, preuve de consentement horodatée en base | ≈ 0,05 € par lead |
| Paiement | Stripe (Payment Links, Billing) ; facturation des artisans : Stripe Invoicing | % par transaction |
| Analytics | Vercel Analytics + Search Console + Plausible si besoin | 0–9 €/mois |
| Suivi d'appels (rank & rent) | Numéro virtuel par site (OnOff, Aircall, Twilio) : le numéro reste à nous | 3–10 €/mois par site |
| Domaines | .fr ≈ 7–10 €/an | ≈ 10 € par site |

## Points de qualité non négociables
- Chaque page programmatique a une **donnée propre et vérifiable** (prix local, réglementation départementale, liste d'acteurs) : c'est ce qui la fait citer par les AI Overviews et la protège des pénalités pour contenu de faible valeur.
- Relecture humaine des 10 premières pages de chaque niche ; ensuite, contrôles automatiques (chiffres sourcés, pas de promesse d'aide publique).
- Consentement : case non précochée, nom de l'acheteur affiché, horodatage, IP, texte exact du consentement conservés 3 ans.
