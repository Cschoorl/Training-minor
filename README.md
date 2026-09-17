# Training Minor

## Van idee naar iets dat bestaat — slidedeck

**Live:** https://cschoorl.github.io/Training-minor/

HTML-slidedeck voor de sessie over het omzetten van een idee in actie,
zichtbaarheid en tractie, met Back to Being als praktijkvoorbeeld.
Achttien slides: eerst het verhaal van de actie, dan drie etappes: **mensen** (Caesar), **verhaal** (Max) en
**lancering** (Stijn).

Zelfstandig bestand, geen build, geen dependencies. Gehost via GitHub Pages
vanaf deze branch.

| Toets | Actie |
|---|---|
| `→` `←` `spatie` `PgUp/PgDn` | Navigeren |
| `Home` / `End` | Eerste / laatste slide |
| `N` | Sprekersnotities tonen of verbergen |
| `F` | Volledig scherm |

De stippen in de linkerkantlijn zijn klikbaar om direct naar een slide te
springen. Printen naar PDF geeft één slide per pagina.

## Autoschade-app

**Live:** https://cschoorl.github.io/Training-minor/car-damage/

Telefoon-app om schade per auto bij te houden. Elke auto wordt herkend aan
het kenteken. Per auto staat een simpele zijaanzicht-tekening; tik op een
plek om schade toe te voegen met een foto, en tik op een rode stip om die
foto terug te zien.

- Kenteken invullen → auto openen (bestaat de auto al, dan zie je meteen de
  bekende schades).
- **Schade toevoegen** → tik op de tekening → foto maken of kiezen → notitie →
  opslaan.
- Werkt als installeerbare web-app: open de link op je telefoon en kies
  *Zet op beginscherm* (iPhone: deel-knop; Android: menu → *App installeren*).
  Daarna werkt hij ook zonder internet.
- Alle gegevens en foto's staan alleen op de telefoon zelf (IndexedDB); er is
  geen server. Taal NL/EN via de knop rechtsboven.

Ook hier: één bestand, geen build, geen dependencies.

### Bestanden

- `index.html` — het deck
- `preview.png` — afbeelding voor het linkvoorbeeld bij delen
- `back-to-being/` — doorverwijzing van de oude URL naar de hoofdpagina
- `car-damage/` — de autoschade-app (`index.html`, `manifest.webmanifest`,
  `sw.js` voor offline gebruik, iconen)
