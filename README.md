# initial d street stage english patch

english fan translation of initial d street stage for the PSP (ULJM-05093).

dialogue, menus, cards, the project d homepage and the in game graphics are all in english. the japanese voice acting is kept.

## what you need

- your own dump of the japanese game, `Initial D - Street Stage (Japan, Asia).iso`
- SHA-256 `55d979a86f207d3b5c5a4272162e90f8e57d76dbcb6a724bd4aecbec564795be`
- the patch from the [releases page](../../releases)

no game files are in this repo. the patch only works on that exact ISO.

## patching

use any xdelta patcher, delta patcher, xdelta ui and xdelta3 all work.

```
xdelta3 -d -s "Initial D - Street Stage (Japan, Asia).iso" "Initial.D.Street.Stage.English.Patched.xdelta" "Initial D Street Stage (English Patched).iso"
```

patched ISO SHA-256 `3abe75eb9b870d52d15e1294565f5902dc5e115a79927efffb799cb9c4967042`

## playing

- PSP, put the patched ISO in the ISO folder on your memory stick and run it with custom firmware like ARK or PRO. it shows up as `Initial D Street Stage (English)` in the game list
- PPSSPP, just open the patched ISO
- saves are shared with the japanese version so your progress carries over
- controls use the japanese layout, circle confirms and cross goes back

## known stuff

- a few menu labels got shortened to fit, like Tsuchi. and Sakamo.
- some small graphics have tiny text because the space is tight
- staff roll names, photos and the logo art stay in japanese
- tested on PPSSPP and on my own PSP

if something clips, reads weird or is still in japanese open an issue with where you were in the game and a screenshot if you can.

## credits

eng tl by moldy094

not affiliated with sega or kodansha.
