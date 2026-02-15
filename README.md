# quickdraw-terminal
Restore quake-style drop-down terminal hotkeys on GNOME Wayland. Hide/show any terminal app with a custom shortcut.

Many terminal emulators offer a “quake” or drop-down style feature that allows you to quickly show/hide the terminal with a global hotkey. However, under Wayland (the default session in modern GNOME), applications cannot globally listen for keyboard shortcuts due to security restrictions. This breaks the hotkey functionality of most drop-down terminals.

This GNOME Shell extension restores that functionality.
You can select any terminal application from a list of running or installed terminals, assign a custom keyboard shortcut, and then use that shortcut to instantly hide or unhide the terminal’s main window. The extension works seamlessly with Wayland and integrates with GNOME’s own keyboard shortcut settings.

Features:

    Select from detected terminal applications (GNOME Terminal, Konsole, Tilix, Alacritty, etc.).

    Assign any custom hotkey via the GNOME Settings panel.

    Toggle visibility of the chosen terminal window with a single keystroke.

    Lightweight and simple – no configuration files, no extra daemons.

Perfect for users who miss their drop-down terminal workflow on Wayland.
