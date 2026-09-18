# BLOCK MATRIX — Deluxe Gold (Mobile Showcase)

A falling-block puzzle game from Deluxe Gold Studios, playable directly in your browser. No installer, account, build step or asset download is required after the page loads.

## Play

[Open the game](./index.html). In a GitHub repository view, use the published **GitHub Pages** address to play; GitHub's HTML source viewer does not run the game.

## Game modes

- **Campaign:** starts at Level 1; complete all ten excavation sectors in order.
- **Practice Level:** select any excavation level. Completing its objective ends the practice run.
- **Free Play:** endless falling-block play with an empty starting board and **no pre-placed excavation blocks**. The selected level sets the initial speed and environment.

Campaign and Practice require both the line quota and removal of all marked excavation cells. How to Play contains the block guide and detailed rules.

## Controls

Use the on-screen buttons: Left/Right to move, the curved arrow to rotate, Down for soft drop, Drop for hard drop, and Hold to store a piece. Pause and Help are also available.

Portrait places controls below the board. On wider landscape phones, controls sit beside the board. Controls remain visible in this edition even when a connected mouse changes the browser's pointer classification. Keyboard support remains available.

Open the page in your phone's normal browser. If an in-app browser has trouble with sound, fullscreen or input, open the link in the device browser. Fullscreen availability depends on the browser; it is optional.

## Settings and records

Defaults: Campaign, Level 1, Normal difficulty, Music Off, first music track, Ghost On, automatic level skins and automatic interface sizing. Fullscreen starts off.

Preferences and mode-specific scores are stored in this browser. **Continue** resumes the current run only while the page remains open; it is not a saved game across reloads. Restore Default Settings keeps records and progress. Reset Everything erases this edition's records, progress, preferences and current run after confirmation.

Desktop and mobile editions have separate storage keys, so resetting one will not clear the other's records even when both share a domain. They do not import earlier showcase records or synchronize between devices. Private browsing or clearing site data can remove local records.

## Publish on GitHub Pages

1. Create a public repository (or use your existing showcase repository).
2. Upload this folder's **contents**, including `index.html`, `README.md` and `.nojekyll`, to the repository root. Upload the extracted files, not the ZIP.
3. In repository **Settings → Pages**, select **Deploy from a branch**, your publishing branch (usually `main`) and **/(root)**, then save.
4. Wait for deployment and open the Pages link GitHub provides. Share that playable link.

See [GitHub's publishing-source instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Credits

Created through the Alex + Astra collaboration for Deluxe Gold Studios. Contributor credits and the DG Studios Manifesto are included in the game.

## Compatibility

This is an HTML browser showcase, not a Windows EXE or installed mobile app. The game includes responsive layouts and embedded artwork/audio generation. Browser-emulated checks do not replace testing on your particular device. Desktop users can open `index.html` locally; mobile users should use the hosted Pages link.

## Touch layout

In landscape, movement, rotation and soft drop sit just to the right of the pit. Drop, Hold, Pause and Help sit just to its left. Their positions follow the pit when the viewport changes. Portrait retains the controls below the board. The compact information panel shows coloured Next and Hold piece previews as well as the objective and Gold charge.

## Hold a piece for later

Press C (keyboard), X (controller), or Hold (touch) to store the falling piece. If a piece is already stored, this swaps it with the falling piece. You must place the incoming piece before using Hold again. Save an I-shaped piece for a four-line clear; the HOLD preview shows your stored piece. A new Campaign sector or losing a life clears Hold.
