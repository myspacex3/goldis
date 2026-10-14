# PrimeTV — six localized country ZIPs

One independent ZIP per country, with local language, country-focused IPTV SEO, calling-code default and prices converted from EUR to the local currency. Arabic versions use a right-to-left interface. Canada uses Canadian English and defaults to the Canada option for +1.

Rates: [Currency API daily EUR reference, 13 October 2026](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@2026-10-13/v1/currencies/eur.json). The recorded latest feed reported this reference date when retrieved. A copy is provided in [EXCHANGE-RATES.json](EXCHANGE-RATES.json). Every price is multiplied by the EUR rate and rounded to two decimal places using decimal ROUND_HALF_UP, with local numeric separators and symbol placement. Rates are fixed in the archives and do not update automatically. Each ZIP includes PRICE-CONVERSION.json with the source amount, converted amount and reference rate.

| Country | Language | Currency | 1 EUR | ZIP |
|---|---|---|---:|---|
| United Arab Emirates | Arabic | AED (د.إ) | 4.10406111 | [PrimeTV_Premium_United_Arab_Emirates_AE.zip](PrimeTV_Premium_United_Arab_Emirates_AE.zip) |
| Colombia | Colombian Spanish | COP ($) | 3571.83818375 | [PrimeTV_Premium_Colombia_CO.zip](PrimeTV_Premium_Colombia_CO.zip) |
| Brazil | Brazilian Portuguese | BRL (R$) | 5.57327642 | [PrimeTV_Premium_Brazil_BR.zip](PrimeTV_Premium_Brazil_BR.zip) |
| Argentina | Argentinian Spanish | ARS ($) | 1694.93321508 | [PrimeTV_Premium_Argentina_AR.zip](PrimeTV_Premium_Argentina_AR.zip) |
| Canada | Canadian English | CAD (C$) | 1.59468036 | [PrimeTV_Premium_Canada_CA.zip](PrimeTV_Premium_Canada_CA.zip) |
| Saudi Arabia | Arabic | SAR (ر.س) | 4.19066825 | [PrimeTV_Premium_Saudi_Arabia_SA.zip](PrimeTV_Premium_Saudi_Arabia_SA.zip) |

SEO: localized page titles, descriptions, main headings, structured data and sharing images use country-focused IPTV subscription and package terms. Search volume was not measured; no ranking guarantee is made.

All six versions passed browser checks covering 12 order-price choices each, selection summaries, required validation, resetting, country defaults, menus, FAQ, pricing tabs and seven popups per country. Success and error responses were mocked locally; no real order was sent. The original remote archive resources were blocked during tests, and remote backend behavior was not verified. Arabic phone inputs accept Arabic-Indic and Persian keyboard digits and send the existing ASCII phone representation.

Conversions preserve the source’s separate homepage and order-form price schedules. The price popup matches the homepage. Backend field names and option values, submission endpoint, links, original styles and artwork are retained. An isolated locale stylesheet supplies Arabic RTL and accommodates wider currency amounts. Policy popups remain qualified drafts. Existing country ZIPs were not modified.

Upload the complete contents of the chosen ZIP. Original canonical URLs are retained; configure the actual deployment domain before publication.

[Country CSV](COUNTRIES.csv) · [Manifest, conversions and SHA-256 hashes](MANIFEST.json)
