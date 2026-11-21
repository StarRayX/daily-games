# Vault Guard identity: sticker pop
- Colours: ground grape #7a4dff, stripe tint #8a62ff, ink #22105c, cream #fff6e8, card #fffaf0, gold #ffc93c, pink #ff6eb4, mint #3ad6a0.
- Landing and result: broad diagonal stripes (grape and tint) plus a faint grid of small white dots. Play screen: flat grape, one cream card, black rectangular buttons (radius 10).
- Wordmark: VAULT / GUARD in Allo 900, ROND 100, opsz 32. Every letter its own colour, small bounce and rotation, letters overlap, coloured inner outline (text-stroke, paint-order stroke fill), dark ink outline and solid drop from stacked drop-shadow. The A of VAULT is a round vault door sprite with a cream A on it.
- Tag word: SNEAK! in cream with a gold inner outline, tilted -6 degrees, same ink outline and drop. The thief sticker sits beside it.
- Sprites: flat fills, at most 4 colours, 3.5 px ink outline, round joins, dot eyes, no gloss or gradients. guard.svg and guard-ghost.svg face up and are rotated in CSS. thief, door (exit), start, vault-disc, alarm (caught), cleared.
- Guard vision is a flat soft yellow tile tint. Route is a dotted pink line with numbered pink dots. Dark dots mean a known guard watches that tile on that step. Ghost guards are the guard sticker at 50 percent opacity with step labels.
- Rules: no grain, no texture, no gradients, no glow, no offset copies. Only shadow is the solid ink drop on wordmark and tag. No text under 14 px.
- Test hooks: ?demo=start (default), ?demo=game, ?demo=sneak, ?demo=end, ?demo=endfail.
