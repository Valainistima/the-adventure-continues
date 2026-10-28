# Spyro Browser V9 – Music Button Fix

This package is based on V8 and fixes the portal music controls.

## Files
- `index.html`: the updated page with a prominent, always-visible PLAY MUSIC button.
- `assets/portal.webp`: portal artwork.
- `assets/dragon-realms-ambience.mp3`: Starlit Dragon Vale · Eternal Drift V7.

## Update your existing GitHub Pages site
1. Back up the current working version/branch first.
2. In the published branch of `Valainistima/the-adventure-continues`, replace `index.html` with the one in this package.
3. In the existing `assets` directory, upload/replace `dragon-realms-ambience.mp3` with the file from this package. It must be at `assets/dragon-realms-ambience.mp3`, not `assets/assets/...`.
4. Keep your existing `assets/portal.webp`; only replace it if you intend to use the copy in this package.
5. Commit both changes to the branch used by GitHub Pages.
6. Open the live page and press `Ctrl+F5`. If the browser blocked autoplay, click `♫ TAP TO PLAY` / `♫ PLAY MUSIC`.

## Diagnostics
- `♫ AUDIO FILE ERROR` means the MP3 failed to load. Verify the path, letter casing, and that the MP3 was committed to the deployed branch.
- `♫ TAP TO PLAY` means the browser blocked autoplay; click the button once.
- Music is intentionally stopped when the emulator starts to reduce competing work on lower-memory PCs.
