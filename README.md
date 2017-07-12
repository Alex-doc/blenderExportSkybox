
### Description ###

Quick and dirty addon that exports Scene render to Urho3D-friendly Skybox images.
based on Blender's operator_file_export.py example.

I was unable to export a cube environment map which included the DOF,
so I made this script which creates 6 cameras with FOV of 90°,
then it renders them one by one and saves the output to separate image files on disk.

This script is meant to be used with Urho3D but could potentially be used for any
Skybox-related need.

### Features ###

- Supports basic scene compositing
- Supports Blender's DOF

### Instructions ###

- Enable the add-on
- Make your scene
- File -> Export Skybox
- select a base file name/path ( _front, _back and so on will be appended to it)
- Click the export button and wait.