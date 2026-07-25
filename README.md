# Starflare — Codex Pet

Starflare is a custom Codex v2 pet based on the supplied lavender horned fox-dragon OC.

<p align="center">
  <img src="running-left.gif" alt="Starflare running-left animation preview" width="420">
</p>

## 运动预览

<p align="center">
  <img src="previews/running-left-00.png" alt="Starflare running-left frame 1" width="150">
  <img src="previews/running-left-02.png" alt="Starflare running-left frame 3" width="150">
  <img src="previews/running-left-04.png" alt="Starflare running-left frame 5" width="150">
  <img src="previews/running-left-06.png" alt="Starflare running-left frame 7" width="150">
</p>

逐帧镜像修复后的向左奔跑动作：完整轮廓、统一重心，并保留 Starflare 的蓬松尾焰与异色瞳。

## Contents

- `spritesheet.webp` — the 1536×2288 v2 spritesheet.
- `pet.json` — Codex pet manifest (`spriteVersionNumber: 2`).
- `running-left.gif` — repaired leftward movement preview.
- `previews/` — four featured stills shown at the top of this README.
- `validation-extended.json` — final v2 atlas validation report.
- `chroma-despill-extended.json` — transparency and chroma-edge cleanup report.
- `running-left-mirror-review.json` — verification data for the direct framewise-mirror repair.

## Repair

The original leftward movement contained generated-strip discontinuities. The repair mirrors the already validated final rightward frames one by one, so the leftward loop has exactly the same registration, cadence, scale, and complete silhouette as the rightward loop.

## Install

Copy `spritesheet.webp` and `pet.json` together into your Codex custom-pets directory:

```text
~/.codex/pets/starflare/
```
