# Lenovo Legion Go 1 Optimal Settings Library

## Permanent rules
- Legion Go 1-specific settings only.
- Bespoke settings for every game.
- Retained power profiles only: Performance battery 20 W; Performance plugged in 25 W; Custom 25 W TDP / 25 W SPPT / 25 W FPPT.
- Quiet 8 W and Balanced 15 W are intentionally omitted.
- Include AMD Adrenalin, Integer Scaling, Legion Space, display, resolution, anti-aliasing/upscaling, graphics, FPS targets, and fallbacks.
- Integer Scaling is the default where the game supports an appropriate 1280x800 path.
- RIS Off by default.
- Prioritize the highest stable real frame rate.

## Current games

### Project CARS 3
- AMD: GPU Scaling On, Preserve Aspect Ratio, Integer Scaling On with 1280x800, RSR/RIS Off, Anti-Lag On, AFMF/Chill Off.
- Performance battery 20 W: 60 Hz, 60 FPS cap, Exclusive Fullscreen, 1280x800, V-Sync Off, TAA/game-default AA, Super Sampling Off, FSR Off, Motion Blur Off; Texture High, Filtering 16x, Geometry High, Tessellation Medium, Shadows Medium, Reflections/Environment Map Medium, Car/Track High, Mirrors Standard, Detailed Grass On, Particles/Density High, Post Processing High.
- Performance plugged in 25 W: 60 Hz, 60 FPS cap, Exclusive Fullscreen, 1280x800, V-Sync Off, Super Sampling/FSR Off, Motion Blur Off; Texture High, Filtering 16x, Geometry/Tessellation High, Shadows High, Reflections/Environment Map Medium, Car/Track High, Mirrors Standard, Grass On, Particles/Density High, Post Processing High.
- Custom 25/25/25: same 1280x800 display path and 60 FPS target; wet/night/cockpit fallback uses 90 Hz and 45 FPS, raising Reflections and Environment Map only if stable.
- Do not force hidden SMAA/FXAA configuration values.

## Update rule
When a new game is requested, append a bespoke entry to both master files while preserving all existing entries and permanent rules.