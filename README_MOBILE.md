# BLOCK MATRIX — Deluxe Gold Mobile

**[Play the mobile edition](./mobile.html)** from the published GitHub Pages website.

A dedicated phone and tablet version of BLOCK MATRIX, retaining the approved 10 × 20 playfield, Gold Pieces, level objectives, scoring, music, Credits, and Deluxe Gold Manifesto.

## Mobile controls

| Button | Action |
| --- | --- |
| Left / Right | Tap to move once; hold to repeat |
| Down | Hold to soft drop |
| ↶ Rotate / ↷ Rotate | Rotate counterclockwise / clockwise |
| Hold | Save or swap the current piece |
| Drop | Immediately drop and lock the piece |
| Pause | Pause play; use Resume to continue |
| Menu | Return to Main Menu |
| Options | Adjust the game settings |

Two fingers can move and rotate together. Next and Hold previews remain visible. Touch controls disable while gameplay dialogs are open. Use the buttons rather than swiping the playfield.

Portrait mode places controls below the board. Landscape mode places them beside it. Rotating the screen pauses play; tap **Resume** when ready. Menus and information dialogs scroll when necessary. The layout accommodates safe-area insets and changing browser viewport height.

Tap Start to begin and enable game audio. Fullscreen is optional and depends on your browser; unsupported browsers display a disabled Browser button. Play remains available in the ordinary browser view.

## Upload to your existing GitHub showcase

1. Extract this ZIP.
2. Upload `mobile.html` and `README_MOBILE.md` to the same repository folder as your existing desktop `index.html`.
3. Commit the files and wait for your GitHub Pages deployment to complete.
4. Open `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/mobile.html` on your phone or tablet.
5. Add `[Play on mobile](./mobile.html)` to your existing README so visitors can find this edition.

Keep the desktop `index.html` and its README. This package uses a separate README filename so it can be added alongside them.

For a new repository, enable **Settings → Pages → Deploy from a branch**, choose **main** and **/(root)**, and save. Access the mobile page through the full `/mobile.html` address. [GitHub Pages instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Files and saved data

`mobile.html` contains the complete game, styling, touch controls, portraits, and browser icon. No separate assets, libraries, or build tools are needed. No service worker or offline installation is included.

Records and settings use browser-local storage. Desktop and mobile pages on the same website use the existing shared game storage keys; other browsers and devices keep their own data. Clearing site data removes saved records and settings.

## Validation

Browser emulation passed at 320 × 568, 390 × 844, 412 × 915, 844 × 390, 667 × 375, and 768 × 1024. Checks covered board/control separation, minimum 44-pixel control height, startup, touch input, pause/resume, Options, Credits, and Manifesto. Additional tests covered multiple fingers on a held control, touch cancellation, and rotation-triggered pause.

These are Chromium-based emulation results, not physical iPhone, iPad, or Android certification. Before announcing a final mobile release, try a sustained session on your intended devices, including audio, browser-toolbar resizing, screen rotation, and returning from another app.
