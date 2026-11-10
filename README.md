# Quizmaatje

Een gratis studie-app voor je telefoon.

- **📝 Eigen notities:** plak tekst of upload een PDF of foto. De AI maakt er een samenvatting, een aanvulling en quizvragen van.
- **💡 Quiz over een onderwerp:** typ een onderwerp en kies een niveau. De AI schrijft de studiestof en de vragen zelf.
- **🧠 Lerend vermogen:** de app houdt per begrip bij hoe goed je het kent.
  - Zwakke begrippen komen vaker terug in elke sessie, ook als ze nog niet aan de beurt zijn.
  - Gaat een begrip vaker mis, dan maakt de AI na de sessie automatisch nieuwe vragen die het vanuit een andere hoek toetsen.
  - Onder Voortgang zie je wat je lastig vindt. Daar kun je de AI om uitleg vragen en alleen je zwakke punten trainen.
  - Gaat een begrip een paar keer op rij goed, dan zakt het weg uit je zwakke punten.

## Live zetten (gratis, ±10 min)
1. Maak op GitHub een nieuwe **public** repo, bijv. `quizmaatje`.
2. Upload alle bestanden uit deze map (Add file → Upload files → Commit).
3. Ga naar Settings → Pages → Source: *Deploy from a branch*, kies `main` en `/ (root)`, en klik op Save.
4. Na ±1 minuut staat de app op `https://<jouw-gebruikersnaam>.github.io/quizmaatje/`.

## Op je telefoon
- **iPhone (Safari):** open de link, tik op Deel → *Zet op beginscherm*.
- **Android (Chrome):** open de link, tik op ⋮ → *App installeren* / *Toevoegen aan startscherm*.

## AI-sleutel
1. Ga naar https://aistudio.google.com/apikey en tik op *Create API key* (geen creditcard nodig).
2. Plak de sleutel in de app bij Instellingen en tik op *Test verbinding*.

De sleutel blijft op je eigen telefoon. Hij staat niet in de code en dus ook niet op GitHub.

## Goed om te weten
- Alles (notities, vragen, scores) staat lokaal op je telefoon. Maak af en toe een back-up via Instellingen.
- Op de gratis Gemini-versie mag Google je invoer gebruiken om zijn modellen te verbeteren. Zet er dus geen vertrouwelijke werkdocumenten in.
- Krijg je een fout over limieten of het model? Zet het model bij Instellingen op `gemini-2.5-flash-lite`.

## Bestanden
- `index.html`: de hele app (opmaak en logica)
- `manifest.json`, `sw.js`, `icon-*.png`: zorgen dat het werkt als app op je homescreen, ook offline
