# Changelog

All notable changes to RNK Core MapGen are documented in this file.

## [1.0.10] - 2026-07-18

### Fixed
- Version-sync bump alongside the free-tier module (no functional changes here — the generation quota fix in that release was server-side only and never affected this module)

## [1.0.9] - 2026-07-18

### Fixed
- GMs (including Assistant GMs) now share Patreon-authenticated access automatically once any GM logs in — access is stored per-world and persists across reloads instead of requiring a fresh per-browser Patreon login every session
- Dungeon prop, furniture, and floor textures now load correctly instead of silently 404ing

## [1.0.8] - 2026-07-17

### Fixed
- Version bump to force Foundry to re-download and overwrite locally cached pre-1.0.7 files with the corrected mapgen-api.rnkstudios.uk endpoints

## [1.0.7] - 2026-07-17

### Fixed
- Server API moved to a new host; default Generator API URL and Patreon auth URL now point to mapgen-api.rnkstudios.uk

## [1.0.6] - 2026-05-02

### Fixed
- Normalized Foundry asset paths and regenerated release packaging

## [1.0.3] - 2026-04-18

### Added
- Foundry VTT v14 verified compatibility alongside v13

### Fixed
- Module metadata cleaned and finalized for initial public release

## [1.0.0] - 2026-04-01

### Added
- All features from the Alpha tier
- Scene darkness control (0-1) and light color picker
- Light intensity (0-1) and 20 light animation options: Torch, Flicker, Pulse, Chroma, Wave, Fog, Sunburst, Dome, Emanation, Hexa, Ghost, Energy, Roiling, Vortex, Witchwave, Revolving, Siren, Void Hole, None, and additional types
- Ambient sound selection: None, Dungeon Mix (Layered), Random Variety, Cave Drip, Underwater, Whispering, Creepy Whispering, Eerie, Ominous, Ominous Drum; volume control (0-1)
- Independent toggles for: wall creation, door creation, light creation, sound creation, mob spawning, boss spawning, miniboss spawning, turbo mode, mob movement, pause on combat, wall collision, player avoidance, waypoint generation, auto-activation, and trap waypoint visibility
- Movement interval control (1-120 seconds)
- Accessibility options: difficulty ramps, tutorial markers, wheelchair-accessible paths, and safe zones
- Atmosphere sliders for corruption level, decay intensity, magical saturation, and cursed level (each 0-10)
- Environmental hazard options: None, Flooding, Lava Flows, Unstable, Multiple
- Deep Foundry VTT scene and canvas integration
