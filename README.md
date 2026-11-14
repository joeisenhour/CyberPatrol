# CyberPatrol

A single-file HTML5 tribute to the classic arcade game Moon Patrol with original pixel art.

**Play it online:** [https://joeisenhour.github.io/CyberPatrol/](https://joeisenhour.github.io/CyberPatrol/)

Or open `index.html` in a browser.

- Reach the Starship — the mission does not end there.

Controls: Left/Right speed, Up/W/Space jump, Z/X/F fire, M mute, P/Esc pause, Enter start. On a phone, hold it sideways; tap the left half to jump (or toggle thrusters on level 2) and the right half to fire. Tap to start or continue.

`screenshots/` holds previews; `ref/` holds reference material used for proportions. The original photographic enemy face is embedded in `index.html` (cutout and source in `ref/enemy-head.png` and `ref/enemy-head-src.jpg`). A second face (`ref/enemy-head2.png` and `ref/enemy-head2-src.jpg`) is also embedded. Levels 1 and 2 use only the original face.

## Credits / Licenses

Background music is [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain). Details and original download links are in `music/LICENSES.txt`.

- Title: [Ground Zero](https://opengameart.org/content/ground-zero) by Centurion_of_war (CC0)
- Level 1: [Cyber City 2-b](https://opengameart.org/content/warped-city-2) (from Warped City 2) by ansimuz (Luis Zuno) (CC0)
- Level 2 (and later): [Cyber Runner](https://opengameart.org/content/cyber-runner-music) by ansimuz (Luis Zuno) (CC0)

The tracks are embedded in `index.html` (and also kept in the `music/` folder) so they loop on the music bus under the sound effects on GitHub Pages, any http(s) server, and a local `file://` open. Press M to mute.

## Development

Hidden title-screen shortcuts (not shown in the game): press `2` or open `?level=2` for Level 2; press `3` or open `?level=3` to skip ahead later in the game; press `E` or open `?ending=1` for the ending.
