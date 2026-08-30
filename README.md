# Guts-Berserk Pet for Codex

> A compact animated Guts companion in the Berserker Armor — black segmented plate, a torn cape, a glowing red visor, and the enormous Dragonslayer secured across his shoulder and back.

<p align="center">
  <img src="assets/preview.png" alt="Preview of the animated Guts-Berserk pet sprite sheet" width="820">
</p>

<p align="center">
  <a href="README.ru.md">Русская версия</a>
</p>

## What is included

- A ready-to-install custom pet named `Guts-Berserk`.
- An 8 × 11, version 2 sprite sheet (`1536 × 2288` pixels).
- Idle, left/right running, waving, jumping, failed, waiting, working, and review animations.
- Sixteen head-look directions for a complete clockwise gaze loop.
- A consistent shoulder/back-mounted Dragonslayer supported by the visible X-shaped harness.
- A closed gauntlet-to-hilt grip throughout the animation set.

## Install

1. Copy `pet.json` and `spritesheet.webp` into:

   ```text
   %USERPROFILE%\.codex\pets\guts-berserker\
   ```

2. Open or refresh Codex.
3. Choose **Settings → Pets → Guts-Berserk**.

Back up an existing folder with the same pet ID before replacing it.

## Repository variants

- [`main`](https://github.com/hqvdvn-cmd/GutsPetCodex/tree/main) — default `Guts`.
- `Guts-Berserk` — this Berserker Armor version.

## Package layout

```text
.
├── assets/
│   └── preview.png
├── pet.json
└── spritesheet.webp
```

`pet.json` declares `spriteVersionNumber: 2`; keep it beside the sprite sheet so Codex loads all eleven animation rows.

## Verification

The published WebP is the same validated asset used by the local Codex package:

- `1536 × 2288`, 8 columns × 11 rows;
- RGBA transparency with zero transparent-RGB residue;
- all required v2 cells present and unused cells transparent;
- deterministic atlas validation completed with zero errors and warnings.

## Notes

This is an unofficial, non-commercial fan-made pet. **Berserk**, Guts, the Berserker Armor, and the Dragonslayer are associated with Kentaro Miura and their respective rights holders. This repository is not affiliated with or endorsed by them.
