# Godot-XR by Diguifi
This is just a full implementation of the [official docs](https://docs.godotengine.org/en/stable/tutorials/xr/setting_up_xr.html). If you have any issue you should check them.

## Prerequisites
- [Steam VR](https://store.steampowered.com/app/250820/SteamVR/)
- [Godot 4.2.1](https://godotengine.org/download/archive/4.2.1-stable/)
- [Android export configured](https://docs.godotengine.org/en/stable/tutorials/export/exporting_for_android.html)
- [Project settings -> XR -> Shaders: Enabled](https://docs.godotengine.org/en/stable/_images/xr_shaders.png)
- [Project settings -> XR -> OpenXR: Enabled](https://docs.godotengine.org/en/stable/_images/openxr_settings.png)

## For passthrough
- [Install build template](https://docs.godotengine.org/en/stable/_images/android_gradle_build.webp)
- [Install vendor plugin](https://github.com/GodotVR/godot_openxr_vendors/releases)
- [Android Export -> Enable Meta Plugin and OpenXR](https://docs.godotengine.org/en/stable/_images/android_meta_quest.webp)
- [Android Export -> Passthrough](https://docs.godotengine.org/en/stable/_images/xr_export_features.webp)
- With Quest connected, run [this option](https://docs.godotengine.org/en/stable/_images/android_one_click_deploy.webp)