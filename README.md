# IRON DROP · Operation Hundred (Open Beta)

A 100-operator pixel-art military battle royale that runs entirely in your browser. You jump from a transport helicopter with 99 AI operators, loot weapons and gear, survive the shrinking zone and fight to be the last one standing.

**Play:** open `index.html` in any modern desktop or mobile browser. No install, no downloads, no account.

## Features
- Three maps: Ironwood Basin (woodland), Dustfall Province (desert) and Frostline Station (snow)
- 99 bots with their own personalities that loot, flank, take cover, heal, throw grenades and fight each other
- 8 weapons in Standard / Enhanced / Elite rarities, 3 weapon slots, frag and smoke grenades, supply drops
- Helicopter deployment, parachuting, shrinking zone, spectating after death, end-of-match route recap
- 6 cosmetic skins, career stats, XP levels and badges
- Keyboard & mouse, touch controls and gamepad support

## Controls (default, rebindable in Settings)
| Action | Keyboard & mouse | Controller |
|---|---|---|
| Move / aim | WASD / mouse | Left stick / right stick |
| Fire / aim down sights | Left click / right click | RT / LT |
| Reload · pick up · heal | R · E · H | X · A · B |
| Weapons | 1 / 2 / 3, Q or mouse wheel | Y, D-pad |
| Frag · smoke | G · F | LB · RB |
| Sprint · jump/parachute | Shift · Space | L3 · A |
| Map (click to set a waypoint) · pause | M or Tab · Esc | D-pad up · Start |

On phones and tablets: left stick moves, right stick aims and fires, and on-screen buttons handle everything else. Landscape is recommended.

## Hosting on GitHub Pages
1. Create a repository and upload `index.html` (and this README).
2. Go to **Settings → Pages** and choose **Deploy from a branch**, then `main` and `/ (root)`.
3. The game goes live at `https://<username>.github.io/<repository>/`.

## Bug reports
The menu, pause screen and error screen have a **Report a bug** button. It copies technical details to the clipboard.
To make it also open your issue tracker, set `BUG_REPORT_URL` near the top of the script in `index.html`, for example:

```js
const BUG_REPORT_URL = 'https://github.com/<username>/<repository>/issues/new';
```

## Notes
- Matches are offline: every other combatant is an AI bot, and the matchmaking screen is simulated locally.
- Settings, skin choice and career stats are saved in the browser (localStorage).
- Adding `?debug` to the URL exposes a testing handle in the browser console. It is off by default.

## Credits
Game design, code, pixel art, sound and music by the IRON DROP team, all generated in code inside the single `index.html`. It uses no third-party assets or libraries.
