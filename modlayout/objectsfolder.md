# "objects" folder

**This only applies to mods with the default mod type.**

This folder is scanned by the mod loader where it will then detect sub-folders within it and add them as objects. The folder names is what it will use for the object names.

Each object sub-folder contains it's own set of GML files which are the object events. See the GameMaker manual for information on each object event listed here.  
The following events are supported:
* create.gml (Create)
* destroy.gml (Destroy)
* cleanup.gml (Cleanup)
* step.gml (Step)
* beginstep.gml (Begin Step)
* endstep.gml (End Step)
* draw.gml (Draw)
* drawbegin.gml (Draw Begin)
* drawend.gml (Draw End)
* drawgui.gml (Draw GUI)
* drawguibegin.gml (Draw GUI Begin)
* drawguiend.gml (Draw GUI End)
* predraw.gml (Pre-Draw)
* postdraw.gml (Post-Draw)
* roomstart.gml (Room Start)
* roomend.gml (Room End)
* outsideroom.gml (Outside Room)
* intersectboundary.gml (Intersect Boundary)
* animationend.gml (Animation End)
* alarm(0-11).gml (Alarms)
* userevent(0-15).gml (User Events)