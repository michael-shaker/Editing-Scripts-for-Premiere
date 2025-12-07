# Editing-Scripts-for-Premiere

**Overview**
- **Type**: AutoHotkey script that enhances Adobe Premiere Pro for power users — adds workflow shortcuts and UI-behavior fixes.

**Features**
- **Right-click timeline scrub**: Hold the right mouse button on the timeline to continuously move the playhead to the cursor (requires mapping `\` to Premiere's "Move playhead to cursor"); sends `Esc` to deselect clips when clicking selected areas.
- **Alternative scrub options (commented)**: Optional commented code for using other mouse buttons (e.g., `XButton2` or middle mouse) to achieve similar smooth scrubbing.
- **Ripple delete shortcut**: `Alt+Shift+E` (`!+e`) sends `v+f` to ripple-delete the clip or blank at the playhead.
- **Auto-dismiss warnings**: Automatically presses Enter on Premiere warning dialogs (for example, the "delete existing keyframes" confirmation dialog).
- **Alt menu-mask & toggles**: Remaps Alt behavior (scan-code workaround) to avoid menu cross-talk and provides a `LAlt+RAlt` suspend/resume toggle for the script.
- **Custom Shift+X mapping**: `Shift+X` is mapped to send a custom shortcut sequence (sends `Ctrl+Shift+Alt+X` then `Ctrl+\`).
- **Tray icon & autostart notes**: Adds tray-icon indicators and contains comments on creating a shortcut for Windows Startup to auto-run the script.

**Notes**
Comment out or in whatever features / code you need based on your individual use cases! Also, if you like having your Premiere Pro colors different than the darkest default (kinda odd, but you do you) then you can change the timeline color values by checking your Windows Spy, which should give you the correct colors necessary. Might be a bit tedious, but that's what you get for being different. JK haha! (Incredibly funny, I know)