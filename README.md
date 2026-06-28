# Die-Cut Sticker Maker

A single-file, fully client-side tool for turning artwork into a die-cut sticker
with a white padded contour border — like a real cut sticker, not a bounding box.

## Use it
Open `die-cut-sticker-tool.html` in any modern browser. Drag in an image
(or paste from clipboard). It will:

- Auto-remove a flat background (corner-sampled, with a tolerance slider)
- Grow a true contour border using a Euclidean distance transform
- Let you tune border width, color, an optional cut line, and corner smoothing
- Export a transparent PNG at 1×–4×

No uploads, no dependencies, no build step. Everything runs locally in the page.
