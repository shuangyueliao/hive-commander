# Hive Commander

An original free light-RTS browser game in a single HTML file. Command a bee
swarm in a flower meadow: gather nectar, grow the hive ring by ring, and defend
the queen from wasp raids.

**Play:** https://shuangyueliao.github.io/hive-commander/

## How to play

- Tap a flower → selected bees fly there, sip for 2 s, and carry nectar home automatically.
- Tap a wasp → selected bees intercept it. Drag → box-select workers. `All` selects the whole swarm, `Home` recalls it.
- Honey economy: 5 honey hatches a new worker, 15 honey expands the hive one ring — a bigger foraging territory (double flower yield), more comb HP, and a fresh wax wall.
- Wasp waves attack every ~45 s (20 s prep between waves). Wasps must chew through your wax wall, then the comb, before they can sting the queen — 3 stings and the hive falls, and so does losing every worker.
- Survive all 10 waves to win. Score: surviving bees ×50 + honey ×10 + hive rings ×100. Three maps of rising difficulty.

## Original design notes

All names, mechanics, art (procedural canvas), and audio (WebAudio synthesis)
are original. No third-party IP assets, no external resources, no tracking.

## Tech

Single-file HTML5 (vanilla JS + Canvas + WebAudio, ~50 KB). Platform SDKs load
only on their own domains (CrazyGames / GameDistribution); everywhere else the
file is fully self-contained and works offline once loaded.

## Files

- `index.html` — the game
- `store/` — portal submission materials (description, upload zips)
