# "sprites" folder

This folder is where the mod loader will search for character sprites.  
Sprites are meant to be named after the sprite variables (use modcharacter_dumpspritenames to figure out the names to use), only support PNG files and only work with sprite strips.

Each sprite can contain an INI file next to it for overriding certain aspects of the sprite, in this case the width, origin and speed (frames per game frame).

Example:
```ini
[Sprite]
Width=100
Speed=0.5
XOrigin=50
YOrigin=50
```