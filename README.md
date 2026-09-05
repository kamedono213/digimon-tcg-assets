# digimon-tcg-assets

Card art asset store for the [digimon-tcg](https://github.com/) prototype game.

This repo holds only images, served via [jsDelivr](https://www.jsdelivr.com/)
(`https://cdn.jsdelivr.net/gh/<owner>/digimon-tcg-assets@main/...`). It has no
game code and no game data.

Every file name embeds a content hash (`<key>.<hash>.<ext>`), so if an image
is ever replaced, its filename - and therefore its URL - changes too. That
means these files can be cached forever by clients and by the CDN without
any risk of serving a stale image after an update.

- `art/` - card illustrations and UI icons (from the game's `ART` table)
- `legend/` - legend-summon cut-in illustrations (from `LEGEND_CUTIN_ART`)
