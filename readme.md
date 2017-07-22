# Blender Custom User Preferences

This set of personalized preferences for Blender is ever evolving toward a more efficient and pleasing workflow.


## Installation

To find out where Blender user preferences are stored on your machine run the following command in the Blender Python Console.

```
bpy.utils.user_resource('CONFIG')
```

The result should be something along these lines:
```
// On Mac
'/Users/username/Library/Application Support/Blender/2.78/config/'
```

To copy these custom preferences to your machine, replace the version number directory (`/Users/username/Library/Application Support/Blender/2.78`) with the corresponding directory contained in the top level of this repository.


# Documentation of Settings

To be concise, only changes to the default settings are documented.

## Key:

✓ = enable

☐ = disable 

## User Preferences

Access this menu via `File > User Preferences...` <kbd>CMD ,</kbd>.

### Interface

![Interface Preferences](readme-assets/interface-prefs.png)

✓ Global Scene

✓ Auto Depth

✓ Zoom To Mouse Position

✓ Auto Perspective

Smooth View: 500

☐ Manipulator
