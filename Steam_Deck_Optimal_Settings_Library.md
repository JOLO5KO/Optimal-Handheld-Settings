# Steam Deck Optimal Settings Library

## Permanent rules
- Steam Deck-specific settings only.
- Use bespoke settings for every game.
- Include Quick Access Menu, display, resolution, anti-aliasing/upscaling, graphics, FPS targets, and fallbacks.
- Prioritize the highest stable real frame rate.
- Do not transfer Legion Go settings into this file.

## Current games

### Project CARS 3
- Recommended target: 60 FPS; use 45 FPS at 90 Hz for rain, night, cockpit, or large-grid situations.
- QAM 60 FPS: 60 Hz, 60 FPS cap, Allow Tearing Off, Half-Rate Shading Off, TDP Off, Manual GPU Clock Off, Scaling Auto, Filter Linear, SteamOS FSR Off.
- Display: Exclusive Fullscreen, 1280x720, V-Sync Off, one in-game resolution setting, Super Sampling Off, game-controlled anti-aliasing, FSR Off, Motion Blur Off.
- Graphics: Textures High, Filtering 16x, Geometry High, Tessellation High, Shadows High, Reflections Medium, Environment Map Medium, Car/Track High, Mirrors Standard, Grass On, Particles/Density High, Post Processing High.
- QAM 45 FPS fallback: 90 Hz, 45 FPS cap, same in-game settings; raise Reflections and Environment Map to High only if stable.
- Do not force hidden SMAA/FXAA configuration values.

## Update rule
When a new game is requested, append a bespoke entry while preserving all existing entries and permanent rules.