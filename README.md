# freezeclub – Link in Bio (allgemein)

Statische Link-in-Bio-Seite für den **freezeclub Balingen** – im gleichen Design
wie die freeze & talk Podcast-Seite. Hauptfokus: **Probemonat** bewerben.

## Inhalt
- `index.html` – die Seite (self-contained, statisch)
- `assets/` – Logo (weiter unten evtl. `og-image` ergänzen)

## Aufbau
- Header: großes Logo (kein ausgeschriebener Titel)
- Hero: Probemonat-Aktion mit Perks + WhatsApp-CTA
- Einblicke: Foto-Slider (Kältekammer, Lymphdrainage, 3D-Bodyscan, Empfang, Team) – swipe/Pfeile
- Unsere Anwendungen: Kryotherapie, Lymphdrainage, 3D-Körperscan (→ freezeclub.de)
- Termin & Kontakt: Buchung, WhatsApp, Telefon, Anfahrt + Öffnungszeiten
- Über den freezeclub
- Du bist bereits Kunde?: Termin in der App buchen (RemediCool, app.remedi-cool.com/login) + Mehrfachkarte nachkaufen (Shop)
- Mehr entdecken (Podcast, Shop, Website)
- Socials + Footer

## Bilder
Fotos liegen in `assets/`. Slider nutzt `gallery-kaeltekammer.jpg`,
`anwendung-lymphdrainage.jpg`, `anwendung-bodyscan.jpg`, `gallery-theke.jpg`
sowie die Team-Porträts `team-jana.jpg` + `team-marc.jpg`. Die Anwendungs- und
Team-Bilder stammen von der offiziellen Website (onecdn.io, via freezeclub.de).
Das aktuelle Team = Jana & Marc (Einzelporträts von der /uber-uns Seite).

## Hinweis zum Angebot
Der Probemonat-Hero ist als Platzhalter/Wunsch-Aktion gesetzt – vor dem Livegang
Konditionen prüfen. Das reale Einstiegsangebot im Shop ist das **Kennenlern-Angebot
Kryotherapie: 3 Kältekammer-Anwendungen (1 gratis), 39 €**, nur einmal pro Person
einlösbar (Produktlink im Angebots-Streifen unter dem Hero). War beim Anlegen im
Shop als „Ausverkauft" markiert – ggf. Verfügbarkeit prüfen.

## Hosting
Reines HTML/CSS/JS. Live via GitHub Pages im Repo `freezeclub/link` →
**https://freezeclub.github.io/link/** (der Podcast liegt auf der Root, Yoga unter
`/yoga-event/`). Für saubere Link-Vorschauen (WhatsApp/Instagram) noch ein
`assets/og-image.png` (1200×630) hinterlegen – die `og:*`-Tags zeigen bereits auf
`…/link/assets/og-image.png`.
