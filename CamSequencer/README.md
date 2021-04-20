# CamSequencer

This TouchDesigner component can be used to save multiple camera settings (t[xyz], r[xyz], s[xyz], p[xyz]) and recall them.

## Usage

- Reference your camera in the **Camera** field
- Press **Initialize**. This will record the momentary camera settings as default 
- Change camera settings
- Pressing **Append** appends the current setting to the end of the list
- With **Select** you can recall the settings in order
- With **Bind** you can bind the snapshot parameters to the internal output of the module, or a Null CHOP referenced by **Nullref**
- You can unbind this with **Unbind**
- With **Insert** you insert at the slot which **Select** references. You can also **Remove** the **Select**ed snapshot.
- Pressing **Initialize** will clear the snapshots and save the current camera settings to slot 0
- TIP: If you move the camera in the OP viewer you need to hit **Bind** again afterwards!

## Improvement ideas

- Extend parameters?

# Support

Feel free to submit ideas, or let me know if I'm doing something someone else already perfected and is available :)
You can support my art/music: www.facebook.com/functionstore/ www.instagram.com/function.str/