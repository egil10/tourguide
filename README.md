# Norske Opplevelser - Tour Guide Website

En moderne, responsiv nettsted for en norsk turistguide-tjeneste. Perfekt for GitHub Pages!

## Funksjoner

- 🇳🇴 Fullstendig på norsk
- 📱 Responsivt design + hamburger-meny for mobile
- 🏔️ 6 vakre turer med ekte Unsplash-bilder
- 🎫 Interaktiv **booking modal** med forhåndsutfylt info + bekreftelse
- 🔎 **Søk + filtrering** av turer etter sesong (Sommer / Vinter / Hele året)
- 💬 Nye kundeanmeldelser (testimonials)
- 📧 Forbedret kontakt-skjema med toast-bekreftelse
- 📈 Scroll progress bar + tilbake-til-topp knapp
- 📅 Flytende "Book"-knapp (FAB)
- 🎨 Mye mer polert UI med animasjoner, hover-effekter og bedre tilgjengelighet
- ⚡ Rask og lett - kun én HTML-fil

## GitHub Pages Deployment

For å publisere dette nettstedet på GitHub Pages:

1. Gå til repository-innstillingene på GitHub
2. Naviger til "Pages" i venstremenyen
3. Under "Source", velg "Deploy from a branch"
4. Velg `main` branch og `/ (root)` mappe
5. Klikk "Save"
6. Nettstedet ditt vil være tilgjengelig på: `https://[ditt-brukernavn].github.io/tourguide/`

## Lokal Utvikling

Åpne bare `index.html` i nettleseren din, eller bruk en lokal server:

```bash
# Med Python
python -m http.server 8000

# Med Node.js (http-server)
npx http-server

# Deretter åpne: http://localhost:8000
```

## Nye Funksjoner i Denne Oppdateringen

- **Booking Modal**: Klikk "Book this tour" på hvilken som helst tur for å åpne et pent booking-skjema.
- **Tour Filters**: Filtrer turer etter sesong eller søk på navn/sted.
- **Real Photos**: Alle turer bruker ekte, vakre bilder fra Unsplash.
- **Forbedret UX**: Toast-meldinger, smooth progress bar, back-to-top, og mobilvennlig navigasjon.

## Tilpassing

Du kan enkelt tilpasse nettstedet ved å redigere `index.html`:
- Legg til flere turer i `tours-grid` seksjonen
- Endre farger i CSS `:root` variablene
- Oppdater kontaktinformasjon i kontakt-seksjonen
- Endre booking-logikk eller legg til ekte backend-integrasjon (f.eks. Formspree)

## Lisens

Fritt å bruke og modifisere for egne prosjekter.