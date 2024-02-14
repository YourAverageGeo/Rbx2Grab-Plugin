# Rbx2Grab-Plugin
A plugin branching off from .Index's roblox script, Instructions are similar.

### Setup Plugin

- Install [Rbx2Grab](https://create.roblox.com/store/asset/16359944935/Rbx2Grab%3Fkeyword=&pageNumber=&pagePosition=)

### Setup Server

- Run `pip install flask` to install flask
- Run `python server.py` to start the server on `https://127.0.0.1:5000`

### Usage (Roblox Studio)

- Click on `Rbx2Grab` located in `Plugins`
- Select desired model / folder
- Press `OK`
- When finished a .json file will be created in the folder with `server.py`
- To convert it to a .level file see [Slin/GRAB-Level-Format](https://github.com/Slin/GRAB-Level-Format) (`tools/ConvertToLevel.py`) or [grab-tools.live](https://grab-tools.live/editor).

Try out this free model `NodeTesting.rbxm` to give an understanding on how this plugin works

## Credits
- [@.index](https://github.com/twhlynch) Duh
- @person615 (Discord) Created the first version / proof of concept.
- [@Slin](https://github.com/Slin) Created Grab and the level format.
