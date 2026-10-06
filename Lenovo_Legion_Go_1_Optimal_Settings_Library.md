# Lenovo Legion Go 1 Optimal Settings Library

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
### AMD Adrenalin
- GPU Scaling: On.
- Scaling Mode: Full Panel.
- Integer Scaling: On at 1280x800.
- Radeon Super Resolution: Off.
- Radeon Image Sharpening: Off.
- Anti-Lag: On.
- Enhanced Sync: Off.
- AFMF: Off.
- Chill: Off.
### Legion Space — Performance battery 20 W
- Operating mode: Performance.
- TDP: 20 W.
- Refresh rate: 120 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 90.
### Legion Space — Custom 25/25/25
- Operating mode: Custom.
- TDP: 25 W.
- SPPT: 25 W.
- FPPT: 25 W.
- Refresh rate: 120 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 120.
### Display and graphics
- Resolution: 1280x800.
- V-Sync: Off.
- Field of View: 100.
- Motion Blur: Off.
- Depth of Field: Off.
- Chromatic Aberration: Off.
- Film Grain: Off.
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

## Killing Floor 3
### AMD Adrenalin
- GPU Scaling: On.
- Scaling Mode: Full Panel.
- Integer Scaling: On at 1280x800.
- Radeon Super Resolution: Off.
- Radeon Image Sharpening: Off.
- Anti-Lag: On.
- Enhanced Sync: Off.
- AFMF: Off.
- Chill: Off.
### Legion Space — Performance battery 20 W
- Operating mode: Performance.
- TDP: 20 W.
- Refresh rate: 120 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 40.
### Legion Space — Custom 25/25/25
- Operating mode: Custom.
- TDP: 25 W.
- SPPT: 25 W.
- FPPT: 25 W.
- Refresh rate: 120 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 40.
### Display and graphics
- Resolution: 1280x800.
- V-Sync: Off.
- Frame Rate Cap: 40.
- Field of View: 90.
- FOV Scaling Axis: Default.
- Motion Blur: Off.
- Depth of Field: Off.
- Film Grain: Off.
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
- Global Illumination Method: Lowest non-Lumen option where exposed.
- Supersampling Mode: Off.
- Quality Mode: Performance or equivalent.
- Frame Generation: Off unless exposed in the installed build and separately tested.

## God of War (2018)
### AMD Adrenalin
- GPU Scaling: On.
- Scaling Mode: Full Panel.
- Integer Scaling: On at 1280x800.
- Radeon Super Resolution: Off.
- Radeon Image Sharpening: Off.
- Anti-Lag: Off.
- Enhanced Sync: Off.
- AFMF: Off.
- Chill: Off.
### Legion Space — Performance battery 20 W
- Operating mode: Performance.
- TDP: 20 W.
- Refresh rate: 90 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 45.
### Legion Space — Custom 25/25/25
- Operating mode: Custom.
- TDP: 25 W.
- SPPT: 25 W.
- FPPT: 25 W.
- Refresh rate: 60 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 60.
### Display and graphics
- Resolution: 1280x800.
- Window mode: Borderless.
- V-Sync: Off.
- Upscaler: FSR 2.0.
- Upscaler mode: Quality.
- Sharpening: 0.2.
- Motion Blur: Off.
- Film Grain: Off.
- Texture Quality: Original.
- Model Quality: Original.
- Anisotropic Filtering: High.
- Shadow Quality: Low.
- Reflection Quality: Original.
- Atmospherics Quality: Low.
- Ambient Occlusion: Original.

## Project CARS 3
### AMD Adrenalin
- GPU Scaling: On.
- Scaling Mode: Preserve Aspect Ratio.
- Integer Scaling: On only with 1280x800 output.
- Radeon Super Resolution: Off.
- Radeon Image Sharpening: Off.
- Anti-Lag: On.
- Enhanced Sync: Off.
- AFMF: Off.
- Chill: Off.
### Legion Space — Performance battery 20 W
- Operating mode: Performance.
- TDP: 20 W.
- Refresh rate: 60 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 60.
### Legion Space — Custom 25/25/25
- Operating mode: Custom.
- TDP: 25 W.
- SPPT: 25 W.
- FPPT: 25 W.
- Refresh rate: 60 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 60.
### Display and graphics
- Resolution: 1280x800 if exposed; otherwise use the lowest suitable 16:9 resolution with Preserve Aspect Ratio.
- Window mode: Exclusive Fullscreen.
- V-Sync: Off.
- Super Sampling: Off.
- Anti-Aliasing: Use the game’s built-in/default behavior; do not invent a separate SMAA/FXAA/TAA control.
- Texture Resolution: High.
- Texture Filtering: 16x.
- Geometry Quality: High.
- Tessellation Quality: Medium for 20 W; High for Custom.
- Shadow Quality: Medium for 20 W; High for Custom.
- Reflection Quality: Medium.
- Environment Map: Medium.
- Car Detail: High.
- Mirror Quality: Standard.
- Detailed Grass: On.
- Particle Quality: High.
- Particle Density: High.
- Post Processing Quality: High.
- Fallback: 90 Hz/45 FPS for wet, night, cockpit, or large-grid events; lower Reflections first.

## Cyberpunk 2077
### AMD Adrenalin
- GPU Scaling: On.
- Scaling Mode: Full Panel.
- Integer Scaling: On at 1280x800.
- Radeon Super Resolution: Off.
- Radeon Image Sharpening: Off.
- Anti-Lag: Off.
- Enhanced Sync: Off.
- AFMF: Off for the base profile.
- Chill: Off.
### Legion Space — Performance battery 20 W
- Operating mode: Performance.
- TDP: 20 W.
- Refresh rate: 120 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 40.
### Legion Space — Custom 25/25/25
- Operating mode: Custom.
- TDP: 25 W.
- SPPT: 25 W.
- FPPT: 25 W.
- Refresh rate: 120 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 40.
### Display and graphics
- Resolution: 1280x800.
- Window mode: Fullscreen.
- V-Sync: Off.
- Max FPS: 40.
- Upscaler: FSR 3.
- Upscaler mode: Balanced at 20 W; Quality on Custom where stable.
- Sharpening: 0.
- Frame Generation: Off for the base profile.
- Field of View: 80.
- Motion Blur: Off.
- Film Grain: Off.
- Chromatic Aberration: Off.
- Depth of Field: Off.
- Lens Flare: On.
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

## Hitman: Absolution
### AMD Adrenalin
- GPU Scaling: On.
- Scaling Mode: Preserve Aspect Ratio.
- Integer Scaling: Off for 16:9 output.
- Radeon Super Resolution: Off.
- Radeon Image Sharpening: Off.
- Anti-Lag: On.
- Enhanced Sync: Off.
- AFMF: Off.
- Chill: Off.
### Legion Space — Performance battery 20 W
- Operating mode: Performance.
- TDP: 20 W.
- Refresh rate: 120 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 90.
### Legion Space — Custom 25/25/25
- Operating mode: Custom.
- TDP: 25 W.
- SPPT: 25 W.
- FPPT: 25 W.
- Refresh rate: 120 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 120.
### Display and graphics
- Resolution: 1280x720.
- Window mode: Fullscreen.
- V-Sync: Off.
- Post-process Anti-Aliasing: High.
- MSAA: Off.
- Anisotropic Filtering: 16x.
- Motion Blur: Off.
- Depth of Field: Normal.
- Bloom: Normal.
- Texture Quality: High.
- Shadow Quality: High.
- Level of Detail: High.
- Post Processing Quality: Medium.
- Ambient Occlusion: High.
- Tessellation: On.

## Halo Infinite
### AMD Adrenalin
- GPU Scaling: On.
- Scaling Mode: Full Panel.
- Integer Scaling: On at 1280x800.
- Radeon Super Resolution: Off.
- Radeon Image Sharpening: Off.
- Anti-Lag: On.
- Enhanced Sync: Off.
- AFMF: Off.
- Chill: Off.
### Legion Space — Performance battery 20 W
- Operating mode: Performance.
- TDP: 20 W.
- Refresh rate: 120 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 60.
### Legion Space — Custom 25/25/25
- Operating mode: Custom.
- TDP: 25 W.
- SPPT: 25 W.
- FPPT: 25 W.
- Refresh rate: 120 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 60.
### Display and graphics
- Resolution: 1280x800.
- V-Sync: Off.
- Minimum FPS: 60.
- Maximum FPS: 60.
- Dynamic Resolution: On.
- Minimum Dynamic Resolution Scale: 80%.
- Upscaler: FSR 2 where exposed.
- Sharpening: 15.
- Async Compute: On.
- Field of View: 90.
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

## Halo: The Master Chief Collection
### AMD Adrenalin
- GPU Scaling: On.
- Scaling Mode: Full Panel.
- Integer Scaling: On at 1280x800.
- Radeon Super Resolution: Off.
- Radeon Image Sharpening: Off.
- Anti-Lag: On.
- Enhanced Sync: Off.
- AFMF: Off.
- Chill: Off.
- Easy Anti-Cheat: Enabled for matchmaking.
### Legion Space — Performance battery 20 W
- Operating mode: Performance.
- TDP: 20 W.
- Refresh rate: 90 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 90 for lighter titles.
### Legion Space — Custom 25/25/25
- Operating mode: Custom.
- TDP: 25 W.
- SPPT: 25 W.
- FPPT: 25 W.
- Refresh rate: 120 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 120 for Reach/CE/Halo 3/ODST.
### Display and graphics
- Resolution: 1280x800.
- V-Sync: Off.
- MCC frame limit: Match Legion Space cap.
- UI: Enhanced.
- Field of View: 90.
- HUD: Centered.
- FidelityFX: Off.
- Graphics Mode: Enhanced.
- Anti-Aliasing: On.
- Detail Quality: High.
- Effects Quality: High for lighter titles; Medium for Halo 2 Anniversary/Halo 4.
- Lighting Quality: High.
- Shadow Quality: Medium.
- Texture Filtering: High.
- Texture Resolution: High.
- Water Quality: High.
- Halo 2 Anniversary/Halo 4 fallback: Integer Scaling Off, 2560x1600, 60 Hz, 60 FPS, Effects/Shadow Medium.

## DiRT 5
### AMD Adrenalin
- GPU Scaling: On.
- Scaling Mode: Full Panel at 1280x800; Preserve Aspect Ratio for 16:9.
- Integer Scaling: On only at 1280x800.
- Radeon Super Resolution: Off.
- Radeon Image Sharpening: Off.
- Anti-Lag: On.
- Enhanced Sync: Off.
- AFMF: Off.
- Chill: Off.
### Legion Space — Performance battery 20 W
- Operating mode: Performance.
- TDP: 20 W.
- Refresh rate: 60 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 60.
### Legion Space — Custom 25/25/25
- Operating mode: Custom.
- TDP: 25 W.
- SPPT: 25 W.
- FPPT: 25 W.
- Refresh rate: 60 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 60.
### Display and graphics
- Final Resolution: Match History Resolution and Render Resolution.
- History Resolution: Match Final Resolution and Render Resolution.
- Render Resolution: Match Final Resolution and History Resolution.
- Resolution value: 1280x800 if exposed; otherwise lowest suitable matching aspect ratio.
- V-Sync: Off.
- Dynamic Resolution: Off.
- Anti-Aliasing: TAA/default game option.
- FSR: Off.
- Motion Blur: Off.
- Geometry Quality: High.
- Tessellation Quality: Medium at 20 W; High on Custom.
- Shadow Quality: Medium at 20 W; High on Custom.
- Volumetric Lighting Quality: Medium.
- Cloud Quality: Medium.
- Procedural Quality: High.
- Global Illumination Quality: Medium.
- Track Quality: High.
- Vehicle Quality: High.
- Crowd Quality: Medium at 20 W; High on Custom if stable.
- Weather Quality: Medium at 20 W; High on Custom if stable.
- Ambient Occlusion: Medium at 20 W; High on Custom if stable.
- Screen Space Reflections: Medium at 20 W; Low in wet/night fallback.
- Post Processing Quality: High.
- Fallback: 90 Hz/45 FPS; lower GI, Volumetrics, Shadows, then SSR.

## Update rule

## Warhammer 40,000: Space Marine 2
### AMD Adrenalin
- GPU Scaling: On.
- Scaling Mode: Full Panel.
- Integer Scaling: On at 1280x800.
- Radeon Super Resolution: Off.
- Radeon Image Sharpening: Off.
- Anti-Lag: On.
- Enhanced Sync: Off.
- AFMF: Off for the base profile.
- Chill: Off.
### Legion Space — Performance battery 20 W
- Operating mode: Performance.
- TDP: 20 W.
- Refresh rate: 60 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 30.
### Legion Space — Custom 25/25/25
- Operating mode: Custom.
- TDP: 25 W.
- SPPT: 25 W.
- FPPT: 25 W.
- Refresh rate: 60 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 30.
### Display and graphics
- Resolution: 1280x800.
- Window mode: Fullscreen.
- V-Sync: Off.
- Frame rate limit: 30 FPS.
- Dynamic Resolution: On.
- Dynamic Resolution FPS target: 30 FPS.
- Resolution Upscaling: FSR.
- Resolution Upscaling mode: Quality at 20 W; Balanced on Custom only if 30 FPS is not sustainable.
- Frame Generation: Off for the base profile.
- Motion Blur: Off.
- Texture Filtering: Ultra.
- Texture Resolution: Medium.
- Shadows: Low.
- SSAO: Default.
- Screen Space Reflections: Default.
- Volumetrics: Low.
- Effects: Low.
- Details: Medium.
- Cloth Simulation: Low.
- Fallback: Keep the 30 FPS cap; switch FSR Quality to Balanced before lowering Texture Resolution or Details. Heavy swarm, Operations, and Siege encounters can still fall below target.

## MARVEL Tōkon: Fighting Souls
### Title-specific exception
- Scope: For this title only, complete dropdown-choice verification is waived by the user; values below are recommended starting points, not a menu-verified or device-tested profile.
- Preservation: Permanent rules and all other title entries remain unchanged.
### AMD Adrenalin
- GPU Scaling: On.
- Scaling Mode: Preserve Aspect Ratio.
- Integer Scaling: Off for 1280x720 output.
- Radeon Super Resolution: Off.
- Radeon Image Sharpening: Off.
- Anti-Lag: On, if available for this game.
- Enhanced Sync: Off.
- AFMF: Off.
- Chill: Off.
### Legion Space — Performance battery 20 W
- Operating mode: Performance.
- TDP: 20 W.
- Refresh rate: 60 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 60.
### Legion Space — Custom 25/25/25
- Operating mode: Custom.
- TDP: 25 W.
- SPPT: 25 W.
- FPPT: 25 W.
- Refresh rate: 60 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 60.
### Display
- Display Mode: Borderless Window.
- Output Display: Built-in display.
- Brightness Settings: Default; adjust to the on-screen calibration.
- Motion Blur: Off.
- Resolution: 1280x720, if selectable.
- Vertical Sync: Off.
- Anti-aliasing Type: TSR, if selectable.
- Sharpness Quality: 0 initially; do not stack driver sharpening.
- Scaling Resolution: 70 initially for both profiles, if selectable; raise only after validating sustained 60 FPS.
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
### AMD Adrenalin
- GPU Scaling: On.
- Scaling Mode: Full Panel.
- Integer Scaling: On at 1280x800.
- Radeon Super Resolution: Off.
- Radeon Image Sharpening: Off.
- Anti-Lag: On if available for the game.
- Enhanced Sync: Off.
- AFMF: Off.
- Chill: Off.
### Legion Space — Performance battery 20 W
- Operating mode: Performance.
- TDP: 20 W.
- Refresh rate: 60 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 60.
### Legion Space — Custom 25/25/25
- Operating mode: Custom.
- TDP: 25 W.
- SPPT: 25 W.
- FPPT: 25 W.
- Refresh rate: 60 Hz.
- Fan mode: Performance/Full Fan while validating.
- FPS cap: 60.
### Display
- Screen Mode: Windowed Fullscreen.
- Resolution: 1280x800.
- V-Sync: Off.
- Motion Blur: Off.
- Field of View: 85, if selectable.
### Graphics
- Overall preset: Medium starting point at 20 W; High starting point on Custom. Exact installed labels are Unverified.
- FSR 1.0 mode: Off initially; Ultra Quality if GPU-limited below target.
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
- Target: 60 real FPS for both power profiles, not guaranteed.
- Fallback: Lower the overall preset or enable FSR Ultra Quality before reducing output resolution; use a 30 FPS cap at 60 Hz if no stable higher target is achievable.
- Validation: Benchmark each power profile separately using three repeat combat captures and a demanding-scene test.
