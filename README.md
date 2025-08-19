# Sport Fryslân • Productenmatrix High-End (Jekyll)

- **Home**: 8 themaknoppen (automatisch uit collectie) + globale zoekbalk + lijst met alle thema’s
- **/thema/<slug>/**: themapagina met sticky sidebar (navigatie), zoek binnen thema, kaarten + links
- **/product/<slug>/**: detailpagina met breadcrumbs en vaste secties (Hoe aanvragen, Interne route, Voorwaarden, Contact)
- **/product/**: overzicht van alle producten/diensten
- **/thema/**: overzicht van alle thema’s

## Beheer
- Producten aanpassen in `_producten/*.md` (front matter + body secties).
- Thema-pagina’s voor **alle thema’s**; titels komen 1-op-1 uit de Excel in het veld **Thema**.
- Slugs en links zijn robuust (geen speciale tekens in bestandsnamen).

## Live zetten (GitHub Pages)
1. Upload alle bestanden naar de root van je repo.
2. Settings → Pages → Deploy from branch → `main` → `/ (root)`.

## Styling
- Sport Fryslân-stijl (donkerblauw #212945, turquoise #52E8E8, Archivo)
- High-end layout: sticky header, thema-dropdown in de header, sidebar, cards, duidelijke zoekvelden en breadcrumbs.
