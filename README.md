# Oberschule Am Sportzentrum Riesa – Website

Statische Website der Oberschule Am Sportzentrum Riesa (ASZ Riesa), gehostet via Netlify.

## Struktur

```
Website/
├── netlify.toml                  # Netlify-Konfiguration
├── cms.sachsen.schule/           # Publish-Verzeichnis
│   ├── asz-riesa/                # Alle HTML-Seiten
│   │   ├── start.html
│   │   ├── bilder.html
│   │   ├── schulprofil.html
│   │   ├── schulinfos.html
│   │   ├── termine.html
│   │   ├── mitwirkung.html
│   │   ├── foerderverein.html
│   │   ├── kontakt.html
│   │   ├── impressum.html
│   │   ├── datenschutz.html
│   │   ├── barrierefreiheit.html
│   │   └── archiv.html
│   └── fileadmin/                # Bilder & Medien
│       ├── _processed_/          # Logos
│       └── _special/             # Uploads & Fotos
```

## Deployment

Die Website wird automatisch via [Netlify](https://netlify.com) deployed.

- **Publish-Dir:** `cms.sachsen.schule`
- **Startseite:** `/asz-riesa/start.html`
- Kein Build-Schritt nötig (statisches HTML)

## Lokal öffnen

Einfach `cms.sachsen.schule/asz-riesa/start.html` im Browser öffnen,  
oder einen lokalen Server starten:

```bash
npx serve cms.sachsen.schule
```