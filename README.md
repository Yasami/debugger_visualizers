# debugger_visualizers
Visual Studio C++ Debugger visualizer files for some libraries.

## How to install .natvis files

Copy a .natvis file into one of the locations below:
* %VSINSTALLDIR%\Common7\Packages\Debugger\Visualizers (requires admin access)
* %USERPROFILE%\My Documents\YOUR_VISUAL_STUDIO_VERSION\Visualizers\
  * YOUR_VISUAL_STUDIO_VERSION: Visual Studio 2012 or above.

## Supporting libraries

* picojson: https://github.com/kazuho/picojson
  * Which file should you use?
    * picojson_2012_2013_undefined_PICOJSON_USE_INT64.natvis : Visual Studio 2012/2013 and undefined PICOJSON_USE_INT64.
    * picojson.natvis : other case.
* ...
