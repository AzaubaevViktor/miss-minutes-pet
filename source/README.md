# Native pixel redraw

The canonical character and all pose families were freshly redrawn with built-in ImageGen for a 192 × 208 rectangular runtime cell. Raw generated source strips are larger than runtime; opaque component seeds recover their existing generated alpha, then each coherent family receives one shared isotropic transform. No aspect stretching or independent per-frame resizing is used. The left run is an exact framewise mirror of the right run.

The logical canvas is 96 × 104, enlarged ×2 to 192 × 208. The assembled opaque master is exported at 80% opacity. RGB uses a shared 32-color palette without dithering. Alpha has 32 independent levels; body alpha remains exactly 204/255. Alpha and RGB are never averaged together, avoiding gray rim artifacts. RGB quantization is a small visual approximation; subsequent WebP compression is lossless. PNG and WebP contain identical final RGBA pixels.

Current prompts are `../prompts/native-*.txt`. Earlier pixel, contour and HD experiments remain historical sources and do not describe the current runtime. Original film reference photos are not published.
