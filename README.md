# 🎴 TCG Queue System - Demo

En demo-version av TCG Live Rip n Ship Queue System.

## 🚀 Live Demo

Besök: [https://nemoo88.github.io/tcg-queue-demo/](https://nemoo88.github.io/tcg-queue-demo/)

## 📁 Filer

```
├── index.html          # Välj språk
├── index-en.html       # Choose language
├── admin/
│   ├── index.html      # Köhanteraren (svenska)
│   └── index-en.html   # Queue Manager (English)
└── overlay/
    └── index.html      # OBS Overlay
```

## 🔐 Inloggning

**Lösenord:** `demo`

Visas på inloggningssidan.

## ✨ Funktioner

- ✅ **Köhantering** - Se och hantera alla ordrar
- ✅ **Flera produkter per order** - Lägg till flera produkter på samma rad
- ✅ **⏭️ Skjut upp order** - Flytta order till sist i kön
- ✅ **ÖPPNA-knapp** - Öppna order på stream
- ✅ **✕ Ta bort-knapp** - Ta bort order från kön
- ✅ **Tid sedan** - Se hur länge ordern väntat
- ✅ **Events** - Hantera giveaways, duckrace, pack battles
- ✅ **OBS Overlay** - Visa kön live i din stream
- ✅ **Dynamisk ETA** - Systemet lär sig hur snabb du är och uppdaterar estimerad tid
- ✅ **Nollställ statistik** - Börja om med nya siffror

### 🕐 Dynamisk tid/ETA

Systemet lär sig automatiskt hur lång tid du behöver per order:

- **Hur det fungerar:** När du markerar en order som "Klar", registreras tiden det tog
- **Snitt beräkning:** Systemet sparar de 20 senaste tiderna och räknar ut ett snitt
- **Vad påverkas:** Endast "Klar - Nästa" registrerar tid. Att skjuta upp en order påverkar inte snittet.
- **ETA i overlay:** `(antal ordrar) × (snitt tid) = estimerad tid kvar`
- **Startvärde:** 5 minuter per order innan systemet lärt sig ditt tempo

Exempel: Om snittet är 3 minuter och du har 4 ordrar i kön → ETA: 12 minuter

## ⚠️ Begränsningar (Demo)

- Data sparas bara i webbläsaren (localStorage)
- Allt försvinner om du rensar cache eller byter webbläsare
- Ingen Shopify/Ecwid/Quickbutik-integration (endast manuell inmatning)

## 🎮 Snabbstart

1. Gå till köhanteraren (`/admin/`)
2. Logga in med lösenord: `demo`
3. Ladda demo-data
4. Testa funktionerna!

## 🛒 Fullversion

Fullversion inkluderar:
- **Shopify**-integration (automatiska ordrar via webhook)
- **Ecwid**-integration (automatiska ordrar via webhook)
- **Quickbutik**-integration (polling var 30:e sekund)
- Netlify Blob Storage (permanent lagring)
- Docker-version för lokal hosting
- Server-side lösenordsskydd
- Anpassningsbar design (ändra färger, storlekar i CSS)

---

**© 2026 TCG Queue System – Demo-version**
