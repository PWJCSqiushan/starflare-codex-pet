# Starflare — Codex Pet

Starflare is a custom Codex v2 pet based on the supplied lavender horned fox-dragon OC.

## Contents

- `spritesheet.webp` — the 1536×2288 v2 spritesheet.
- `pet.json` — Codex pet manifest (`spriteVersionNumber: 2`).
- `running-left.gif` — repaired leftward movement preview.
- `validation-extended.json` — final v2 atlas validation report.
- `chroma-despill-extended.json` — transparency and chroma-edge cleanup report.
- `running-left-stable-review.json` — frame-extraction diagnostics for the leftward-motion repair.

## Repair

The original leftward movement used independently fitted frame extraction, making the vertical crop position jump across the loop. The repair re-extracts that row using stable source slots so the full row shares one registration basis while preserving the original gait.

## Install

Copy `spritesheet.webp` and `pet.json` together into your Codex custom-pets directory:

```text
~/.codex/pets/starflare/
```
