# Path Out M1 Greybox — iPhone Safari (Web)

**Open on iPhone:** Safari → https://vind-games.github.io/path-out-web/ → tap a boat to sail (Undo top-right).

Greybox: ColorRect boats + Line2D grid (no Kenney/board PNG). Godot 4.7.2, threads OFF.

Tap fix: ColorRect `MOUSE_FILTER_IGNORE` + GameController `_unhandled_input` fallback.

Backup zip: https://github.com/Vind-Games/path-out/releases/tag/debug-sticky-web (`PathOut-m1-web.zip`)  
Local build: `/workspace/path-out-assets/web-greybox2/`
