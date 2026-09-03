# Coin Jam Lounge

Final local prototype baseline for the Coin Jam 2D Lounge.

## Run locally
Open `index.html` in a browser.

## GitHub Pages
This package is already structured so `index.html` can be served as the site entry point.

Typical flow:
1. Create a GitHub repository.
2. Upload the contents of this folder to the repository root.
3. Enable GitHub Pages for the repository.
4. Test the hosted lounge.
5. Later multiplayer/client changes can be committed to this same repository.

## Current controls
- A / D or Arrow Left / Arrow Right: move
- Space / W / Arrow Up: jump
- Arrow Down: crouch
- E: bat attack
- Enter: interact
- T: type avatar message
- Enter while typing: post message
- Backspace while typing: edit
- Escape while typing: cancel

## Prototype chat rules
- 25 character maximum
- 13 characters or fewer: 3 seconds
- More than 13 characters: 5 seconds
- Maximum 3 visible posted messages
- Older messages move upward
- New live draft gets the closest line above the avatar

## Important
This build is the approved prototype baseline. Future work should patch forward from this version rather than rebuilding the game from scratch.
