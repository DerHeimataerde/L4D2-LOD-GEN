# Low Poly (L4D2-LOD-GEN)
Recursively decimate l4d2 models
(Can be reworked to use any source engine game, probably)

## Usage:

``lp.py '\path\to\models\directory\to\decimate' decimate-ratio-as-float '\path\to\studiomdl.exe\'``

- Decimation ratio MUST be from 0 to 1 as a float

- If studiomdl.exe path is omitted, defaults to standard C drive install dir

- Final compiled models are found in \left4dead2\models

## Uses:
Recursively decimate any .mdl models and associated files in a directory tree with configurable decimation ratio. Mainly used to create a low-poly overhaul of all game models, but also useful for created different lods for models.

## Credits:

https://github.com/Artfunkel/BlenderSourceTools

https://github.com/ZeqMacaw/Crowbar

https://github.com/UltraTechX/Crowbar-Command-Line

