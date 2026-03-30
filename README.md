# 🎴 TCG Queue System - Demo

En demo-version av TCG Live Rip n Ship Queue System för GitHub Pages.

## 🚀 Live Demo

Besök: [`https://nemoo88.github.io/tcg-queue-demo/`](https://nemoo88.github.io/tcg-queue-demo/)

```
## ✨ Funktioner i demon

- ✅ **Admin-panel** med full funktionalitet (lösenordsskyddad)
- ✅ **Flera produkter per order** - Lägg till "2 pack Pika, 3 pack Booster" på samma rad
- ✅ **⏭️ Skjut upp order** - Flytta order till sist i kön (fungerar både för väntande och öppna ordrar)
- ✅ **⏭️ Nästa i kön** - Skjut upp pågående order och öppna nästa automatiskt
- ✅ **🔗 ÖPPNA-knapp** - Öppna vilken order som helst på stream
- ✅ **✕ Ta bort-knapp** - Ta bort order från kön
- ✅ **🕐 Tid sedan** - Se hur länge ordern har väntat
- ✅ **🎉 Events** - Hantera giveaways, duckrace, pack battles (rosa bakgrund)
- ✅ **📺 OBS Overlay** - Visa kön live i din stream
- ✅ **📊 Dynamisk tid** - Systemet lär sig hur snabb du är och uppdaterar estimeringen
- ✅ **🔄 Nollställ statistik** - Börja om med nya siffror (behåller kön)
- ✅ **Automatisk nästa** - Nästa order öppnas när du klickar "Klar - Nästa"

## ⚠️ Begränsningar (Demo)

- Data sparas bara i webbläsaren (localStorage)
- Allt försvinner om du rensar cache eller byter webbläsare
- Ingen Shopify-integration (endast manuell inmatning)
- Ingen permanent lagring

## 🔐 Säkerhet

Admin-panelen är skyddad med lösenord för att förhindra obehörig åtkomst.

**Demo-lösenord:** `demo123`

> 💡 I fullversionen kan du ändra till ett eget lösenord i `admin/index.html`.

## 🎮 Så här använder du demon

1. **Gå till admin-panelen** (`/admin/`)
2. **Logga in** med lösenord: `demo123`
3. **Ladda demo-data** - Klicka på "🎲 Ladda demo-data" för att få test-ordrar
4. **Testa funktionerna:**
   - **⏭️ Skjut upp** - Flytta order längst bak i kön
   - **🔗 ÖPPNA** - Öppna order på stream
   - **✕ Ta bort** - Ta bort order från kön
   - **✓ Klar - Nästa** - Markera klar och gå till nästa automatiskt
5. **Öppna overlay** i ny flik för att se hur det ser ut i OBS

## 🛒 Fullversion

Kontakta för fullversion med:
- 📥 Shopify-integration (automatiska ordrar från din butik)
- 💾 Netlify Blob Storage (permanent lagring)
- 🔒 HMAC-verifiering (extra säkerhet)
- 🎨 Custom anpassning (färger, logo, etc.)

---

**© 2026 TCG Queue System – Demo-version**
