# 🍺 Bryggetidskalkulator

**Bull Balls' Brewery** sin offisielle bryggetidskalkulator – en mobiloptimalisert webapp for å holde styr på alle stegene i bryggeprosessen.

## Funksjoner

**Tidsstyring**
- Skriv inn starttidspunkt, og alle påfølgende klokkeslett beregnes automatisk ut fra hvor lang tid det vanligvis tar i BBB-bryggeri 
- Trykk «Brygg nå»-knappen for å bruke nåværende tidspunkt som start
- Sanntids nedtelling til neste hendelse, oppdateres hvert sekund

**Bryggesteg (standard 5 timer)**
| Steg | Varighet |
|---|---|
| Oppkobling | 5 min |
| Oppvarming | 30 min |
| Mesking | 60 min |
| Temp til utmesk | 15 min |
| Utmesk | 10 min |
| Skylle | 30 min |
| Oppvarming kok | 10 min |
| Kok | 60 min |
| Hopstand | 30 min |
| Nedkjøling | 5 min |
| Gjæringskar | 15 min |
| Vasking | 30 min |

**Fasevisning**
Velg 1, 2 eller 3 faser – hendelsene farges og grupperes for lettere oversikt under bryggedagen.

**Redigerbare varigheter**
Lås opp varighetsfeltene for å tilpasse tidene til ditt brygg. Alle klokkeslett oppdateres øyeblikkelig.

**Varsler**
Varsles 2 minutter før hvert nytt steg med lyd og in-app-alarm. Støtter native nettlesarvarsler der det er tilgjengelig.

> **iPhone:** For push-varsler i Safari må siden legges til på hjemskjermen: trykk Del-ikonet → «Legg til på hjemskjerm», og åpne appen derfra.

**Eksport**
- 📊 **Excel/CSV** – eksporter hele bryggetidsplanen med brygginfo
- 📅 **Kalender (.ics)** – importer til Kalender/Outlook med bryggfaser som separate hendelser

**Brygginfo**
Lagre navn på brygg, bryggere og bryggedato som vises i eksporten.

## Bruk

Appen er en enkeltstående HTML-fil uten avhengigheter – ingen installasjon eller internettilkobling nødvendig.

1. Åpne `index.html` i en nettleser (eller last den opp som GitHub Pages)
2. Trykk «Brygg nå» eller skriv inn starttidspunkt
3. Aktiver varsler hvis ønskelig
4. Bryggesuksess 🍻

## GitHub Pages

For å kjøre appen direkte fra GitHub:

1. Push `index.html` og `bbb-logo.jpeg` til et GitHub-repo
2. Gå til **Settings → Pages**
3. Velg `main`-branch og root (`/`) som kilde
4. Appen er tilgjengelig på `https://<brukernavn>.github.io/<repo>/`

## Filer

| Fil | Beskrivelse |
|---|---|
| `index.html` | Webapp – alt i én fil (HTML, CSS, JS, logo innebygd) |
| `bbb-logo.jpeg` | Bull Balls' Brewery-logo |
| `Bryggetid-vibekode.ods` | Original bryggetidsark (LibreOffice Calc) |
