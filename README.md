# Guts Pet for Codex

> A compact animated Guts companion for the Codex desktop app — dark armor, a stern expression, the Behelit, and an enormous Dragonslayer.

<p align="center">
  <img src="assets/preview.png" alt="Preview of the animated Guts pet sprite sheet" width="820">
</p>

<p align="center">
  <a href="README.ru.md">Русская версия</a>
</p>

## What is included

- A ready-to-install custom pet named `Guts`.
- An 8 × 11, version 2 sprite sheet (`1536 × 2288` pixels).
- Idle, directional running, waving, jumping, failed, waiting, working, and review animations.
- Custom Behelit toss-and-catch and stationary Dragonslayer training loops.
- Sixteen look-direction poses for a smooth full-circle gaze loop.

## Install

1. Close or refresh the Codex pet picker.
2. Copy `pet.json` and `spritesheet.webp` into:

   ```text
   %USERPROFILE%\.codex\pets\guts\
   ```

3. Open Codex, then choose **Settings → Pets** and select `Guts`.

If you already have a custom pet with this ID, back up its folder first.

## Package layout

```text
.
├── assets/
│   └── preview.png
├── pet.json
└── spritesheet.webp
```

`pet.json` declares `spriteVersionNumber: 2`; keep it next to the sprite sheet so Codex loads the extended animation contract.

## Verification

The published sheet is the validated final asset used by the local Codex pet package:

- `1536 × 2288` WebP atlas
- RGBA transparency with no opaque chroma-key pixels
- all required v2 cells present, unused cells transparent

## Notes

This is an unofficial, non-commercial fan-made pet. **Berserk**, Guts, and the Dragonslayer are associated with Kentaro Miura and their respective rights holders. This repository is not affiliated with or endorsed by them.
