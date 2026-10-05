# Lenovo Legion Go 1 Optimal Settings Library

## Permanent rules
- Legion Go 1-specific settings only.
- Bespoke settings for every game.
- Retained profiles: Performance battery 20 W; Performance plugged in 25 W; Custom 25 W TDP / 25 W SPPT / 25 W FPPT.
- Quiet 8 W and Balanced 15 W are omitted.
- Include AMD Adrenalin, Integer Scaling, Legion Space, display, resolution, AA/upscaling, graphics, FPS targets, and fallbacks.
- Integer Scaling is default where an appropriate 1280x800 path exists.
- RIS, RSR, AFMF, and Chill are Off unless explicitly noted.
- Prioritize stable real FPS.

## DOOM Eternal
- AMD: GPU Scaling On, Full Panel, Integer Scaling On at 1280x800, RSR/RIS/AFMF/Chill Off, Anti-Lag On, Enhanced Sync Off.
- Performance battery 20 W: 90 FPS, 120 Hz, 1280x800, V-Sync Off, FOV 100, blur/DOF/CA/film grain Off; Texture Pool/Filtering/Geometry Ultra Nightmare, Shadows/Reflections Medium, Directional Occlusion/Lights High, Particles/Decals/Water High, Volumetrics Medium, RT Off.
- Performance plugged 25 W: 120 FPS, 120 Hz, same resolution; Geometry/Textures/Filtering Ultra Nightmare, Shadows/Reflections/DO/Lights/Decals/Water High, Particles Ultra, Volumetrics High, RT Off.
- Custom 25/25/25: same 120 FPS profile; fallback Volumetrics Medium -> Reflections Medium -> Shadows Medium.

## Killing Floor 3
- AMD: GPU Scaling On, Full Panel, Integer Scaling On, RSR/RIS/AFMF/Chill Off, Anti-Lag On.
- Performance battery 20 W: 40 FPS, 120 Hz, 1280x800, XeSS Balanced, sharpening 0, blur/DOF/film grain/CA Off; View Distance/Post Processing/Shadows/GI/Reflections/Effects/Foliage/Shading Low, Textures Medium, Lumen GI/Reflections Off.
- Performance plugged 25 W: 40 FPS, same display and graphics; use XeSS Quality only if stable.
- Custom 25/25/25: 40 FPS, same profile; 60 FPS experiment uses XeSS Performance and low effects but is not preferred.

## God of War (2018)
- AMD: GPU Scaling On, Full Panel, Integer Scaling On at 1280x800, RSR/RIS/AFMF/Chill Off.
- Performance battery 20 W: 45 FPS, 90 Hz, Borderless, 1280x800, FSR 2 Quality, sharpening 0.2, blur/film grain Off; Textures/Models Original, AF High, Shadows Low, Reflections Original, Atmospherics Low, AO Original.
- Performance plugged 25 W: 60 FPS, 60 Hz, same 1280x800 and graphics values.
- Custom 25/25/25: 60 FPS, same profile; native exception uses Integer Scaling Off, 2560x1600, 40 FPS, FSR 2 Quality.

## Project CARS 3
- AMD: GPU Scaling On, Preserve Aspect Ratio, Integer Scaling On at 1280x800, RSR/RIS Off, Anti-Lag On, AFMF/Chill Off.
- Performance battery 20 W: 60 FPS, 60 Hz, Exclusive Fullscreen, 1280x800, V-Sync Off, game-controlled AA, Super Sampling/FSR Off, Motion Blur Off; Texture High, Filtering 16x, Geometry High, Tessellation Medium, Shadows Medium, Reflections/Environment Map Medium, Car/Track High, Mirrors Standard, Grass On, Particles/Density High, Post Processing High.
- Performance plugged 25 W: 60 FPS, same resolution; Geometry/Tessellation/Shadows High, other settings as above.
- Custom 25/25/25: 60 FPS, same profile; wet/night/cockpit fallback 90 Hz/45 FPS; raise Reflections/Environment Map only if stable. Do not force hidden SMAA/FXAA values.

## Cyberpunk 2077
- AMD: GPU Scaling On, Full Panel, Integer Scaling On at 1280x800, RSR/RIS/AFMF/Chill/Anti-Lag Off, RT/PT Off.
- Performance battery 20 W: 40 FPS, 120 Hz, 1280x800, FSR 3 Balanced, sharpening 0, FG Off, FOV 80, blur/film grain/CA/DOF Off; Textures High, Crowd Low, Contact Shadows Off, Facial Lighting On, AF 8x, shadows/fog/clouds Low, Decals Medium, SSR Low, SSS/AO/Color/Mirrors/LOD Medium.
- Performance plugged 25 W: 40 FPS, FSR 3 Quality, same settings; Dogtown fallback FSR Balanced.
- Custom 25/25/25: 40 FPS, FSR 3 Quality; optional FG experiment at 60 output is not equivalent to native 60 FPS.

## Hitman: Absolution
- AMD: GPU Scaling On, Preserve Aspect Ratio, Integer Scaling Off for 16:9 output, RSR/RIS Off, Anti-Lag On, AFMF/Chill Off.
- Performance battery 20 W: 90 FPS, 120 Hz, 1280x720, post-process AA High, MSAA Off, AF 16x, blur Off; Textures/Shadows/LOD High, Post Processing Medium, AO High, DOF Normal, Bloom Normal, Tessellation On.
- Performance plugged 25 W: 120 FPS, 120 Hz, same settings.
- Custom 25/25/25: 120 FPS, same settings; lower Shadows to Medium if needed.

## Halo Infinite
- AMD: GPU Scaling On, Full Panel, Integer Scaling On, RSR/RIS/AFMF/Chill Off, Anti-Lag On, high-resolution textures DLC Off.
- Performance battery 20 W: 60 FPS, 120 Hz, 1280x800, DRS On, minimum scale 80%, FSR 2 Quality, sharpening 15, Async Compute On, FOV 90; Texture Medium, Filtering 4x, Geometry Medium, Reflections/Fog/Clouds/Shadows/Effects Low, Lighting/Details/Animation/Terrain Medium, Simulation/Ground Cover Low.
- Performance plugged 25 W: 60 FPS, same profile.
- Custom 25/25/25: 60 FPS, same profile; 120 FPS experiment uses FSR Balanced, minimum scale 65-70%, and low effects, but is not the preferred quality target.

## Halo: The Master Chief Collection
- AMD: GPU Scaling On, Full Panel, Integer Scaling On at 1280x800, RSR/RIS/AFMF/Chill Off, Anti-Lag On; EAC enabled for matchmaking.
- Performance battery 20 W: 90 FPS for lighter titles, 90 Hz, 1280x800, MCC limit 90, Enhanced, AA On, Details/Effects/Lighting High, Shadows Medium, Texture Filtering/Resolution High, Water High.
- Performance plugged 25 W: 120 FPS for Reach/CE/Halo 3/ODST, 120 Hz, same graphics.
- Custom 25/25/25: 120 FPS for lighter titles; Halo 2 Anniversary/Halo 4 fallback 60 Hz/60 FPS, Integer Scaling Off, 2560x1600, Effects/Shadows Medium, other settings High.

## DiRT 5
- AMD: GPU Scaling On, Full Panel for 1280x800, Preserve Aspect Ratio for 16:9, Integer Scaling On only at 1280x800, RSR/RIS/AFMF/Chill Off, Anti-Lag On.
- Performance battery 20 W: 60 FPS, 60 Hz; Final/History/Render Resolution all match at 1280x800 if exposed; Geometry High, Tessellation/Shadows/Volumetric Lighting/Clouds Medium, Procedural High, GI Medium, Track/Vehicle High, Crowd/Weather Medium, AO Medium, SSR Medium, Post Processing High, TAA/default AA, FSR Off, Motion Blur Off.
- Performance plugged 25 W: 60 FPS, same matched resolution; raise Geometry/Tessellation/Shadows/Procedural/GI/Track/Vehicle/Crowd/Weather/AO to High, Clouds Medium, SSR Medium.
- Custom 25/25/25: 60 FPS, same profile; wet/night/cockpit fallback 90 Hz/45 FPS with GI/Volumetrics/Shadows Medium and SSR Low.

## Update rule
When a new game is requested, append a complete bespoke entry to both master files while preserving all existing entries and permanent rules. Quiet and Balanced profiles remain omitted.