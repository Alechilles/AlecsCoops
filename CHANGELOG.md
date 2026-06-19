# Changelog

## 1.0.4 - Telemetry Stats and Release Metadata - 2026-06-18

### Added
- Added a telemetry consent icon and stats descriptor so Alec's Coops can opt into hosted usage summaries through the shared telemetry consent flow.

### Changed
- Updated release metadata for Hytale `0.5.x`, Modtale `0.5.3`, Alec's Tamework `2.15.x`, and manifest version `1.0.4`.

### Fixed
- Updated hosted telemetry stats routing to the current Alec telemetry ingest endpoint used by the shared rollout.

## 1.0.3 - Asset Pack Icon - 2026-06-07

### Added
- Added a 256x256 in-game icon for the Coops asset pack.

## 1.0.2 - Update 5 Compatibility + Publishing Metadata - 2026-05-26

- Updated release metadata for Hytale server `0.5.0`, Alec's Tamework `2.11.x`, and manifest version `1.0.2`.
- Updated CurseForge publishing to upload changelogs as HTML.
- Updated Modtale release metadata to target Hytale `0.5.0`.

## 1.0.1 - Animal Husbandry Fallback Override Priority - 2026-04-03

- Increased `Server/Tamework/Items/Coops/ACCoopChicken.json` priority so Alec's Coops reliably overrides Animal Husbandry's temporary fallback coop config when both mods are enabled.
- Updated `manifest.json` version to `1.0.1`.

## 1.0.0

- Initial release.
- Added standalone coop override asset: `Server/Farming/Coops/Coop_Chicken.json`.
- Added managed coop config override asset: `Server/Tamework/Items/Coops/ACCoopChicken.json`.
- Added required dependency on `Alec's Tamework!`.
- Added optional dependency on `Alec's Nametags!`.
