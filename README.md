# Coupon Master

[Play Coupon Master](https://gamegen-astranova.github.io/Coupon-Master/)

A browser puzzle game with 30 orders. Arrange coupons in the right sequence to reduce each shopping bill, then buy and sell coupons at the exchange.

## Controls

- Drag coupons to rearrange the book.
- Double-click a coupon to add it to the play order; at the exchange, double-click to sell it.
- Use Q / E or the rotation buttons to rotate a selected coupon.
- The top-right icons control sound effects, background music, and language separately.

English, Traditional Chinese, Simplified Chinese, and Japanese are supported. Progress is saved in the current browser.

## Deployment

This repository contains the built playable game. GitHub Pages publishes `main` from `/ (root)`, following the other gamegen-AstraNova game projects. The root `index.html`, `assets/`, `common/`, and `config/` come directly from the tested GameGen delivery ZIP.

The React 19 / TypeScript development project is maintained separately. To update, rebuild that project, replace the runtime files with the new build, remove obsolete runtime files, and push to `main`. Do not add development dependencies, local art research, or source-workspace paths to this delivery repository.

## Credits

Sound effects: [Kenney](https://kenney.nl/assets), Interface Sounds, Casino Audio, and Music Jingles, licensed under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

Background music: 鍛冶職人のお店, supplied for this game separately; it is not covered by the sound effects' CC0 license. Character art features AstraNova's Asteria, Lumi, and Nyx.

Gameplay inspiration: Super Coupon Club by Gizmo199 and NicolaiGD. This is a separate game project and is not an official release of Super Coupon Club.

## Build verification

2026-09-15: production build and 35 automated tests passed. The 80 runtime files were checked byte-for-byte against the delivery ZIP. Full 30-order manual playthrough and GameGen backend upload are not claimed by this release.
