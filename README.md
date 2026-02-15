# quickdraw-terminal
Restore quake-style drop-down terminal hotkeys on GNOME Wayland. Hide/show any terminal app with a custom shortcut.

Many terminal emulators offer a “quake” or drop-down style feature that allows you to quickly show/hide the terminal with a global hotkey. However, under Wayland (the default session in modern GNOME), applications cannot globally listen for keyboard shortcuts due to security restrictions. This breaks the hotkey functionality of most drop-down terminals.

This GNOME Shell extension restores that functionality.
You can select any terminal application from a list of running or installed terminals, assign a custom keyboard shortcut, and then use that shortcut to instantly hide or unhide the terminal’s main window. The extension works seamlessly with Wayland and integrates with GNOME’s own keyboard shortcut settings.

Features:

* Select from detected terminal applications (Ptyxis, Ghostty, Tilix, Alacritty, etc.).
* Assign any custom hotkey via the GNOME Settings panel.
* Toggle visibility of the chosen terminal window with a single keystroke.

Why another drow-down terminal extension?

* Other extensions minimize or move the window between workspaces. 
* This one simply hides it (using the visibility property). 
* Instant show/hide, no animations, no delays. Just fast, clean drop-down behavior.

