# Leading AI · Builders & Leaders

Een interactief dashboard dat de meerwaarde toont van het 10-weekse leerlijn-traject **Leading AI: Builders & Leaders** voor Avans, het MKB, studenten, expertbedrijven en strategische partners in West-Brabant.

Onderdeel van het project Data & AI / LLO-Katalysator (ABE · ORM).

## Bestanden

- `index.html` — De volledige website (single-page, geen build-stap nodig)
- `netlify.toml` — Configuratie voor Netlify deployment
- `.gitignore` — Standaard ignore-regels voor Git

## Hoe zet je dit live via GitHub + Netlify?

### Stap 1 — Upload naar GitHub

1. Maak een nieuwe repository aan op [github.com/new](https://github.com/new) (bijvoorbeeld `leading-ai-dashboard`)
2. Pak deze zip uit op je computer
3. Open een terminal in de uitgepakte map en voer uit:

```bash
git init
git add .
git commit -m "Initial commit: Leading AI dashboard"
git branch -M main
git remote add origin https://github.com/JOUW-USERNAME/leading-ai-dashboard.git
git push -u origin main
```

(Vervang `JOUW-USERNAME` door je eigen GitHub-gebruikersnaam.)

**Geen ervaring met de terminal?** Je kunt de bestanden ook gewoon via de GitHub-website uploaden: klik op "uploading an existing file" op de lege repository-pagina en sleep alle bestanden uit de zip erin.

### Stap 2 — Koppel Netlify

1. Ga naar [app.netlify.com](https://app.netlify.com) en log in (of maak een gratis account)
2. Klik op **"Add new site" → "Import an existing project"**
3. Kies **GitHub** en autoriseer Netlify
4. Selecteer je `leading-ai-dashboard` repository
5. De build-instellingen worden automatisch overgenomen uit `netlify.toml` — klik op **"Deploy site"**

Je site is binnen ~30 seconden live op een willekeurige URL zoals `https://wonderful-octopus-12345.netlify.app`.

### Stap 3 — (Optioneel) Eigen domein

In Netlify onder **"Domain settings"** kun je een eigen domeinnaam koppelen of de standaard URL hernoemen naar bijvoorbeeld `leading-ai-avans.netlify.app`.

## Aanpassingen maken

Omdat het een single-file website is, kun je gewoon `index.html` openen in een teksteditor (VS Code, Sublime, of zelfs Notepad) en wijzigingen maken. Push de wijziging naar GitHub en Netlify deployt automatisch opnieuw.

## Contact

Janne Toonen · Avans Hogeschool · ABE / ORM
