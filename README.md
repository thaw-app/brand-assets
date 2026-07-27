# brand-assets

Shared branding and packaging art for the [thaw-app](https://github.com/thaw-app) organization.

All files in this repository are proprietary brand assets of the Thaw project. Do not reuse or redistribute without permission.

## Layout

| Path | Purpose |
|------|---------|
| `headers/` | README / store page headers (dark & light) |
| `icons/` | Design sources and exported icons |
| `packaging/` | DMG backgrounds used by Thaw release CI |
| `marketing/` | Banners and screenshots (sources) |

## Consumers

- **README images** — use raw GitHub URLs, e.g.  
  `https://raw.githubusercontent.com/thaw-app/brand-assets/main/headers/thaw-dark.svg`
- **Thaw DMG CI** — sparse-checkout `packaging/dmg-background-27@2x.png` (prefer a pinned commit SHA)
- **Raycast** — keep thin local copies of `extension-icon.png` and `metadata/` for the store; headers point here

## Do not put here

App-runtime assets (`Assets.xcassets`, Icon Composer, `Info.plist`, strings) stay in product repos.
