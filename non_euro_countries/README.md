# PrimeTV — 8 versions locales avec conversion monétaire

Un ZIP indépendant par pays : langue locale, SEO ciblé, indicatif téléphonique et prix convertis depuis EUR vers la devise locale. Les anciens ZIPs en euros restent inchangés.

Source des taux : [Currency API — 13 octobre 2026](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@2026-10-13/v1/currencies/eur.json). Copie du relevé : [EXCHANGE-RATES.json](EXCHANGE-RATES.json). Chaque montant est multiplié par le taux EUR→devise et arrondi au centième (ROUND_HALF_UP), avec séparateurs et symbole locaux. Les taux et prix sont fixes dans les ZIPs, sans actualisation automatique.

| Pays | Langue | Devise | 1 EUR | ZIP |
|---|---|---|---:|---|
| Tchéquie | Tchèque | CZK (Kč) | 24.37137217 | [PrimeTV_Premium_Czechia_CZ.zip](PrimeTV_Premium_Czechia_CZ.zip) |
| Danemark | Danois | DKK (kr.) | 7.47515463 | [PrimeTV_Premium_Denmark_DK.zip](PrimeTV_Premium_Denmark_DK.zip) |
| Hongrie | Hongrois | HUF (Ft) | 364.882647 | [PrimeTV_Premium_Hungary_HU.zip](PrimeTV_Premium_Hungary_HU.zip) |
| Pologne | Polonais | PLN (zł) | 4.38666401 | [PrimeTV_Premium_Poland_PL.zip](PrimeTV_Premium_Poland_PL.zip) |
| Roumanie | Roumain | RON (lei) | 5.3344448 | [PrimeTV_Premium_Romania_RO.zip](PrimeTV_Premium_Romania_RO.zip) |
| Suède | Suédois | SEK (kr) | 11.20040451 | [PrimeTV_Premium_Sweden_SE.zip](PrimeTV_Premium_Sweden_SE.zip) |
| Royaume-Uni | Anglais britannique | GBP (£) | 0.84520585 | [PrimeTV_Premium_United_Kingdom_GB.zip](PrimeTV_Premium_United_Kingdom_GB.zip) |
| Norvège | Norvégien (bokmål) | NOK (kr) | 10.69683298 | [PrimeTV_Premium_Norway_NO.zip](PrimeTV_Premium_Norway_NO.zip) |

SEO : titres, descriptions, texte principal, données structurées et images de partage localisés pour les recherches liées aux abonnements IPTV dans chaque pays. Les expressions choisies sont naturelles et orientées vers la recherche d’un abonnement ; aucune mesure de volume de recherche ni garantie de classement n’est revendiquée.

Les 8 versions ont été vérifiées dans le navigateur : 12 options de prix par pays, récapitulatif, champs obligatoires, réinitialisation, menus, FAQ, onglets de prix et sept popups. Les succès et erreurs d’envoi ont été simulés localement ; aucune véritable commande n’a été envoyée. Les ressources distantes héritées ont été bloquées pendant les tests ; les services externes n’ont pas été vérifiés en direct.

Les contrôles confirment les conversions, les noms et valeurs envoyées des champs, liens, chemins des ressources, structures HTML, CSS et dimensions des images. Les tarifs d’origine de la page d’accueil et du formulaire diffèrent : chacun est converti indépendamment, et le popup de prix correspond à l’accueil. Les adresses réelles, marques et affiches de films sont conservées. Les projets de politiques restent des projets.

Téléverser le contenu complet du ZIP choisi sur le site. Les URL canoniques d’origine sont conservées ; configurez votre domaine réel au déploiement.

[Tableau CSV](COUNTRIES.csv) · [Manifest, conversions et empreintes SHA-256](MANIFEST.json)
