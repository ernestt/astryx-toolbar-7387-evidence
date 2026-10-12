# Core Toolbar pre-#6954 restoration evidence

This matrix compares the compact Toolbar behavior currently on `main` with the proposed restoration. Both sides use the same 1440 × 1000 Chromium viewport and neutral/light/LTR Storybook globals.

- **Before source:** Astryx `6ecd41722788031aec349c3676ac4ab3f7d2dc4c`
- **After source:** Astryx `9368c86f` (the Core-only restoration commit)
- **Changed state:** `sm` block padding returns from 4px to 8px.
- **Preserved states:** Section/theme-owned inline padding remains 12px in this theme; `md` and `lg` remain at 8px block padding; controls continue to inherit Toolbar size.
- **Machine-readable measurements:** [`geometry.json`](./geometry.json)

## Compact

| Before — 4px block padding | After — 8px block padding |
| --- | --- |
| ![Compact Toolbar before restoration](./before-compact.png) | ![Compact Toolbar after restoration](./after-compact.png) |

## Card header composition

| Before — 4px block padding | After — 8px block padding |
| --- | --- |
| ![Card header Toolbar before restoration](./before-card-header.png) | ![Card header Toolbar after restoration](./after-card-header.png) |

## Size cascade matrix

| Before | After |
| --- | --- |
| ![Toolbar size matrix before restoration](./before-size-matrix.png) | ![Toolbar size matrix after restoration](./after-size-matrix.png) |
