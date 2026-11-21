# Vault Guard identity: architectural drafting sheet
- Palette: blueprint navy #11305c, drafting white #e9f2ff, line cyan #8fc4ff, guard amber #ffb21f, alarm red #ff4636. Result screen only: paper #f3f1e7, with ink navy #0a2347 as shadow and text colour.
- Shape language: one 1.5 px linework weight, lines overshoot their corners like a hand-ruled plan. Top-down guards (circle head, shoulder ellipse, hatched torso), dotted outlines for ghost trails, hatched amber for sight lines, door symbol with a swing arc, crosshair start.
- Texture: faint construction grid tile, feTurbulence displacement (scale 2 to 4) on every line asset, grain overlay at 7 percent, rubber-stamp ink dropout on the CLEARED and ALARM stamps.
- Layout: the play screen is a drawing sheet with a title block at the bottom. Sheet number is the attempt counter, the revision log is the attempt history. The result flips to a printed incident report on paper with tick-box rows.
- Type: Allo, ROND 0. Small caps labels at +0.16em tracking, huge tabular numerals for sheet and score. Logo is hand-built monoline paths, keyhole as the counter of each A. Stamp lettering uses the same stroke alphabet.
- Colour rules: flat fills only. Red text only on dark fills of ink (contrast), never small red on paper.
- Avoid: rounded cards, pills, soft shadows, gradients, emoji or icon-set art, centred single column, typed logo.
- Build: assets generated from a stroke-font script, sprites are 64 box SVGs, guard.svg faces up and is rotated in CSS.
- Test hooks: ?demo=start, ?demo=game, ?demo=sneak, ?demo=end, ?demo=endfail.
