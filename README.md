# Forge Fitness — Recovery Build

This build intentionally starts from the last known-working V1 browser foundation and adds the body modules without replacing the working shell.

## Active
- Training logger
- Knowledge Base with 303 starter exercises, filters, sorting, ratings
- Permanent baseline
- Goals
- Weekly review workflow
- Structural Body Type data entry
- Body Shape data entry with men/women presentation
- Real camera multi-view scan prototype
- Real pose-landmark model loaded only when Scan is opened
- Actual captured frames stored in IndexedDB

## Deliberately not faked
- 3D reconstruction is not claimed complete
- Measurements are not claimed to come from a validated 3D mesh
- Body composition is not estimated from the camera

## GitHub Pages
`index.html` is at the repository root. `.nojekyll` disables Jekyll processing for this static app. The build does not register a caching service worker from the page.
