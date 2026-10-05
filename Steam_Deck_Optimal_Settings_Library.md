# Steam Deck Optimal Settings Library

## Permanent rules
- Use only settings exposed by the installed game menu or Steam Deck QAM.
- List QAM, display, and every individual exposed graphics setting as separate bullets.
- Mark unavailable controls as `Not exposed in menu`; never invent settings.
- Prioritize the highest stable real FPS and consistent frametimes.

## DOOM Eternal
### QAM
- Refresh rate: 60 Hz.
- FPS limit: 60.
- Allow Tearing: Off.
- Half-Rate Shading: Off.
- TDP Limit: Off.
- Manual GPU Clock: Off.
- Scaling Mode: Auto.
- Scaling Filter: Linear.
- SteamOS FSR: Off.
- HDR: Off.
### Display
- Window mode: Fullscreen.
- Resolution: 1280x800.
- V-Sync: Off.
- Field of View: 100.
- Motion Blur: Off.
- Depth of Field: Off.
- Chromatic Aberration: Off.
- Film Grain: Off.
- HDR: Off.
### Graphics
- Texture Pool Size: Ultra Nightmare.
- Texture Filtering: Ultra Nightmare.
- Geometry Quality: High.
- Shadow Quality: Medium.
- Reflection Quality: Medium.
- Directional Occlusion: High.
- Lights Quality: High.
- Particles Quality: High.
- Decal Quality: High.
- Water Quality: High.
- Volumetric Quality: Medium.
- Ray Tracing: Off.
- Fallback: Lower Volumetric Quality, then Reflections, then Shadows.

## Killing Floor 3
### QAM
- Refresh rate: 40 Hz.
- FPS limit: 40.
- Allow Tearing: Off.
- Half-Rate Shading: Off.
- TDP Limit: Off.
- Manual GPU Clock: Off.
- Scaling Mode: Auto.
- Scaling Filter: Linear.
- SteamOS FSR: Off.
### Display
- Resolution: 1280x720.
- V-Sync: Off.
- Dynamic Resolution: Off.
- Upscaler: XeSS.
- Upscaler mode: Balanced.
- Sharpening: Low.
- Field of View: 90.
- Motion Blur: Off.
- Depth of Field: Off.
- Film Grain: Off.
- Chromatic Aberration: Off.
### Graphics
- View Distance Quality: Low.
- Reflection Quality: Low.
- Post Process Quality: Low.
- Shadow Quality: Low.
- Global Illumination Quality: Low.
- Texture Quality: Medium.
- Effects Quality: Low.
- Foliage Quality: Low.
- Shading Quality: Low.
- Reflection Method: SSR where exposed.
- Global Illumination Method: Lumen Off or lowest non-Lumen option where exposed.
- Supersampling Mode: Off.
- Quality Mode: Performance or equivalent lowest non-destructive mode.
- Frame Generation: Off unless the installed build exposes it and it is separately tested.
- Fallback: XeSS Performance, then Effects Quality and Shadow Quality Low.

## God of War (2018)
### QAM
- Refresh rate: 40 Hz.
- FPS limit: 40.
- Allow Tearing: Off.
- Half-Rate Shading: Off.
- TDP Limit: Off.
- Manual GPU Clock: Off.
- Scaling Mode: Auto.
- Scaling Filter: Linear.
- SteamOS FSR: Off.
### Display
- Window mode: Borderless.
- Resolution: 1280x720.
- V-Sync: Off.
- Upscaler: FSR 2.0.
- Upscaler mode: Quality.
- Sharpening: 0.3.
- Motion Blur: Off.
- Film Grain: Off.
### Graphics
- Texture Quality: Original.
- Model Quality: Original.
- Anisotropic Filtering: High.
- Shadow Quality: Low.
- Reflection Quality: Original.
- Atmospherics Quality: Low.
- Ambient Occlusion: Original.
- Fallback: 30 Hz/cap 30; raise Shadows only if stable.

## Project CARS 3
### QAM
- Refresh rate: 60 Hz.
- FPS limit: 60.
- Allow Tearing: Off.
- Half-Rate Shading: Off.
- TDP Limit: Off.
- Manual GPU Clock: Off.
- Scaling Mode: Auto.
- Scaling Filter: Linear.
- SteamOS FSR: Off.
### Display
- Window mode: Fullscreen.
- Resolution: 1280x720.
- V-Sync: Off.
- Super Sampling: Off.
- Anti-aliasing: Game-controlled; no normal selectable AA control is claimed.
- Motion Blur: Off.
### Graphics
- Texture Resolution: High.
- Texture Filtering: 16x.
- Geometry Quality: High.
- Tessellation Quality: High.
- Shadow Quality: High.
- Reflection Quality: Medium.
- Environment Map: Medium.
- Car Detail: High.
- Mirror Quality: Standard.
- Detailed Grass: On.
- Particle Quality: High.
- Particle Density: High.
- Post Processing Quality: High.
- Fallback: 90 Hz/cap 45 for rain/night/cockpit/large grids; lower Reflections first.

## Cyberpunk 2077
### QAM
- Refresh rate: 40 Hz.
- FPS limit: 40.
- Allow Tearing: Off.
- Half-Rate Shading: Off.
- TDP Limit: Off.
- Manual GPU Clock: Off.
- Scaling Mode: Auto.
- Scaling Filter: Linear.
- SteamOS FSR: Off.
### Display
- Resolution: 1280x720.
- Window mode: Fullscreen.
- V-Sync: Off.
- Max FPS: 40.
- Upscaler: FSR 2.1.
- Upscaler mode: Balanced.
- Sharpening: 0.2.
- Frame Generation: Off.
- Field of View: 80.
- Motion Blur: Off.
- Film Grain: Off.
- Chromatic Aberration: Off.
- Depth of Field: Off.
- Lens Flare: On.
### Graphics
- Texture Quality: High.
- Crowd Density: Low.
- Contact Shadows: Off.
- Improved Facial Lighting Geometry: On.
- Anisotropy: 8x.
- Local Shadow Quality: Low.
- Cascaded Shadow Resolution: Low.
- Cascaded Shadows Range: Low.
- Distant Shadows Resolution: Low.
- Volumetric Fog Resolution: Low.
- Volumetric Cloud Quality: Low.
- Max Dynamic Decals: Medium.
- Screen Space Reflections Quality: Low.
- Subsurface Scattering Quality: Medium.
- Ambient Occlusion: Medium.
- Mirror Quality: Medium.
- Level of Detail: Medium.
- Ray Tracing: Off.
- Path Tracing: Off.
- Fallback: 30 Hz/cap 30 for Dogtown; FSR Performance if required.

## Hitman: Absolution
### QAM
- Refresh rate: 60 Hz.
- FPS limit: 60.
- Allow Tearing: Off.
- Half-Rate Shading: Off.
- TDP Limit: Off.
- Manual GPU Clock: Off.
- Scaling Mode: Auto.
- Scaling Filter: Linear.
- SteamOS FSR: Off.
### Display
- Window mode: Fullscreen.
- Resolution: 1280x720.
- V-Sync: Off.
- Post-process Anti-Aliasing: High.
- MSAA: Off.
- Anisotropic Filtering: 16x.
- Motion Blur: Off.
- Depth of Field: Normal.
- Bloom: Normal.
### Graphics
- Texture Quality: High.
- Shadow Quality: High.
- Level of Detail: High.
- Post Processing Quality: Medium.
- Ambient Occlusion: High.
- Tessellation: On.
- Fallback: Shadows Medium.

## Halo Infinite
### QAM
- Refresh rate: 40 Hz.
- FPS limit: 40.
- Allow Tearing: Off.
- Half-Rate Shading: Off.
- TDP Limit: Off.
- Manual GPU Clock: Off.
- Scaling Mode: Auto.
- Scaling Filter: Linear.
- SteamOS FSR: Off.
### Display
- Resolution: 1280x720.
- V-Sync: Off.
- Minimum FPS: 40.
- Maximum FPS: 40.
- Dynamic Resolution: On.
- Minimum Dynamic Resolution Scale: 85%.
- Upscaler: FSR 2 where exposed.
- Sharpening: 20.
- Async Compute: On.
- Field of View: 78.
### Graphics
- Texture Quality: Medium.
- Texture Filtering: 4x.
- Geometry Quality: Medium.
- Reflection Quality: Low.
- Fog Quality: Low.
- Cloud Quality: Low.
- Shadow Quality: Low.
- Effects Quality: Low.
- Lighting Quality: Medium.
- Terrain Quality: Medium.
- Simulation Quality: Low.
- Animation Quality: Medium.
- Flocking Quality: Low.
- Ground Cover Quality: Low.
- Decal Quality: Medium.
- Wind Quality: Off.
- High-Resolution Textures: Off.
- Fallback: 30 FPS for large co-op; FSR Balanced if required.

## Halo: The Master Chief Collection
### QAM
- Refresh rate: 60 Hz.
- FPS limit: 60.
- Allow Tearing: Off.
- Half-Rate Shading: Off.
- TDP Limit: Off.
- Manual GPU Clock: Off.
- Scaling Mode: Auto.
- Scaling Filter: Linear.
- SteamOS FSR: Off.
### Display
- Resolution: 1280x800.
- V-Sync: Off.
- MCC frame limit: 60.
- UI: Enhanced.
- Field of View: 85-90.
- HUD: Centered.
- FidelityFX: Off.
### Graphics
- Graphics mode: Enhanced.
- Anti-Aliasing: On.
- Detail Quality: High.
- Effects Quality: Medium.
- Lighting Quality: High.
- Shadow Quality: Medium.
- Texture Filtering: High.
- Texture Resolution: High.
- Water Quality: High.
- Fallback: Halo 2 Anniversary/Halo 4 at 40 Hz/cap 40; lower Effects and Shadows.

## DiRT 5
### QAM
- Refresh rate: 40 Hz.
- FPS limit: 40.
- Allow Tearing: Off.
- Half-Rate Shading: Off.
- TDP Limit: Off.
- Manual GPU Clock: Off.
- Scaling Mode: Auto.
- Scaling Filter: Linear.
- SteamOS FSR: Off.
### Display
- Resolution: Use the lowest exposed matching aspect-ratio option.
- Final Resolution: Match History Resolution and Render Resolution.
- History Resolution: Match Final Resolution and Render Resolution.
- Render Resolution: Match Final Resolution and History Resolution.
- V-Sync: Off.
- Dynamic Resolution: Off.
- Anti-Aliasing: TAA/default game option.
- FSR: Off.
- Motion Blur: Off.
### Graphics
- Geometry Quality: High.
- Tessellation Quality: Medium.
- Shadow Quality: Medium.
- Volumetric Lighting Quality: Medium.
- Cloud Quality: Medium.
- Procedural Quality: High.
- Global Illumination Quality: Medium.
- Track Quality: High.
- Vehicle Quality: High.
- Crowd Quality: Medium.
- Weather Quality: Medium.
- Ambient Occlusion: Medium.
- Screen Space Reflections: Low.
- Post Processing Quality: High.
- Fallback: 30 FPS; lower GI, Volumetrics, Shadows, then SSR.

## Update rule
When a new game is requested, append a menu-verified, fully vertical bespoke entry without changing existing rules or entries.