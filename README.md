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
| `badges/` | Partner / “works with” badges |

## Consumers

- **README images** — use raw GitHub URLs, e.g.  
  `https://raw.githubusercontent.com/thaw-app/brand-assets/main/headers/thaw-dark.svg`
- **Thaw DMG CI** — sparse-checkout `packaging/dmg-background-27@2x.png` (prefer a pinned commit SHA)
- **Raycast** — keep thin local copies of `extension-icon.png` and `metadata/` for the store; headers point here
- **GitHub org avatar** — `icons/org-avatar.png`, uploaded by hand in the organization's settings. It is Icon Composer's dark render of Thaw's `AppIcon.icon`, with the corners filled in the tile's own colours so it is a full square for GitHub to round

## Do not put here

App-runtime assets (`Assets.xcassets`, Icon Composer, `Info.plist`, strings) stay in product repos.
