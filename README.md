# BLOCK MATRIX — Deluxe Gold Desktop Showcase

Open [index.html](./index.html) on your hosted showcase to play the desktop edition, or [mobile.html](./mobile.html) for the touch edition. Both are standalone HTML files.

## Main menu

Start (selected mode) / Continue; Full Screen / Options; How to Play / DG Studios Manifesto; Credits / Exit Game.

Open **Options** for mode and level selection, difficulty, music, interface size, on-screen controls, records, reset actions, control reference and gamepad status. Back returns to the main menu. Campaign starts at Level 1; Practice uses a selected excavation level; Free Play starts empty.

Music and desktop On-Screen Controls default to ON. Existing saved choices remain intact. Restore Default Settings applies the defaults and resets other options while retaining scores and progress.

Mouse/touch controls sit outside the pit. Hold movement arrows to repeat; Drop, Hold and Rotate activate once. Keyboard: arrows move/soft drop, Up/X rotates clockwise, Z counterclockwise, Space hard drops, C holds, P pauses, O opens in-game Options, M returns to menu, F toggles fullscreen. Controller support remains available.

Browser Exit stops play and asks you to close the tab. The installed Windows app exits directly. Continue resumes an existing run while the page is open; records/settings are stored locally and do not sync across devices. How to Play contains the full rules and Hold explanation.

## GitHub showcase update

Upload index.html and README.md to the existing desktop showcase folder. If hosting mobile beside desktop, upload mobile.html and README_Mobile.md there too and link to /mobile.html. An old /mobile/ directory link does not automatically change. Keep the existing published paths where you need old links to continue working. Upload extracted files, not the ZIP.

## Windows builds

The Electron folder contains the updated RC4 source. Run Electron/Build_Windows.cmd with Node.js 22 or newer and an internet connection to produce Portable and Setup under Electron/dist. The accepted Fix 2 Portable approach and approved installer branding are retained. No newly compiled EXEs are included here; test rebuilt Windows editions before release.


Update 2.1 — Exit confirmation and Orbital Station
- Exit Game asks “Do you want to leave this game?” with Yes / No. No is focused initially and returns to the main menu.
- Yes closes the Electron application. Browsers stop the game and display a close-tab message because ordinary browser tabs cannot reliably close themselves.
- Copyright © Deluxe Gold Studios 2026.
- Orbital Station now features shaded ringed planets, a warm sun, and a spiral galaxy inspired by the supplied Nova Striker reference. Other skins are unchanged.
- Desktop, mobile and Windows build source updated together. Existing saves, preferences, portable launcher fix and installer branding retained.


Update 2.2: Ten supplied numbered skin images are embedded in the game. New tower splash artwork and five-second minimum display in Electron. See Phase_Upgrades.txt for details.


Update 2.4: Sector Excavation help now explains marked blocks, clearing rows, completion requirements and mode differences. In the Windows build kit, controls align along the bottom of the gameplay field. See Phase_Upgrades.txt.
