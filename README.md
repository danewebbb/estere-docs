# Estere Docs

Documentazione ufficiale di **Estere**, generata con Jekyll e pubblicata su GitHub Pages.

## Struttura

```
docs/
├── _config.yml              # Configurazione Jekyll
├── _layouts/
│   └── default.html         # Layout HTML unico per tutte le pagine
├── assets/
│   └── css/
│       └── style.css        # Tema custom (IBM Plex, minimal tecnico)
├── index.md                 # Homepage / Panoramica
├── guida-utente/
│   ├── index.md             # Guida utente overview
│   ├── upload-fattura.md    # Come caricare una fattura
│   ├── collegare-fic.md     # Come collegare Fatture in Cloud (OAuth)
│   └── creare-autofattura.md
├── architettura/
│   ├── index.md             # Stack tecnico
│   ├── flusso-dati.md       # Flusso upload → autofattura
│   └── database.md          # Schema tabelle PostgreSQL
├── api-reference/
│   ├── index.md             # Endpoints REST
│   └── fic-integration.md   # Edge Function fic-integration
├── field-mapping/
│   └── index.md             # Mapping Estere → FiC
└── faq/
    └── index.md             # FAQ
```

## Setup GitHub Pages

### 1. Copia la cartella `docs/` nella root del repository

```bash
# Già presente nella root del repo fattureestere
```

### 2. Abilita GitHub Pages su GitHub

1. Vai su **Settings** → **Pages** nel repo `fattureestere`
2. In **Source**, seleziona: `Deploy from a branch`
3. Branch: `main` (o `master`) — Folder: `/docs`
4. Clicca **Save**

### 3. La wiki sarà disponibile su

```
https://danewebbb.github.io/fattureestere/
```

> **Nota:** la prima pubblicazione richiede 1-2 minuti. Le successive si aggiornano automaticamente a ogni push su `main`.

## Aggiungere una nuova pagina

1. Crea un file `.md` nella cartella appropriata
2. Aggiungi il front matter in cima:

```yaml
---
layout: default
title: Titolo della pagina
description: Breve descrizione per SEO
---
```

3. Aggiungi il link nella sidebar in `_layouts/default.html`

## Sviluppo locale (opzionale)

```bash
cd docs
bundle install
bundle exec jekyll serve
# → http://localhost:4000
```
