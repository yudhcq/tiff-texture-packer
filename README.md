## tiff-texture-packer
Takes an OBJ file with TIF textures and merges them into a single texture file.

## 🚧 WIP

# How to use:
- `pip install -r requirements.txt`
- Create a folder and add your texture files and .mtl file in the same folder.
- `python objuvpacker.py [path to .obj file] -m [path to the .mtl file. Make sure the textures files are in the same folder as .mtl file] --no-crop -o [output folder name. This folder will contain the new material file, .obj file and combined texture .tif file. This folder will be created inside the folder that contains .mtl file]`

# Contribute:
- To report an issue, open an issue, provide the command that you used along with your dataset. This will help in debugging