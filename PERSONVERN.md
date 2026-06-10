# Personvernerklæring — BoligSikt

*Sist oppdatert: juni 2026*

BoligSikt er en Chrome-utvidelse for boligkjøpere som følger boligannonser på Finn.no.
Den er bygget etter ett prinsipp: **dataene dine er dine, og de blir på din maskin.**

## Hva lagres — og hvor

Alt BoligSikt lagrer — boliger du følger, prishistorikk, notater, bud, tagger,
visningsnotater, arkiverte bilder, økonomiske innstillinger (egenkapital, rente,
inntekt, budsjett) og analyser — lagres **lokalt i Chromes utvidelseslagring på din
maskin**. Det finnes ingen konto, ingen innlogging, ingen sky og ingen server hos oss.

Konsekvensen: avinstallerer du utvidelsen, slettes alt. Last derfor ned en backup-fil
i blant (Innstillinger → Data → «Last ned backup-fil»).

## Hva sendes ut av maskinen din

BoligSikt sender **aldri** boligdataene, notatene eller økonomitallene dine noe sted.
Fire eksterne tjenester kontaktes, til avgrensede formål:

| Tjeneste | Hva sendes | Formål |
|---|---|---|
| Finn.no | Vanlige sideoppslag av annonser **du selv** har valgt å følge | Oppdage pris-/statusendringer (automatisk inntil hver 6. time mens Chrome er åpen) |
| SSB (data.ssb.no) | Kommune-/fylkeskode + boligtype — **aldri adresser** | Offentlig prisstatistikk (tabell 06035) |
| OpenStreetMap | Kartfliser for området rundt boligene | Kartvisningen |
| Nominatim (OSM) | **Kun jobbadressen din**, og kun hvis du selv bruker pendleranalysen | Gjøre adresse om til koordinater |
| GitHub (raw.githubusercontent.com) | Et vanlig filoppslag (ingen data om deg) | Hente en statusfil hver 6. time, så vi kan varsle deg hvis Finn endrer formatet |

Som ved alle nettoppslag ser disse tjenestene IP-adressen din. Ingen av dem får vite
hvilke boliger du følger (Finn ser oppslagene, men de er ikke knyttet til noen
BoligSikt-konto — noen slik konto finnes ikke).

## Sporing og analyse

Ingen. BoligSikt har ingen analytics-tjenester, ingen sporingspiksler, ingen cookies
og ingen «telemetri hjem». Den enkle bruksstatistikken du kan se under Statistikk
(antall økter o.l.) lagres kun lokalt og sendes aldri ut.

## Deling du selv starter

«Del»-funksjonen lager en fil/utklippstekst du selv velger å sende til noen. Den
inneholder boligene med historikk, notater, bud og markedsreferanser — men **ikke**
de økonomiske innstillingene dine (egenkapital, inntekt, budsjett, jobbadresse).
Merk at meglers navn/telefon på annonsene følger med i delingen. Backup-filer du
laster ned til deg selv inneholder alt, inkludert innstillinger.

## Feilrapporter

«Rapporter problem» åpner et e-postutkast i din egen e-postklient, forhåndsutfylt med
teknisk info (annonse-URL, versjon, parse-status). **Ingenting sendes før du selv
trykker send.** E-poster vi mottar brukes kun til feilsøking og slettes når saken er
løst.

## Dine rettigheter og sletting

Siden alt ligger lokalt hos deg, har du full kontroll: eksporter alt (Innstillinger →
Data), slett enkeltboliger, eller slett alt (Innstillinger → Faresone, og/eller
avinstaller utvidelsen). Vi kan ikke se, endre eller slette dataene dine — vi har dem
ikke.

## Kontakt

Spørsmål om personvern: **bragejonassen.28@gmail.com**

Endringer i denne erklæringen varsles i utvidelsens endringslogg.
