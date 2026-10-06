# Steam Deck Optimal Settings Library

## Permanent rules

### Settings and formatting
- Provide bespoke settings for each game and device, rather than a generic preset.
- List every QAM, AMD Adrenalin, Legion Space, display, and graphics control as a separate bullet where applicable.
- Use only controls supported by documented menus or the installed software.
- Mark controls as Not exposed only when their absence is verified.
- Mark unresolved controls as Unverified; do not invent settings or selectable values.
- Research published menus, documentation, and gameplay testing before requesting user screenshots.
- Ask the user only for specific details that available evidence cannot resolve.

### Performance evidence
- Prioritize the highest sustainable real FPS with consistent frametimes.
- Distinguish Recommended, Third-party measured, and Locally validated profiles.
- Recommended means a researched starting point without sufficient measurements to establish sustained performance.
- Third-party measured means results were captured on the same device model under documented conditions.
- Locally validated means results were captured on the user's device under documented conditions.
- Do not infer handheld performance from desktop benchmarks or a different handheld model.
- Do not describe a target, cap, average FPS, or video title as a performance guarantee.
- Count generated frames separately from real rendered frames.

### Measurement requirements
- Record the device model, game build, operating system, driver or Proton version, power profile, resolution, upscaler, and complete tested settings.
- Record the capture tool and its metric definitions.
- Report average FPS, 99th-percentile frametime, and notable stutters or target violations when available.
- State the tested scene, mode, capture duration, and number of runs.
- Include demanding combat or other representative worst-case scenes, not only menus or quiet traversal.
- Disclose missing data rather than estimate benchmark results.
- Describe results as valid for the recorded test conditions, not as guarantees for all gameplay.

### Validation protocol
- Use a warmed-up system and complete shader compilation where applicable.
- As a library testing standard, capture at least three repeat runs of the same representative route.
- Include a separate demanding-scene test.
- Define the target and acceptance criteria before testing.
- Report whether the profile passed those criteria and disclose exceptions.
- If evidence does not support the target, recommend a lower cap or revised settings and label them for further validation.

### Device-specific requirements
- Steam Deck: List QAM settings separately from display and graphics settings.
- Legion Go: Retain only Performance battery 20 W and Custom 25 W TDP / 25 W SPPT / 25 W FPPT profiles.
- Legion Go: Omit Performance plugged 25 W, Quiet 8 W, and Balanced 15 W.
- Use Integer Scaling only where the resolution, aspect ratio, and output scaling make it appropriate.
- Keep Radeon Image Sharpening Off by default; do not stack sharpening methods.

### Library maintenance
- Preserve existing game entries unless the user explicitly requests their revision.
- Append new entries using the complete current master files.
- Include evidence status, measured results where available, limitations, and fallback settings for each new title.
- Preserve the MARVEL Tōkon-only dropdown-verification exception.
- Require approval of the exact write before committing changes to GitHub.

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

## Warhammer 40,000: Space Marine 2
### QAM
- Refresh rate: 30 Hz.
- FPS limit: 30.
- Allow Tearing: Off.
- Half-Rate Shading: Off.
- TDP Limit: Off.
- Manual GPU Clock: Off.
- Scaling Mode: Auto.
- Scaling Filter: Linear.
- SteamOS FSR: Off.
- HDR: Not exposed in menu.
### Display
- Window mode: Fullscreen.
- Resolution: 1280x720.
- Render Resolution: Dynamic.
- Dynamic Resolution target: 30 FPS.
- Resolution Upscaling: FSR 2.
- Resolution Upscaling mode: Performance.
- V-Sync: Off.
- FPS Limit: 30.
- Motion Blur Intensity: Off.
### Graphics
- Preset: Low.
- Texture Filtering: High.
- Texture Resolution: Medium.
- Shadows: Low.
- Screen Space Ambient Occlusion: Default.
- Screen Space Reflections: Off.
- Volumetrics: Low.
- Effects: Low.
- Details: Low.
- Cloth Simulation: Low.
- Fallback: Keep the 30 FPS cap; lower the game resolution before using FSR Ultra Performance. Large horde encounters can still fall below 30 FPS.
When a new game is requested, append a menu-verified, fully vertical bespoke entry without changing existing rules or entries.

## MARVEL Tōkon: Fighting Souls
### Title-specific exception
- Scope: For this title only, complete dropdown-choice verification is waived by the user; values below are recommended starting points, not a menu-verified or device-tested profile.
- Preservation: Permanent rules and all other title entries remain unchanged.
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
- Display Mode: Borderless Window.
- Output Display: Built-in display.
- Brightness Settings: Default; adjust to the on-screen calibration.
- Motion Blur: Off.
- Resolution: 1280x720, if selectable.
- Vertical Sync: Off.
- Anti-aliasing Type: TSR, if selectable.
- Sharpness Quality: 0 initially; do not stack driver sharpening.
- Scaling Resolution: 50 initially, if selectable; this is an untested conservative Steam Deck recommendation.
### Graphics
- Graphics Quality: Custom.
- Auto Graphics Quality Settings: Do not run after applying this custom profile.
- Anti-aliasing Quality: Medium Quality, if selectable.
- Post-processing Quality: Medium Quality, if selectable.
- Global Illumination Quality: Low Quality, if selectable.
- Reflection Quality: Low Quality, if selectable.
- Texture Quality: Medium Quality, if selectable.
- Shadow Quality: Low Quality, if selectable.
- Effect Quality: Low Quality, if selectable.
- Launch Shader Warmup: On.
- Execute Shader Warmup: Run before first play and after game or driver updates.
- Revert to Defaults: Do not activate after applying this profile.
### Validation
- Target: 60 real FPS during battles; sustained performance is not verified on this device.
- Validation: Test demanding stages and multiple simultaneous effects before treating the profile as stable.
- Fallback: Reduce Scaling Resolution in small steps if GPU-limited; do not substitute generated frames for the battle target.
- Unverified controls: Confirm availability in the installed build; an unverified control is not classified as Not exposed.


## Necromunda: Hired Gun
### Evidence status
- Classification: Recommended; not Third-party measured or Locally validated under the library's measurement requirements.
- Game build: Unverified.
- OS, driver, and Proton versions: Not recorded for these recommendations.
- Average FPS: No qualifying capture available.
- 99th-percentile frametime: No qualifying capture available.
- Capture tool, duration, and repeat-run count: Not available.
- Limitation: Complete graphics-menu labels and values remain partly unverified; recommendations below are not a claim of complete menu verification.
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
- Screen Mode: Windowed Fullscreen.
- Resolution: 1280x800.
- V-Sync: Off.
- Motion Blur: Off.
- Field of View: 85, if selectable.
### Graphics
- Overall preset: Medium starting point; exact installed label is Unverified.
- FSR 1.0 mode: Ultra Quality.
- Anti-aliasing quality: High where exposed; exact installed label is Unverified.
- Texture quality: Unverified; retain the selected preset's value.
- Shadow quality: Unverified; retain the selected preset's value.
- Post-processing: Medium where exposed; exact installed label is Unverified.
- Special effects: Low where exposed; exact installed label is Unverified.
- Screen-space reflections: Unverified; retain the selected preset's value.
- Other individual quality controls: Unverified; do not add invented controls.
### Sources
- Steam Deck gameplay: https://www.youtube.com/watch?v=KeaEoaJxDHE
- Graphics feature reference: https://www.pcgamingwiki.com/wiki/Necromunda:_Hired_Gun
- PC performance discussion: https://www.reddit.com/r/NecromundaHiredGun/comments/nq6c2z/huge_performance_issues_on_pc_anyone_knows_any/
- FSR comparison: https://videocardz.com/newz/amd-fsr-and-nvidia-dlss-comparison-shows-similar-quality-and-performance-at-4k-resolution-in-necromunda-hired-gun
### Target and fallback
- Target: 60 real FPS, not guaranteed.
- Fallback: Use a 40 FPS cap with a compatible refresh rate if demanding combat cannot sustain 60 FPS; try FSR Quality if GPU-limited.
- Validation: Record three repeat combat captures plus a demanding-scene test before assigning validated status.
