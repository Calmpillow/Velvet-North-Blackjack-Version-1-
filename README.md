# Velvet North — Character Studio Refresh

This refresh updates the character customization interface while preserving the existing game files and game flow.

## Character customization
- Live avatar preview.
- Masculine/feminine presentation toggle.
- Eight skin tones.
- Hair, shirts, hats, glasses, chains, and necklaces.
- Choose a style shape and then its color independently.
- Every appearance option is free; no purchase or currency flow is connected to customization.
- Optional accessories can be removed.
- Random look and save character controls.
- Saved appearance remains on the current device using localStorage.

## Files
- `index.html` — page structure and customization controls.
- `style.css` — refreshed character studio layout and responsive styling.
- `game.js` — character catalog rendering, selection, preview, and persistence.

## Validation
`game.js` passes `node --check`. The project should still be tested in a browser on desktop and mobile before publishing.

## Unequip controls
- Hats, glasses, chains, and necklaces can be unequipped and re-equipped at any time.
- Hair can be removed completely; choosing a hair style or color equips it again.
- Clothing keeps a starter outfit equipped for a dressed character; the action restores that starter outfit rather than leaving the avatar without clothing.
- Unequipped state is reflected in the live preview and is saved with the character.
