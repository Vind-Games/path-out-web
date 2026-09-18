# Path Out M1 Greybox — 20-level pack (Web)

**Open on iPhone:** Safari → https://vind-games.github.io/path-out-web/ → tap a boat to sail (Undo top-right).

Greybox: ColorRect boats + Line2D grid (no Kenney/board PNG). Godot 4.7.2, threads OFF.

20-level Harbor Launch pack (`TOTAL_LEVELS := 20`) with redesigned L3 soft-jam teach + mid/spike tune (L9–10 / L16–17). Tap fix: ColorRect `MOUSE_FILTER_IGNORE` + GameController `_unhandled_input` / ScreenTouch fallback.

Source branch: `cursor/milestone-1-harbor-launch-fe2d` @ `66c78f7745678761932a9cbbc12dc13b40b0f927` (NEXT/level-advance fix)

Backup zip: https://github.com/Vind-Games/path-out/releases/tag/debug-sticky-web (`PathOut-m1-web.zip`)  
Local build: `/workspace/path-out-assets/web-levels2/`
