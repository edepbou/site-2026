# edepartment.nl — de complete website, offline

Open **`index.html`** in een browser. Vanaf daar klikt u door de hele site: menu, links in de
tekst, sectoren, begrippen, downloads. Geen internet nodig, niets installeren.

## Wat erin zit

| | Aantal |
|---|---|
| Pagina's | 292 |
| Waarvan energiebegrippen | 237 |
| Printbare documenten | 14 |
| Eigen foto's | 75 |

De mappen volgen de echte URL's. `energie-inkopen/collectief/index.html` wordt straks
`edepartment.nl/energie-inkopen/collectief`. U kunt de map dus één op één op de server zetten.

| Map | Wat |
|---|---|
| `index.html` | de homepage, hier begint u |
| `energie-inkopen/`, `energiebesparingsplicht/`, `advies-begeleiding/`, `energiemanagement/` | de vier diensten met hun subpagina's |
| `sectoren/` | tien sectorpagina's |
| `energiebegrippen/` | 237 begrippen met zoekfunctie |
| `klantcases/`, `blog/`, `nieuws-inzichten/` | bewijs en artikelen |
| `downloads/` | de veertien printbare documenten |
| `assets/` | foto's, logo's, lettertypen |

## Delen met het team

Zip de map en stuur hem door, of zet hem op een gedeelde schijf. Iedereen die `index.html` opent,
ziet dezelfde site. Verplaats niets binnen de map: pagina's verwijzen naar elkaar met relatieve
paden.

## Als een pagina niet doorklikt

Sommige browsers zijn streng bij bestanden die rechtstreeks van de schijf komen. Werkt iets niet,
dan zijn er twee oplossingen:

1. Open de map in **Firefox** — die is soepeler met lokale bestanden.
2. Of start een kleine lokale server in de map en ga naar het adres dat hij noemt:
   `python3 -m http.server 8000` en dan `http://localhost:8000`.

Optie 2 is ook de eerlijkste voorvertoning: dan gedraagt alles zich exact zoals op de echte server.

## Wat nog niet werkt, en waarom

De formulieren tonen een bevestigingsscherm maar versturen niets. Er is nog geen CRM en geen
mailplatform gekoppeld, en dat is bewust: die keuze staat nog open. Alles wat u ziet en aanklikt
is wel echt.

Ook de veertien downloads zijn echt en print-klaar; twaalf andere documenten worden op de site
wel aangeboden maar bestaan nog niet. Die staan op de werklijst.
