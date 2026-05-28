# OpenFPS
 OpenFPS is a project that aims to help people build first-person shooter (FPS) games in Godot, as this field is lacking interest around the godot community.

# Requirements:
 - **Godot 4.6+** (Forward Plus renderer)

# Features:
 1. Basic FPS character controller.
 2. Weapon system that supports only a gun as of now.
 3. Reloading mechanism that works.
 4. An enemy.
 5. Hitscan weapon mechanisem.
 6. HUD showing remaining bullets.
 7. An open enivronment for future contributions.
 
By using OpenFPS, you can save yourself a significant amount of time and effort in building your own FPS game.

OpenFPS is still under development, but it is a valuable resource for anyone who wants to build an FPS game in Godot.

# Demo:



https://github.com/user-attachments/assets/9f729762-60f7-4c99-8dfa-f62edb01e430


# LICENSING:
Code is licensed under MIT License.

All assets are licensed under [Creative Commons (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

# Crediting:
Crediting this project isn't required but is highly appreciated

# Migration Notes (4.3 → 4.6):
 - Updated project target from Godot 4.3 to Godot 4.6.
 - Replaced deprecated `AnimationPlayer.play_backwards()` calls with `play()` using a negative `custom_speed` parameter.
 - Updated SphynxMotionBlurToolkit addon version tag to 4.6 (CompositorEffect API unchanged).
 - Removed hardcoded local editor paths from project settings.
 - Export presets reviewed for Linux, Windows, and macOS compatibility.
 - After opening in Godot 4.6, allow the editor to re-import assets and re-save `.tscn`/`.tres` files when prompted.
 - Test the following flows after upgrading: player movement/jump, firing/hitscan, reload, ADS/inspect, HUD, enemy death, and nuke/tablet sequence.
