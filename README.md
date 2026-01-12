# Blender Bridge
Open .FBX and .OBJ files in Blender from Unity, with instant exporting back to the original asset (using a Python script to replace normal saving)

## Features
* Two-click editing, you can double-click any .FBX or .OBJ file in Unity to instantly open it in Blender
* Pressing Ctrl+S OR using the entry in File/Export/ in Blender will save and automatically export the file back to Unity
* Formats are preserved
* Blender starts with your default startup scene
* Viewport zooms into your model on import, so even if your startup scene has you really zoomed out, you won't have to zoom back in :D
* Export settings are specifically for Unity, so there should be proper axis orientation (you can add/remove any export settings in `blenderbridge-injector`)
* Settings for close behavior, as well as setting your Blender path (by default configured to use the default Steam path)
* No splash screen
* Edit mode is in face selection by default

https://github.com/user-attachments/assets/c8879a20-0098-4138-a847-a047c0887f8a

