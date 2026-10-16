# Current pixel-art pose artwork

Current strips and canonical base are generated pixel artwork. The native atlas uses a 96 × 104 logical grid enlarged to 192 × 208 with nearest-neighbor sampling. `spritesheet-opaque-master.png` preserves the assembled opaque source. The installed atlas applies `round(source_alpha * 0.4)` once to every pixel, for 60% transparency / 40% visibility. Warm amber contour light is already part of the generated strips.

Current prompts: `../prompts/pixel-*.txt`. Previous contour/foreground-extraction prompts and `smooth-amber-bloom.png` are preserved as historical experiments and are not the current specification. The old HD directory belongs to a previous, non-pixel version.
