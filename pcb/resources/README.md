# KiCad Libraries
Symbols, footprints, and 3D models used for this project.


## Installation
1. Add path variable
    - Go to **Preferences -> Configure Paths...**
    - Add a path variable named `WAFFLE18` and define its path to this directory
    - **Do not use a different path variable name as the 3D models depend on it**
2. Add symbol library
    - Go to **Preferences -> Manage Symbol Libraries...**
    - Add `waffle18.kicad_sym` from `symbols`
3. Add footprint libraries
    - Go to **Preferences -> Manage Footprint Libraries...**
    - Add all `.pretty` directories from `footprints`

See [KiCad Reference Manual: Paths and libraries configuration](https://docs.kicad.org/10.0/en/kicad/kicad.html#path-variables) for more information.


## Sources
1N4148W (SOD-123)
- [KiCad Libraries](https://gitlab.com/kicad/libraries) - symbol, footprint, and 3D model

KS-2P02B01-01
- [marbastlib](https://github.com/ebastler/marbastlib) - symbol, footprint, and 3D model

MX Stabilizer
- [Keyswitch Kicad Library](https://github.com/kiswitch/kiswitch) - footprint and 3D model
- [marbastlib](https://github.com/ebastler/marbastlib) - symbol

MX Switch
- [Keyswitch Kicad Library](https://github.com/kiswitch/kiswitch) - 3D model

Seeed Studio XIAO RP2350
- [OPL_Kicad_Library](https://github.com/Seeed-Studio/OPL_Kicad_Library) - symbol and footprint
- [Printables](https://www.printables.com/@SeeedStudio) - 3D model