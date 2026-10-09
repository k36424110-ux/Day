# Footprint BTC Day Trading (multi-bourses)

Site statique : aucun serveur. Le navigateur se connecte directement aux flux publics de Binance Futures, Bybit, OKX et Coinbase.

## Déploiement
1. Nouveau dépôt GitHub avec `index.html`, `render.yaml` et `README.md` à la racine.
2. Render > New > Static Site > ce dépôt. Build command : vide. Publish directory : `.`

## Niveaux affichés (chacun avec sa quantité en $)
- Open, HOD / LOD (plus haut / plus bas du jour, UTC), PDH / PDL (veille)
- VWAP et bandes ±1 écart-type
- VPOC, VAH, VAL (profil de volume 24 h, approximatif)
- Carnet = liquidité en attente à ±25 $ ; Vol 24 h = volume échangé à ±25 $

Outil d'analyse uniquement, pas un conseil financier.
