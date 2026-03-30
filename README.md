# 🎴 TCG Queue System - Demo

En demo-version av TCG Live Rip n Ship Queue System för GitHub Pages.

## 🚀 Live Demo

Besök: [`https://nemoo88.github.io/tcg-queue-demo/`](https://nemoo88.github.io/tcg-queue-demo/)

```

## ✨ Funktioner i demon

- ✅ **Admin-panel** med full funktionalitet
- ✅ **Flera produkter per order** - Lägg till "2 pack Pika, 3 pack Booster" på samma rad
- ✅ **⏭️ Hoppa över** - Skjut upp order till sist i kön (både i kön och öppna)
- ✅ **⏭️ Skjut upp öppen** - Skjut upp pågående order och öppna nästa
- ✅ **ÖPPNA-knapp** för alla ordrar (inklusive events)
- ✅ **✕ Ta bort-knapp** för alla ordrar
- ✅ **🕐 Tid sedan** order kom in
- ✅ **Events** med rosa bakgrund (Giveaway, Duckrace, etc.)
- ✅ **OBS Overlay** - Visar kön med både Rip n Ship och Events
- ✅ **Dynamisk tidsberäkning** - Systemet lär sig din takt och uppdaterar estimeringen
- ✅ **🔄 Nollställ statistik** - Behåller kön, nollställer siffror
- ✅ **Automatisk nästa** - Nästa order öppnas vid "Klar - Nästa"

## ⚠️ Begränsningar (Demo)

- Data sparas bara i webbläsaren (localStorage)
- Allt försvinner om du rensar cache eller byter webbläsare
- Ingen Shopify-integration (manuell inmatning)
- Ingen permanent lagring

## 🔐 Säkerhet

Admin-panelen är skyddad med lösenord. För att testa:
- **Demo-lösenord:** `demo123`

I fullversionen kan du ändra till ett eget lösenord i `admin/index.html`.

## 🎮 Så här använder du demon

1. **Gå till admin-panelen** (`/admin/`)
2. **Logga in med lösenord:** `demo123`
3. **Klicka "🎲 Ladda demo-data"** för att få några test-ordrar
3. **Testa knapparna:**
   - **⏭️** - Skjut upp order till sist i kön
   - **ÖPPNA** - Öppna order på stream
   - **✕** - Ta bort order
   - **✓ Klar - Nästa** - Markera klar och öppna nästa automatiskt
4. **Öppna overlay** i ny flik för att se hur det ser ut i OBS

## 🛒 Fullversion

Kontakta för fullversion med:
- Shopify-integration (automatiska ordrar)
- Netlify Blob Storage (permanent lagring)
- HMAC-verifiering (säkerhet)
- Custom anpassning

---

**© 2026 TCG Queue System – Demo-version**
