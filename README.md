# Fun Games 🎈

A tiny arcade of colorful games for little kids. No ads, no tracking, no dependencies — just open and play.

**Play it:** https://adam0thman.github.io/donut-sort/

## Games
- **🍩 Donut Sort** (ages ~5–7) — sort the donut towers so each pole holds one flavor. 8 levels, undo / restart / new deal, every level verified solvable.
- **🍓 Yummy Match** (ages ~3–5) — a gentle memory game: tap two cards to find the matching treats. 4 levels that grow from 3 to 8 pairs.

A big friendly **Back** button on every game returns to the game-picker hub. Cheerful sound effects are built in (toggle with the 🔊 button) and work with no audio files — generated with the Web Audio API.

## Pages
| File | What it is |
|------|------------|
| `index.html` | Game-selection hub with tappable cards |
| `donut-sort.html` | Donut Sort game |
| `match.html` | Yummy Match memory game |

## Tech
Three self-contained HTML files — no build step, no libraries, no CDN. All icons and art are inline SVG; all sound is Web Audio. Works fully offline once loaded. Just serve the folder statically.
