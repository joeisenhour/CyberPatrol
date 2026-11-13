# CyberPatrol

A single-file HTML5 tribute to the classic arcade game Moon Patrol with original pixel art.

**Play it online:** [https://joeisenhour.github.io/CyberPatrol/](https://joeisenhour.github.io/CyberPatrol/)

Or open `index.html` in a browser.

- Two levels and an ending at the Starship.

Controls: Left/Right speed, Up/W/Space jump, Z/X/F fire, M mute, P/Esc pause, Enter start.
Test shortcuts: `?level=2`, `?ending=1`, or press 2 / E on the title screen.

`screenshots/` holds previews; `ref/` holds reference material used for proportions (not used by the game).

## Credits / Licenses

Background music is [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain). Details and original download links are in `music/LICENSES.txt`.

- Title: [Ground Zero](https://opengameart.org/content/ground-zero) by Centurion_of_war (CC0)
- Level 1: [Pure Raceway](https://opengameart.org/content/pure-raceway) by MintoDog (CC0)
- Level 2: [Cyber Runner](https://opengameart.org/content/cyber-runner-music) by ansimuz (Luis Zuno) (CC0)

The tracks load from the `music/` folder over http(s) (including GitHub Pages) and loop on the music bus, under the sound effects. Press M to mute. If the files cannot be loaded — for example when opening `index.html` directly as a `file://` page — the game falls back to the built-in WebAudio chiptune.
