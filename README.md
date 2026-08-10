## Description
WSTFG stands for Weapon Sounds Tweaks and Fixes for [G.A.M.M.A.](https://github.com/Grokitach/Stalker_GAMMA)
It is a weapon audio overhaul based on [Dark Signal Weapon Audio](https://www.moddb.com/mods/stalker-anomaly/addons/dark-signal-stand-alone-weapon-audio)

## Installation
*WSTFG is included in GAMMA by default (version 3.0.5), but GAMMA launcher pulls updates only on GAMMA update releases*
1. Download the latest release archive *(do not extract it)*: <https://github.com/oleh5230/WSTFG/releases>
2. In Mod Organizer, go to `File` > `Install Mod...` (or press `Ctrl` + `M`)
3. Select the downloaded archive
4. Enable the installed mod
5. Check dependecies below

**Load order (priority) does not matter, keep it below default GAMMA addons**

**Disabling default GAMMA sound addons is not required**

## Dependencies
[MSIG](https://github.com/oleh5230/MSIG) (version 2026.08.10 or newer)

## Troubleshooting
- Gunfire sounds are missing: make sure `weapon_sounds.ltx` is not overwritten
- Can't open section 'scripted_snd_*' error: update your exes
- Gunfire Volume sliders are ineffective: update your exes

## Recommended in-game settings:
- SFX Volume (`snd_volume_eff`): `0.5` - otherwise sounds may be louder/quieter than intended
- Rendering Distance (World) (`rs_vis_distance`): at least `0.9` (50% of the slider) - otherwise distant gunfire sounds would not be audible

## Recommended addons
Only sound addons I use personally (excluding default GAMMA addons)
- [Spatial Audio Rework](https://www.moddb.com/mods/stalker-anomaly/addons/spatial-audio-rework)
- [S.T.A.L.K.E.R. 2 HoC - Soundscape](https://www.moddb.com/mods/stalker-anomaly/addons/stalker-2-hoc-ambience-overhaul-for-anomaly)
- [Arrival](https://www.moddb.com/mods/stalker-anomaly/addons/arrival-anomalies)
- [MovementSFX](https://github.com/oleh5230/MovementSFX)
- [Ukrainian voices](https://www.moddb.com/addons/dxml-anomaly-ukrainian-voices)

## Credits
- **Shrike**: a lot of gunfire sounds
- **YungPr1nce**: a lot of foley sounds included directly or reused as material
- **TheDJ**: multiple resounds, help with sources and general advice
- **relax_68**: multiple foley resounds
- **HarukaSai**: original low ammo hint script
- **Qudix**: original aim rattle script
- **bert**: original casings falling sounds port
- **The_aphrodite_child**: indoor tails sources
- **Varian**: indoor configs

## Features
- Dark Signal gunfire sounds overhaul: redistributed and tweaked gunshot sounds, as well as addition of new ones, aiming for quality over quantity.
- Suppressed gunfire sounds overhaul
- Inclusion of better sounds from various addons
- Sound synchronisation with animations
- Custom foley sound replacements
- Volume adjustments
- Multitude of bug fixes
- Edited and custom scripts:
  - Grok's & Bert's Casings Falling Sounds Revised
  - Weapon rattle
  - Enhanced dryfire
  - Low ammo sounds
  - Scope zoom adjustment sounds
  - Gunfire volume settings
