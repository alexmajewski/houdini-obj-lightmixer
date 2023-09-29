# Houdini /obj/ Context Light Mixer

Obj Light Mixer is a custom panel built to mimic the Solaris Light Mixer functionality and appearance (currently only the "Sliders" tab is reconstructed).

Only Redshift is supported.

![obj_lightmixer_example](https://github.com/alexmajewski/houdini-obj-lightmixer/assets/77795178/ee939e5b-b556-4c1f-bd1a-07e4d9232886)

# How to use

[![Obj Lightmixer v0.1.5](https://i.imgur.com/pIzrKwS.jpg)](https://www.youtube.com/watch?v=mIzkDsI2BHY)

Drag and drop Redshift lights from the network onto the Light Mixer panel to control them. If any buttons are disabled or missing, that means they aren't available for the chosen light type.

## Installation

#### Option 1: Install as package

1. Put the downloaded folder somewhere on your drive.
2. Copy the `packages/Obj_Lightmixer.json` file into your `/packages/` folder in your user preferences directory (usually `C:/Users/You/Documents/houdini19.5/`. Create it if it's missing).
3. Edit the copied `Obj_Lightmixer.json` and replace the path inside `"OBJ_LM":` to your downloaded folder's path, e.g. `"C:/houdini-obj-lightmixer-main/"`
4. Launch Houdini. If performed correctly, clicking the + button to add a New Pane will now feature an "Obj Context Light Mixer" option.

#### Option 2: Copy .pypanel file into the user preferences folder

1. Copy `python_panels/obj_lightmixer.pypanel`
2. Paste it into `/python_panels/` folder inside your user preferences directory (usually `C:/Users/You/Documents/houdini19.5/`)
3. Clicking the + button to add a New Pane will now feature an "Obj Context Light Mixer" option.
