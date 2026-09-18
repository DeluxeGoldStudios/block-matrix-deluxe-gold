# BLOCK MATRIX — Deluxe Gold Mobile Showcase

A browser-based falling-block puzzle game from **Deluxe Gold Studios**, with touch controls for phones and tablets. The same buttons also work with a mouse on a laptop or desktop.

## Play

[Open the mobile game](./mobile.html) from the published showcase site. GitHub's repository file viewer shows HTML source; use the **GitHub Pages** address to play.

No installation, account, build command or Electron runtime is required. The game is a standalone HTML file with embedded artwork and generated audio.

## Controls and layout

The on-screen controls remain available during gameplay in this edition, including when using a mouse.

| Button | Action |
| --- | --- |
| Left / Right | Move; hold to repeat |
| Curved arrow | Rotate clockwise |
| Down | Soft drop; hold to repeat |
| Drop | Hard drop to the ghost position |
| Hold | Store or exchange the falling piece |
| Pause | Pause the game |
| Help | Open How to Play |

On wider landscape screens, the action buttons sit close to the left of the pit and movement buttons close to its right. Portrait uses controls below the board. The compact information panel shows coloured **Next** and **Hold** previews. Controls dim and stop responding during popups; use the popup's own Resume or Close button.

**Hold** saves a useful piece until you need it. If a piece is already stored, Hold exchanges it with the falling piece. You can use Hold once per placement; place the incoming piece before using Hold again.

Keyboard controls remain available: arrows move and soft drop; Up/X rotates clockwise, Z counterclockwise, Space hard drops, C holds, P pauses, O opens Options, M opens the menu and F toggles fullscreen. Compatible gamepads are also supported by the game.

## Game modes

- **Campaign:** always starts at Level 1. Finish the line target and clear all marked excavation cells to advance through ten sectors.
- **Practice Level:** choose any of the ten excavation layouts and complete that sector's objectives.
- **Free Play:** starts with an empty board and no pre-placed excavation blocks. The selected level sets the starting speed and environment.

How to Play includes the block guide, Hold explanation and mode rules.

## Defaults, music and saved settings

Defaults are Campaign, Level 1, Normal difficulty, **Music ON**, first music track, Ghost ON, automatic level skins and automatic interface sizing. The on-screen controls are available automatically. Fullscreen starts off.

Existing saved preferences remain intact. If you previously saved Music OFF, turn it ON manually or choose **Restore Default Settings**. Restoring defaults resets other options too, while retaining records and campaign progress. **Reset Everything** is a separate destructive action requiring confirmation.

Sound requires a tap or click before many browsers permit playback. Start the game, check the Music setting and check device/browser volume if silent.

Preferences and records are local to this browser profile. The existing mobile save-key namespace is preserved. Desktop and mobile editions have separate keys; they do not synchronize between devices or with Windows builds. Clearing browser site data can remove records. Continue resumes the current run while the page remains open; it does not restore a run after a reload.

## Upload beside the desktop showcase

Upload the extracted **mobile.html** and **README_Mobile.md** files into the same published folder as the desktop `index.html`. Keep the desktop file intact.

The mobile page's address ends in **/mobile.html**. Use that exact lowercase filename in your showcase links. If you instead place it in a subfolder, include that folder in the URL. Uploading `mobile.html` does not automatically update an older link ending in `/mobile/` or `/mobile/index.html`.

After publishing, test the direct mobile link on a phone and the desktop link on a laptop. If an older page remains visible, refresh without the cached copy.

## Browser use

Open the showcase in the device's normal browser. Fullscreen support varies; the game can be played without it. If a social app's embedded browser has input, sound or fullscreen trouble, open the same link in the device browser.

This is a browser showcase, not an installed mobile app. Responsive browser checks do not replace testing on your actual phone or tablet.

## Credits

Open **Credits**, **DG Studios Manifesto** and **How to Play** in the game for contributor acknowledgements, the studio statement and the player guide.
