# Steam Deck Optimal Settings Library

## Permanent rules
- Steam Deck-specific settings only.
- Bespoke settings for every game.
- Include QAM, display, resolution, AA/upscaling, graphics, stable FPS target, and fallback.
- Prioritize stable frametimes over peak FPS.
- Do not transfer Legion Go settings into this file.

## DOOM Eternal
- Target: 60 FPS at 60 Hz; 90 FPS is a secondary test target only.
- QAM: 60 Hz, cap 60, Allow Tearing Off, Half-Rate Shading Off, TDP Off, Manual GPU Clock Off, Scaling Auto, Filter Linear, SteamOS FSR Off.
- Display: Fullscreen, 1280x800, V-Sync Off, FOV 100, Motion Blur Off, DOF Off, Chromatic Aberration Off, Film Grain Off, HDR Off.
- Graphics: Texture Pool Ultra Nightmare, Filtering Ultra Nightmare, Geometry High, Shadows Medium, Reflections Medium, Directional Occlusion High, Lights High, Particles High, Decals High, Water High, Volumetrics Medium, RT Off.
- Fallback: Volumetrics Medium -> Reflections Medium -> Shadows Low.

## Killing Floor 3
- Target: 40 FPS; 30 FPS fallback for full co-op or heavy waves.
- QAM: 40 Hz/cap 40; use 60 Hz/cap 30 for fallback; TDP/GPU Clock Off; scaling Auto; SteamOS FSR Off.
- Display: 1280x720, V-Sync Off, Dynamic Resolution Off, XeSS Balanced, sharpening low, Motion Blur/DOF/Film Grain/CA Off.
- Graphics: View Distance/Post Processing/Shadows/GI/Reflections/Effects/Foliage/Shading Low; Textures Low/Medium; Lumen GI/Reflections Off; SSR where available.
- Fallback: XeSS Performance, then lower Effects and Shadows.

## God of War (2018)
- Target: 40 FPS at 40 Hz; 30 FPS visual-quality fallback.
- QAM: 40 Hz/cap 40; tearing/half-rate/TDP/GPU Clock Off; scaling Auto; SteamOS FSR Off.
- Display: 1280x720, Borderless, V-Sync Off, FSR 2 Quality, sharpening 0.3, Motion Blur/Film Grain Off.
- Graphics: Textures Original, Models Original, AF High, Shadows Low, Reflections Original, Atmospherics Low, AO Original.
- Fallback: 30 Hz/cap 30; raise Shadows to Original only if stable.

## Project CARS 3
- Target: 60 FPS; 45 FPS at 90 Hz for rain/night/cockpit/large grids.
- QAM: 60 Hz/cap 60; fallback 90 Hz/cap 45; TDP/GPU Clock Off; scaling Auto; filter Linear.
- Display: Fullscreen, 1280x720, V-Sync Off, one resolution setting, Super Sampling Off, game-controlled AA, FSR Off, Motion Blur Off.
- Graphics: Textures High, Filtering 16x, Geometry High, Tessellation High, Shadows High, Reflections Medium, Environment Map Medium, Car/Track High, Mirrors Standard, Grass On, Particles/Density High, Post Processing High.
- Fallback: Lower Reflections first; do not force hidden SMAA/FXAA values.

## Cyberpunk 2077
- Target: 40 FPS; 30 FPS Dogtown/Phantom Liberty fallback.
- QAM: 40 Hz/cap 40; fallback 60 Hz/cap 30; tearing/half-rate/TDP/GPU Clock Off; SteamOS FSR Off.
- Display: 1280x720, FSR 2.1 Balanced, sharpening 0.2, Frame Generation Off, FOV 80, Motion Blur/Film Grain/CA/DOF Off, Lens Flare On.
- Graphics: Textures High, Crowd Low, Contact Shadows Off, Facial Lighting On, AF 8x, shadows/fog/clouds Low, Decals Medium, SSR Low, SSS/AO/Color/Mirrors/LOD Medium, RT/PT Off.
- Fallback: FSR Performance, then SSR and fog/clouds lower.

## Hitman: Absolution
- Target: 60 FPS; 40 FPS is the quality/heat fallback.
- QAM: 60 Hz/cap 60; fallback 40 Hz/cap 40; tearing/half-rate/TDP/GPU Clock Off; scaling Auto.
- Display: Fullscreen, 1280x720, V-Sync Off, post-process AA High, MSAA Off, AF 16x, Motion Blur Off.
- Graphics: Textures High, Shadows High, LOD High, Post Processing Medium, AO High, DOF Normal, Bloom Normal, Tessellation On.
- Fallback: Shadows Medium.

## Halo Infinite
- Target: 40 FPS Campaign; 60 FPS lighter multiplayer scenes.
- QAM: 40 Hz/cap 40; fallback 60 Hz/cap 30; tearing/half-rate/TDP/GPU Clock Off.
- Video: 1280x720, DRS On, minimum scale 85%, FSR 2 Quality, sharpening 20, Async Compute On, FOV 78, V-Sync Off.
- Graphics: Textures Medium, Filtering 4x, Geometry Medium, Reflections/Fog/Clouds/Shadows/Effects Low, Lighting/Details/Animation/Terrain Medium, Simulation Low, Flocking/Wind Off, Ground Cover Low, Decals Medium, high-resolution texture DLC Off.
- Fallback: FSR Balanced and lower Effects/Clouds.

## Halo: The Master Chief Collection
- Target: 60 FPS Enhanced; 40 FPS fallback for Halo 2 Anniversary/Halo 4.
- QAM: 60 Hz/cap 60; tearing/half-rate/TDP/GPU Clock Off; scaling Auto; Filter Linear.
- Display: 1280x800, V-Sync Off, MCC limit 60, UI Enhanced, FOV 85-90, HUD Centered, FidelityFX Off.
- Graphics: Enhanced, AA On, Details High, Effects Medium, Lighting High, Shadows Medium, Texture Filtering/Resolution High, Water High.
- Fallback: 40 Hz/cap 40 for demanding campaigns; Effects and Shadows Low.

## DiRT 5
- Target: 40 FPS; 30 FPS visual-quality fallback.
- QAM: 40 Hz/cap 40; fallback 60 Hz/cap 30; tearing/half-rate/TDP/GPU Clock Off; scaling Auto.
- Resolution: Final Resolution, History Resolution, and Render Resolution must match; use 1280x800 if exposed, otherwise the lowest matching 16:9 option.
- Graphics: Geometry High, Tessellation Medium, Shadows Medium, Volumetric Lighting Medium, Clouds Medium, Procedural High, GI Medium, Track/Vehicle High, Crowd Medium, Weather Medium, AO Medium, SSR Low, Post Processing High, TAA/default AA, FSR Off, Motion Blur Off.
- Fallback: GI/Volumetrics/Shadows Low; SSR Off.

## Update rule
When a new game is requested, append a complete bespoke entry while preserving all existing entries and permanent rules.