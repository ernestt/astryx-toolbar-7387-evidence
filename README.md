# Astryx Toolbar PR #7387 visual evidence

Matched real-browser before/after screenshots for every rendered story under:

- `Core/Toolbar` (14 stories)
- `Core/ToolbarEdgeCompensation` (23 stories)

## Capture contract

- **Before:** Astryx `6ecd41722788031aec349c3676ac4ab3f7d2dc4c`
- **After:** Astryx PR #7387 head `876e3f98f28e2bb273a86ceb168db55046055cd2`
- **Browser:** Chrome 155 via Playwright
- **Viewport:** 1440 × 1000 CSS pixels, device scale factor 1
- **Theme / mode / direction:** neutral / light / LTR
- **State:** default rendered state for each story
- **Determinism:** fonts awaited; transitions, animation, and caret disabled
- **Post-processing:** only the outer background canvas was trimmed, then a 24px white evidence margin was added. Story pixels were not resized or edited.

`manifest.json` maps story IDs to each screenshot and records dimensions. `capture-details.json` contains the computed capture geometry. All 74 PNGs are named with the same ordinal and story ID so each before/after pair sorts together.

These images are review evidence only; they are not part of the Astryx source tree or package output.
