# Tide Run identity: pop sticker, ocean blue
- Colours: ground #2f8bff, stripe tint #4a9bff, ink #0b2a66, cream #fff8e6 (card #fffaf0), sand #ffd98a, coral #ff5a5f, sun yellow #ffc93c, flooded water #a9d3ff. Flat fills only.
- Landing and result: broad diagonal stripes (two blues, 64px bands, -32deg) plus faint white dots on a 16px grid. Play screen: flat #2f8bff and one cream card.
- Wordmark "TIDE RUN": Allo 900, ROND 100, opsz 32. Each letter own colour (yellow, coral, cream, sand), small rotation and baseline shift, letters overlap.
- Letter recipe: -webkit-text-stroke .12em in a contrasting inner colour with paint-order stroke fill, then stacked drop-shadow() in ink for the outline (.055em) and a solid drop (.1em).
- Game sprite in the wordmark: a curling wave sticker splashes off the end of the N (assets/wave.svg, own ink outline and solid drop). Tag word "RUN!" tilted -5deg, same recipe.
- Sprites: runner, chest, flag-hill, rock, wave (next to flood), splash (washed away). 64px grid, flat fills, 3.5px ink outline, round joins, 4 colours max, dot eyes, no gloss.
- Board: dry tiles flat sand with 12px corners, flooded tiles flat soft blue with one cream wave mark, coral inset ring on tiles you can step to, countdown number top right.
- Buttons black #111, 10px radius, 56px tall, no text under 14px. Banned: grain, noise, gradients (except hard stripe stops), glow, hatching, offset copies, blur shadows.
- Files: assets/thumb.svg (stripes, dots, embedded PNG of the wordmark), assets/mark.svg (favicon), one SVG per sprite. Test hooks: ?demo=start, game, end, washed.
