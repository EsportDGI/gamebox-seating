# Gamebox 2027 – Pladsfordeling

Interaktivt værktøj til at fordele og finde pladser. Ren HTML/JS, ingen build eller server.

## Filer
- `index.html` – selve værktøjet
- `data.json` – pladsplan, hold og fordeling (det er den, deltagerne ser)

## Læg det på GitHub Pages
1. Opret et nyt repository på github.com (fx `gamebox-seating`, offentligt).
2. Klik **Add file → Upload files**, træk `index.html` og `data.json` ind, og tryk **Commit changes**.
3. Gå til **Settings → Pages**. Vælg **Deploy from a branch**, branch `main` og mappen `/ (root)`, og tryk **Save**.
4. Efter et par minutter ligger siden på `https://<dit-brugernavn>.github.io/gamebox-seating/`.

## Sådan redigerer du (administrator)
1. Åbn siden med `#admin` i enden, fx `https://<brugernavn>.github.io/gamebox-seating/#admin`.
2. Tilføj hold (navn + antal), og ret manuelt om nødvendigt. Dine ændringer gemmes som kladde i din egen browser.
3. Tryk **Download data.json**.
4. I repoet: **Add file → Upload files**, upload den nye `data.json` (overskriv den gamle) og commit.
5. Siden opdateres for alle efter et minuts tid.

## Gode at vide
- Alle kan åbne siden med `#admin` og lege med den, men ændringer gemmes kun i deres egen browser. Kun den `data.json`, du committer, er synlig for andre.
- Er repoet offentligt, kan alle læse `data.json` med holdnavne. Brug et privat repo eller skån holdnavne, hvis det er et problem.
- Åbner du `index.html` direkte fra din computer, bruger den den indbyggede demo-data i stedet for `data.json`.

## Hallen
Plantegningen af Hal K og logoerne er indlejret i `index.html`, så du kun behøver `index.html` og `data.json`. De 900 pladser (sektion A–I) ligger inden for den røde markering fra haloversigten.
