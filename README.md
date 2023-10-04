[![Current Release](https://img.shields.io/github/v/release/sneakyevil/SD-MapEditorFree?label=Current%20Release&color=red&0)](https://github.com/sneakyevil/SD-MapEditorFree/releases/latest/download/MapEditor.zip)
![Downloads](https://img.shields.io/github/downloads/sneakyevil/SD-MapEditorFree/total?label=Total%20Downloads&color=red&0)
![Latest Downloads](https://img.shields.io/github/downloads/sneakyevil/SD-MapEditorFree/latest/total?color=red&label=Latest%20Downloads&0)

# Installation
1. First check readme from SDmodding org: [Here](https://github.com/SDmodding/.github/blob/main/profile/README.md)
2. Download latest [MapEditor.zip](https://github.com/sneakyevil/SD-MapEditorFree/releases/latest) file from Release or by [Clicking here](https://github.com/sneakyevil/SD-MapEditorFree/releases/latest/download/MapEditor.zip).
2. Extract all files inside game folder

# Models Installation
- This is essential and needed!
- The Map Editor is meant to be used only for custom models, there isn't anyway to load individual models from the game because they're "baked" to the map cells.
1. Inside game folder and under folder `data` you create `MapEditor` folder.
2. Inside that folder you create another folder that you name whatever you want, it's model category.
3. Now you need to use [Model Scriber](https://github.com/SDmodding/ModelScriber) and use the script something like this:
   - `Scribe Model Model_T MapEditor\YourCustomCategory`
   - The `YourCustomCategory` is the folder you created inside `MapEditor`, it doesn't matter how you name it just make sure it's scribed and moved to the same folder!
5. After you scribe your model, you just simply copy it to that folder and then load game and it should show inside model list.
6. You can put how many models you want inside the category.

# Why not full version?
- It takes time to do develop stuff like this and when you're sponsoring me, it motivates me to still work on those projects related to Sleeping Dogs even more.
- You can find the sponsor tier on my github that gives you access to the Pro Version.
  - You don't need to pay monthly, just paying once to get Pro Version for that one month gives you option to keep it forever. (But you will miss out updates)  
- Current Free Version limitation:
  - Unable to save project. `(You can still load projects from people that have Pro Version)`

# Controls
| Type | Key | Description |
| ------------- | ------------- | ------------- |
| Open/Close | Left ALT + Home | Open/Close the editor |
| Moving Object | Arrow Keys / Page Up / Page Down | - |
| Rotate Object | CTRL + (Arrow Keys / Page Up / Page Down) | - |
| Snap Rotate Object | CTRL + Mouse Wheel | - |
| Camera | Right Mouse Button | Unlocks movement while holding key |
| Camera Movement Speed | Right Mouse Button + Mouse Wheel | - |
