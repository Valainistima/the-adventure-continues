# Spyro Browser — Public Portal

A fan-made static web interface that loads EmulatorJS from its official CDN. The page includes a portal illustration, lightweight CSS effects, fullscreen emulator display, and a local ROM/optional BIOS selector opened by clicking the golden dragon (or the START GAME area).

## Important

- This repository/package intentionally does **not** include a PlayStation ROM or BIOS.
- Visitors select their own files in the browser. The page code does not upload those selected files to this website host.
- If the visitor enables **Remember my files on this device**, files are stored in that browser's IndexedDB. Browser storage can be cleared or quota-limited.
- EmulatorJS is loaded from `https://cdn.emulatorjs.org/stable/data/`, so an internet connection is needed to start the emulator.
- This project is unofficial and is not affiliated with the rights holders of Spyro or PlayStation.

## Publish with GitHub Pages

1. Create a new public repository named `spyro-browser` (or another name you prefer).
2. Upload `index.html`, `README.md`, `.nojekyll`, `.gitignore`, and the complete `assets` folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/(root)` folder, then save.
6. Use the URL shown in **Settings → Pages** after the deployment finishes.

Do not add ROM, BIOS, memory-card, or save-state files to a public repository unless you have permission to distribute them.
