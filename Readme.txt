==================================================
Quickapply
Version 1.0
Made by WRATH
==================================================

OVERVIEW
--------------------------------------------------
Quickapply is an Adobe After Effects utility script designed to speed up two repetitive tasks:

1. Applying animation presets (.ffx) to multiple layers quickly
2. Extracting text layers out of selected precomps while keeping their timing and position as close as possible to the original setup

This tool is built for motion designers and editors who work with text animation frequently and want a faster workflow inside After Effects.

==================================================
FEATURES
--------------------------------------------------
- Browse and load any .ffx animation preset
- Apply the preset to multiple selected layers at once
- Choose where the preset should be applied:
  - At each layer's In Point
  - At comp time 0
- Option to apply only to text layers
- UnPrecompose selected precomp layers
- Extract text layers from inside precomps back into the main composition
- Attempts to preserve:
  - Source Text
  - Timing
  - Visibility flags
  - Basic transform values
  - Layer order relative to the original precomp

==================================================
OPTION EXPLANATION
--------------------------------------------------

Apply at layer In Point
Applies the selected preset at the in-point of each selected layer.

Apply at comp time 0
Applies the selected preset at the start of the composition timeline.

Only apply to text layers
When enabled, the preset will only be applied to layers that are text layers.
Non-text layers in the selection will be skipped.

==================================================
IMPORTANT NOTES
--------------------------------------------------
- The UnPrecompose function is intended for text layers inside precomps
- The script attempts to preserve timing and transform values, but results may vary depending on:
  - complex parenting
  - collapsed transformations
  - expressions
  - 3D layers
  - cameras/lights
  - track mattes
  - effects and advanced animation setups
- It is recommended to save your project before heavy batch operations
- Always test on duplicate comps when working with complex production files

==================================================
KNOWN LIMITATIONS
--------------------------------------------------
- UnPrecompose currently focuses on text layers only
- Very complex nested animation setups may not translate perfectly
- Some transform relationships may require manual correction after extraction
- Preset behavior depends on how the .ffx file was originally built

==================================================
CHANGELOG
--------------------------------------------------
v1.0
- Initial release
- Added batch .ffx preset application
- Added timing mode options
- Added text-layer-only filter
- Added UnPrecompose function for text layers

==================================================
THANK YOU
--------------------------------------------------
Thank you for using Quickapply.

This tool was built to save time on repetitive animation tasks and improve text workflow inside After Effects.

Made by WRATH
==================================================