# Island Bar for Omarchy

Floating pill-island status bar for [Omarchy](https://github.com/omarchy/omarchy) shell.

Replaces the default full-width status bar with elegant, floating pill-shaped capsules for workspaces, active media/lyrics, and system status widgets.

## Features

- **Pill Islands**: Grouped modules in individual rounded capsules with subtle accent borders.
- **Floating Gap**: Minimal 2px gap from the top of the screen and calibrated window spacing.
- **Smooth Animations**: Scale & fade transitions on song change / appearance and smooth width morphing.
- **Full Compatibility**: Retains 100% compatibility with Omarchy native widgets, tray, popups, and drag-and-drop customization.

## Installation

Clone this repository into your Omarchy plugins folder:

```bash
git clone https://github.com/ilyamaximusaws/omarchy-island-bar.git ~/.config/omarchy/plugins/custom.island-bar
```

Activate the bar:

```bash
omarchy bar use custom.island-bar
```

To revert back to the stock bar at any time:

```bash
omarchy bar reset
```

## License

GPL-3.0 (matches Omarchy shell license).
