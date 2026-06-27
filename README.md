# Fun Games 🎈

A tiny arcade of colorful games for little kids. No ads, no tracking, no dependencies — just open and play.

**Play it:** https://adam0thman.github.io/donut-sort/

## Games
- **🍩 Donut Sort** (ages ~5–7) — sort the donut towers so each pole holds one flavor. 8 levels, undo / restart / new deal, every level verified solvable.
- **🍓 Yummy Match** (ages ~3–5) — a gentle memory game: tap two cards to find the matching treats. 4 levels that grow from 3 to 8 pairs.
- **🐾 Baby Animals** (ages ~4–7) — see a hand-drawn animal and tap the right baby name (a baby cow is a Calf!). The question is read aloud for pre-readers, with gentle retry-until-right. 11 animals, 8 questions a round.
- **🌍 Flag Quiz** (ages ~6+) — a flag appears and you tap the country it belongs to. The choices grow from 3 to 5 as your streak climbs. Tracks your current streak and your best-ever streak (saved on the device). 24 countries.
- **🔢 Math Quest** (ages ~5–8) — a 24-question math trainer with a progress bar and score. Mixes addition, subtraction, counting pictures, "tap the bigger number", missing numbers, number patterns, and simple times tables, getting harder as you go. Questions are read aloud.

A big friendly **Back** button on every game returns to the game-picker hub. Cheerful sound effects are built in (toggle with the 🔊 button) and work with no audio files — generated with the Web Audio API.

## Pages
| File | What it is |
|------|------------|
| `index.html` | Game-selection hub with tappable cards |
| `donut-sort.html` | Donut Sort game |
| `match.html` | Yummy Match memory game |

## Tech
Three self-contained HTML files — no build step, no libraries, no CDN. All icons and art are inline SVG; all sound is Web Audio. Works fully offline once loaded. Just serve the folder statically.
