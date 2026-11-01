# Redet – nettsiden

Markedsføringssiden for familieappen Redet. Hele siden er `index.html`, pluss App Store-badgen i `bilder/`. Den trenger ingen bygging og henter ingenting fra andre nettsteder (ingen skrifter, bilder eller sporing utenfra).

- **Se den på Macen:** høyreklikk `index.html` i Finder og velg Åpne med → Safari.
- **Publisering:** `.github/workflows/nettside.yml` publiserer siden med GitHub Pages hver gang noe endres på `main`.
- **Navnene** (Ingrid, Jonas, Ida, Emil) er eksempler.
- **App Store-badgen** (`bilder/last-ned-i-app-store.svg`) er Apples offisielle norske, svarte badge og skal ikke endres. Den står i toppmenyen og under prisen.
- **Når appen er godkjent:** søk etter `APP-STORE-LENKE` i `index.html`. Bytt `href="#pris"` og `href="#sporsmal"` på de to badgene med App Store-lenken (f.eks. `https://apps.apple.com/no/app/redet/id1234567890`). Lenken finner du i App Store Connect under appen → App Information → «View on App Store».
- **Farger** er hentet fra temaet Fargeklatt i appen.

Laget av [tillerflatendigital.no](https://tillerflatendigital.no).
