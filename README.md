# a11a13
Block All IP Addresses that Support Article 11 and Article 13

## Format
This format is made in two steps:
1. IPv4
2. IPv6

Also, using the great MaxMind GEO IP Database (free version): https://dev.maxmind.com/geoip/geoip2/geolite2/

## Usage
Built with Pi-Hole in mind.

## Current Countries in EU
### Use the eu-ipv#-country.txt
| GEONAME_ID | LOCALE_CODE | CONTINENT_CODE | CONTINENT_NAME | COUNTRY_ISO_CODE | COUNTRY_NAME |
| ---- | ---- | ---- | ---- | ---- | ---- |
| 146669 | en | EU | Europe | CY | Cyprus |
| 390903 | en | EU | Europe | GR | Greece |
| 453733 | en | EU | Europe | EE | Estonia |
| 458258 | en | EU | Europe | LV | Latvia |
| 597427 | en | EU | Europe | LT | Republic of Lithuania |
| 660013 | en | EU | Europe | FI | Finland |
| 661882 | en | EU | Europe | AX | Ã…land |
| 719819 | en | EU | Europe | HU | Hungary |
| 732800 | en | EU | Europe | BG | Bulgaria |
| 798544 | en | EU | Europe | PL | Poland |
| 798549 | en | EU | Europe | RO | Romania |
| 935317 | en | AF | Africa | RE | RÃ©union |
| 1024031 | en | AF | Africa | YT | Mayotte |
| 2264397 | en | EU | Europe | PT | Portugal |
| 2411586 | en | EU | Europe | GI | Gibraltar |
| 2510769 | en | EU | Europe | ES | Spain |
| 2562770 | en | EU | Europe | MT | Malta |
| 2623032 | en | EU | Europe | DK | Denmark |
| 2635167 | en | EU | Europe | GB | United Kingdom |
| 2661886 | en | EU | Europe | SE | Sweden |
| 2750405 | en | EU | Europe | NL | Netherlands |
| 2782113 | en | EU | Europe | AT | Austria |
| 2802361 | en | EU | Europe | BE | Belgium |
| 2921044 | en | EU | Europe | DE | Germany |
| 2960313 | en | EU | Europe | LU | Luxembourg |
| 2963597 | en | EU | Europe | IE | Ireland |
| 3017382 | en | EU | Europe | FR | France |
| 3057568 | en | EU | Europe | SK | Slovakia |
| 3077311 | en | EU | Europe | CZ | Czechia |
| 3175395 | en | EU | Europe | IT | Italy |
| 3190538 | en | EU | Europe | SI | Slovenia |
| 3202326 | en | EU | Europe | HR | Croatia |
| 3570311 | en | NA | North America | MQ | Martinique |
| 3578421 | en | NA | North America | MF | Saint Martin |
| 3579143 | en | NA | North America | GP | Guadeloupe |

## Current Cities in EU
### Use the eu-ipv#-city.txt
| To Many To | List |
| ---------- | ---- |
| 58,026 | results |
| Read CITY.md | for more info |
