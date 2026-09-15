# BLOCK MATRIX — Deluxe Gold

A falling-block puzzle game for Windows desktops and laptops, with a classic 10 × 20 playfield, Gold Pieces, level objectives, local records, and adjustable interface sizes.

**[Play BLOCK MATRIX](./index.html)** — use this link from the published GitHub Pages site. On the repository page, use the live website link provided under Settings → Pages.

## Features

- Move, rotate, hold, and drop blocks to clear horizontal lines.
- Charge Gold Pieces and complete level objectives for additional challenges.
- Keyboard, mouse, and standard gamepad support.
- Adjustable UI size, including Large and TV presentation, plus reduced-motion settings.
- Local records and saved settings, with pause protection when focus changes.
- Built-in How to Play, Deluxe Gold Manifesto, and contributor Credits.

## Play on Windows

Open `index.html` in Microsoft Edge or Google Chrome, then select **Start**. No installation or build tools are required. Click the game before using gameplay shortcuts if focus is elsewhere.

| Key | Action |
| --- | --- |
| Left / Right arrows | Move |
| Down arrow | Soft drop |
| Up arrow / X | Rotate clockwise |
| Z | Rotate counterclockwise |
| Space | Hard drop |
| C | Hold piece |
| P | Pause / resume |
| M | Main Menu |
| Esc | Close the current dialog, or return to Main Menu |
| O | Options |
| R | Restart |
| F | Toggle game fullscreen, including from Main Menu |
| Tab / Shift+Tab | Navigate controls |
| Enter / Space | Activate a focused button |

Gameplay shortcuts apply when the playfield has focus; focused menu controls use normal keyboard navigation. Use the on-screen buttons when needed. Audio starts after interaction. Select **UI Size** to suit your display and viewing distance.

Records and settings stay in the current browser's local storage. They do not sync between browsers, computers, the Electron app, or different website addresses. Clearing site data removes them; private browsing may not retain them.

## Publish with GitHub Pages

1. Create a public GitHub repository, for example `block-matrix`.
2. Upload **index.html** and **README.md** directly to the repository root, then commit them to `main`. Upload the extracted files, not the ZIP or its enclosing folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select **main** and **/(root)**, then **Save**.
6. Wait for deployment to finish. Open the published website address shown on the Pages settings screen.
7. Add that address to the repository's **About → Website** field so visitors can find the playable showcase.

A project website normally uses `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`. Replace the placeholders with your actual account and repository names. The ordinary GitHub file viewer displays source code; visitors should use the Pages website to play.

Official instructions: [GitHub Pages publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Package

```text
index.html   Complete standalone browser game
README.md    Overview, controls, and publishing instructions
```

The HTML includes the game code, styles, contributor portraits, and supplied BLOCK MATRIX browser icon. It needs no separate asset folder, external library, server application, or Electron runtime. This browser edition opens at Main Menu; the Windows installer and desktop splash belong to the separate Electron edition.

Based on the approved HTML 1.0 RC1 gameplay. Intended for desktop/laptop browser play; a dedicated mobile release remains a separate development target. Physical gamepad behavior and performance vary with hardware and browser.

## Credits

See **Credits** and **Deluxe Gold Manifesto** in Main Menu for the existing contributor acknowledgments and project philosophy.
