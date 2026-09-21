# Changelog

All notable user-visible changes to Dark Mode for SketchUp should be documented here.

## 1.1.0

- Reinforced QToolTip styling in QSS to reduce white tooltips.
- Added lightweight theme reapplication every 2.5 seconds while dark mode is active.
- Reapplies styling to windows and toolbars created after startup, including some floating extension toolbars.
- Reapplies DWM dark title-bar handling to newly created native windows.
- Added an additional attempt to theme native Win32 `tooltips_class32` tooltips.
- Keeps compatibility with the previous extension ID/folder when updating from 1.0.
