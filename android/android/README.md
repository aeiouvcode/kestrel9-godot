# KESTREL-9 Android source

Editable Godot 4 project for the Android version of KESTREL-9. Open `project.godot` in Godot 4. The existing root `index.*` files remain the separate web export.

The campaign includes nine missions and 29 stops. Tap anywhere to aim and fire at that point; hold to auto-fire and use MODE to switch semi/auto. Cover, reload, defusal, overwatch, armory, holdout and the campaign ending are included.

Run `node control-kestrel.mjs doctor` and `node control-kestrel.mjs interact --action smoke` for source checks. Android export uses `export_presets.cfg`; the signed APK is attached to the v1.1 release. Physical-device input and frame pacing have not yet been checked.
