# Pixel Quest — YES2 V5: Relic Trail, Music and CVs

## What changed
- Extended town exploration: collect three glowing relics (Water, Grass, Fire), talk to the friendly guide, open Field Journal, or auto-walk to the gym.
- Full original 3v3 YES2 battle, with enhanced hit particles, combat history, defensive turn, type matchup indicators, arena intro and winning confetti.
- Find all 3 relics before the match to unlock an 18% attack-power bonus.
- Two user-uploaded soundtracks: `audio/town-chill.mp3` (extracted from uploaded MP4) and `audio/yes2-battle.mp3` (uploaded MP3). Audio starts only following a player gesture, loops, switches by scene, fades between tracks, and can be muted or adjusted by volume slider.
- CV viewer for original Grace (Water), Nicholas (Grass), Keith (Fire) pages. All 3 CV HTML files remain byte-for-byte unchanged. The external game overlay provides a back button and Lets Connect shortcut; an extra footer with contact links is created in the live iframe at runtime only.
- All known original contact links were taken from supplied CVs. Instagram usernames were not supplied, so no fake accounts have been linked. Add verified Instagram profile URLs once provided.

## How to play
Extract ZIP, then open `pokemon-gym/index.html` in a browser. For the most reliable portfolio iframe behavior and caching, run a local server (`python -m http.server 8000` inside the `pokemon-gym` folder), or deploy to GitHub Pages.

Click START ADVENTURE or EXPLORE MYSELF. Auto-walk follows the path and collects the relics it passes. Manual controls: WASD/arrows to move; E or on-screen A to interact; map/journal buttons are on screen. In the gym select MY PARTY, 3v3 BATTLE, RIVAL LINEUP, TRAINER CARD, or LETS CONNECT. Use moves, heal, guard, or switch to beat the three rivals.

## Publishing and privacy
The supplied audio recordings are from Pokémon soundtrack releases and may be copyrighted; public use may require permission from their respective rights holders. Replace them with licensed tracks if appropriate. Please also obtain consent from the three individuals whose photos, CVs, and contacts appear in the website before public publication. The Nicholas original CV includes a PDF link whose PDF was not among the uploads, so that specific download remains unavailable.

## GitHub Pages
Upload every file and folder inside `pokemon-gym` (including `assets`, `audio`, and `portfolios`) into the repository root, then enable Pages from `main` and `/(root)`.
