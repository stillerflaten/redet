# Redet – nettsiden

Markedsføringssiden for familieappen Redet. Hele siden er `index.html`, pluss App Store-badgen i `bilder/`. Den trenger ingen bygging og henter ingenting fra andre nettsteder (ingen skrifter, bilder eller sporing utenfra).

- **Se den på Macen:** høyreklikk `index.html` i Finder og velg Åpne med → Safari.
- **Publisering:** `.github/workflows/nettside.yml` publiserer siden med GitHub Pages hver gang noe endres på `main`.
- **Navnene** (Ingrid, Jonas, Ida, Emil) er eksempler.
- **App Store-badgen** (`bilder/last-ned-i-app-store.svg`) er Apples offisielle norske, svarte badge og skal ikke endres. Den står i toppmenyen og under prisen.
- **App Store-lenken** er https://apps.apple.com/no/app/id6827096660 (Apple ID 6827096660). Den står på de to badgene (søk etter `APP-STORE-LENKE` i `index.html`) og i spørsmålet «Hvor laster jeg ned Redet?». Taggen `apple-itunes-app` øverst i `index.html` gir Safari på iPhone et banner med «Åpne»/«Last ned».
- **Farger** er hentet fra temaet Fargeklatt i appen.

Laget av [tillerflatendigital.no](https://tillerflatendigital.no).
