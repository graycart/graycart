# Graycart

Family umbrella. Clone with submodules, or clone any child on its own.

| Repo | What |
|------|------|
| [graycart-gba](https://github.com/graycart/graycart-gba) | **Long-term play host** for GBA + DMG/CGB (`graycart-gba` crate/binary) |
| [graycart-gb](https://github.com/graycart/graycart-gb) | DMG/CGB **library** (`graycart` crate) + maintenance host (left daily-target at P12) |
| [graycart-nes](https://github.com/graycart/graycart-nes) | NES emulator (placeholder) |
| [graycart-snes](https://github.com/graycart/graycart-snes) | SNES emulator (placeholder) |
| [graycart-n64](https://github.com/graycart/graycart-n64) | N64 emulator (placeholder) |
| [graycart-linux](https://github.com/graycart/graycart-linux) | Omarchy-derived; Graycart-stripped host OS |

```bash
git clone --recurse-submodules https://github.com/graycart/graycart.git
```

Each emulator is independently `cargo test`-able. This repo is **not** a Cargo workspace.

**P12 cutover:** prefer **graycart-gba** for new 8-bit and GBA play. graycart-gb remains the intentional SM83/lib dependency.

MIT — Copyright (c) 2026 Graycart.
