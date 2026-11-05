# Hive Commander — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Command a bee swarm: gather nectar, expand the hive ring by ring, and hold the
wax wall against wasp raids. Survive 10 waves and the queen reigns supreme.

(195 characters)

## Details

- Genre: Strategy / Casual / Light RTS
- Controls: Mouse / Touch. Tap a flower to send the swarm gathering (2 s per
  load, auto return trip), tap a wasp to intercept, drag to box-select.
  Buttons: All (select swarm), Home (recall), Hatch (5 honey), Expand
  (15 honey). Keyboard shortcuts: A / H / B / E.
- Features:
  - Swarm command: box-select and point-and-click orders, units avoid each other
  - Economy loop: flowers refill over time; flowers inside your territory yield double
  - Hive growth: each expansion ring adds territory radius, comb HP and wax segments
  - Defense layers: guard-wax wall (raiders chew 2 s per segment, it regrows), comb HP buffer, the queen herself
  - Wasp AI: hunts gatherers, besieges the hive, gives up hopeless chases, flees after stinging
  - Giant wasps from wave 4 (double HP, triple honey drop)
  - 3 maps (Casual / Standard / Hard) with different flower layouts and raid directions
  - Win by surviving 10 waves; score = bees ×50 + honey ×10 + rings ×100; best score saved locally
- Tech: Vanilla JavaScript, Canvas (all graphics procedural), WebAudio (all
  sound synthesized, swarm hum scales with bee count). Single-file HTML5, no
  external assets, no tracking, works offline once loaded.

## Tags

rts, strategy, bees, swarm, defense, casual, honey, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas letterbox-scales, portrait hint shown)
- [x] No external links inside gameplay, no analytics
- [ ] Cover 16:9 (1280×720) — screenshot the meadow with the swarm mid-gather
- [ ] Screenshots — one combat shot with wasps, one hive-expansion shot

## GameDistribution
- Upload `hive-commander-gd.zip` (contains only index.html)
- The GameDistribution SDK script loads only on gamedistribution / gd.games domains

## itch.io
- Upload `hive-commander-itch.zip`, mark "This file is playable in browser",
  entry file: index.html, kind: html, viewport: any (canvas letterboxes to fit)
- Pricing: $0 (donations optional)
