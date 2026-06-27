# Reborn Builds

Public WebGL build assets for The Real Run Reborn.

## Structure

- `catalog.json` lists available Reborn maps.
- `maps/<map-slug>/reborn.json` is the Unity WebGL manifest for one map.
- `maps/<map-slug>/Build/` contains loader, framework, wasm, and split data parts.
- `maps/<map-slug>/StreamingAssets/` contains Unity streaming assets.

Secrets do not belong in this repository. The production boot token is signed by the Cloudflare Pages Function in the site repository.
