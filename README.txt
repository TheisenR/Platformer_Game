Escape the Academy — MVP
=========================

HOW TO PLAY
-----------
Open index.html in any modern web browser (double-click it, or drag it
into a browser window, or open it on your phone). No installation or
server is required — it's fully self-contained.
(An internet connection is needed the first time it loads, since it
pulls in the Phaser game engine and two Google Fonts from public CDNs.)

WHAT'S INCLUDED
----------------
- index.html                 The complete game (HTML + CSS + JavaScript).
                              This is the only file you need to run.
- hero-sprite-source.piskel   The original Piskel source file for the
                              player character's walk-cycle sprite, kept
                              here for reference / future editing in
                              piskelapp.com or the Piskel desktop app.
- README.txt                  This file.

CONTROLS
--------
Desktop:
  Move:   Arrow keys or A / D
  Jump:   Up arrow or Space
  Pause:  ESC
  Mute:   M (or click the speaker icon)

Mobile / touch:
  On-screen buttons appear automatically in the corners of the game
  (left / right / jump / pause).

FEATURES
--------
- 4 levels ("wings") with a level-select screen that unlocks as you clear each one
- Coins, a key-and-portal exit puzzle per level, and a stomp-to-defeat enemy mechanic
- Two enemy types (ground patrol Warden + flying Proctor), moving bonus platforms
- Power-ups: extra life, temporary shield, speed boost
- Procedurally generated chiptune music + sound effects (no external audio files)
- Custom player sprite (your uploaded walk-cycle art)
- Mobile-friendly touch controls
- Progress and best scores are saved locally in your browser (localStorage)
- All level layouts are physics-verified so every level is completable —
  the ground-and-pits path to the exit portal never requires platforming;
  only the key does, via a short, safely-jumpable staircase.

EDITING
-------
Everything is in index.html — open it in any text/code editor to tweak
level layouts (see the LEVELS array near the top of the <script> block),
difficulty, colors, or add more levels. A small on-page diagnostic log
box (below the game) will show boot progress and any errors if something
ever fails to load, to help with troubleshooting.
