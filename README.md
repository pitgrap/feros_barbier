# Fero's Barbier Website

Eine einseitige, scrollbare Business-Website für Fero's Barbier in Braunschweig.

## Struktur
```
feros_barbier/
├── index.html          ← die ganze Seite
├── assets/
│   ├── styles.css
│   ├── script.js
│   └── images/         ← Logo & Fotos vom Laden
└── README.md
```

## Vor dem Veröffentlichen noch ausfüllen
Im `index.html` stehen ein paar Platzhalter, die noch echte Infos brauchen:

- `[TELEFONNUMMER]`: erscheint im Kontakt-Bereich, bitte ersetzen, inkl. `tel:`-Link
- Echte Preise wurden bewusst **nicht erfunden**, bitte in der Leistungen-Sektion ergänzen
- Optional: Instagram-Link ergänzen (aktuell nur Facebook verlinkt)

Einfach mit Strg+F nach `[` suchen, dann findest du alle offenen Stellen.

## Lokal ansehen
Einfach `index.html` doppelklicken und im Browser öffnen, kein Server nötig.

## Auf GitHub Pages hosten (kostenlos)

1. Neues Repository auf GitHub erstellen, z. B. `feros_barbier`
2. Diesen Ordnerinhalt hochladen (entweder per Drag&Drop im Browser oder per Git):
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Fero's Barbier Website"
   git branch -M main
   git remote add origin https://github.com/DEIN-USERNAME/feros_barbier.git
   git push -u origin main
   ```
3. Im Repository zu **Settings → Pages**
4. Unter "Branch" `main` und Ordner `/ (root)` auswählen → **Save**
5. Nach 1–2 Minuten ist die Seite live unter:
   ```
   https://DEIN-USERNAME.github.io/feros_barbier/
   ```

## Später: eigene Domain
Wenn Fero später eine eigene Domain möchte (z. B. `feros_barbier.de`), kann die einfach
bei GitHub Pages unter "Custom domain" eingetragen werden, der Code bleibt gleich.
