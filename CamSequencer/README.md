# CamSequencer

This TouchDesigner component can be used to save multiple camera settings (t[xyz], r[xyz], s[xyz], p[xyz]) and recall them.

## Usage

- Reference your camera in the **OBJ** field
- Press **Initialize**. This will record the momentary camera settings as default 
- Change camera settings
- Pressing **Add** appends the current setting. Add as many as you want! If you change your mind you can **Remove** the last setting. (***#TODO**: better management?*)
- You can recall settings via the **Select** field. The output CHOP will contain the settings, which then can be referenced as the camera settings 
- Pressing **Initialize** will recall the default record and clear all other entries

## Improvement ideas

- Better record management (remove currently selected instead of last entry?)
- Extend number of parameters (multiple choosable subsets?)
- Export/Import record sets
- One-click post-referencing
- UI?? Snapshots??

# Support

Feel free to submit ideas, or let me know if I'm doing something someone else already perfected and is available :)
You can support my art/music: www.facebook.com/functionstore/ www.instagram.com/function.str/
