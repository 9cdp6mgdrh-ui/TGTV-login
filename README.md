# TGTV – inloggning

Sidan som mobilen öppnar när en TV ska loggas in i TGTV. TV:n visar en kod och en QR-kod. Här
loggar man in (eller skapar ett konto) och anger koden, så loggas TV:n in.

`config.js` innehåller Supabase-projektets adress och publika nyckel. Den nyckeln är gjord för att synas:
datan skyddas av inloggning och radregler i databasen. Inga hemligheter finns i det här repot.

Källan finns i TGTV-appens repo (`login-page/`). Publiceras med GitHub Pages (Settings → Pages →
Deploy from a branch → `main` / root).
