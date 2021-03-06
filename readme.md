# Blender Custom User Preferences

This set of personalized preferences for Blender is ever evolving toward a more efficient and pleasing workflow.

Blender 2.79


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

Any options within `<!--` and `--!>` are under consideration but not currently employed. They are only visible while editing the Markdown source of the documentation.

## User Preferences

Access this menu via `File > User Preferences...` <kbd>Cmd ,</kbd>.


### Interface

![Interface Preferences](readme-assets/interface-prefs.png)

✓ Global Scene

✓ Auto Depth

✓ Zoom To Mouse Position

✓ Auto Perspective

Smooth View: 500

☐ Manipulator


### Input

Select With: Left

#### 3D View > 3D View (Global) > Set 3D Cursor
✓ Cmd


#### 3D View > 3D View (Global) > Context Toggle Values [Keyboard: Alt Z]
Value: TEXTURED
Value: MATERIAL

Change top value to `TEXTURED`, bottom value to `MATERIAL`. Toggle between texture and material shading modes with <kbd>Alt Z</kbd>.
![Context Toggle Values](readme-assets/input-context-toggle-values.png)

#### Mouse Zoom
☐ 3D View > 3D View (Global) > Rotate View [Mouse: Mouse/Trackpad Pan]

##### 3D View > 3D View (Global) > Zoom View [Mouse: Mouse/Trackpad Zoom]
Change to `Mouse: Mouse/Trackpad Pan`

<!-- #### 3D View > 3D View (Global) > Rotate View [Mouse: Mouse/Trackpad Pan]
☐ Rotate View [Mouse: Mouse/Trackpad Pan]
Disable mouse/trackpad pan from rotating view. -->

<!-- #### 3D View > 3D View (Global) > Zoom View [Mouse: Ctrl Mouse/Trackpad Pan]
☐ Ctrl
✓ Alt
Zoom with <kbd>Alt trackpad pan<kbd>. Same method as Adobe products.-->

#### 3D View > 3D View (Global) > Move View
Add new: view3d.move
Map Type: Mouse
Type of Event: Right, Click

### Add-ons

Enable these add-ons that come standard with Blender.

✓ Node Wrangler

✓ Import Images as Planes

✓ Bool Tool

✓ Layer Management


#### Install Add-ons

These add-ons must be downloaded and installed.

✓ [Blender Custom Tools](https://github.com/anthonyesau/blender-custom-tools)


#### Optional Add-ons

* 3D Print Toolbox

* [Animation Nodes](https://github.com/JacquesLucke/animation_nodes)

* [Sverchok](https://github.com/nortikin/sverchok)

### Themes

Go to the Node Editor theme area from the left menu bar.
Noodle curving: 1

### System

![System Preferences](readme-assets/system-prefs.png)

Cycles Compute Device: OpenCL

Images Draw Method [2D Texture]: GLSL

✓ Regional Overlap


## Settings within GUI

### Info Window

Render Engine [Blender Render]: Cycles Render


### Properties Window > Scene > Color Management

View: Filmic Log Encoding Base
Look: Base Contrast
