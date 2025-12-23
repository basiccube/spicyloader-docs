# Custom Afterimage Color Sets

Starting with the July 2nd (2025) build, custom afterimage color sets can now be added into the mod.  
These are loaded from the afterimages folder in Spicy Topping's AppData directory.
If the folder doesn't exist then just create it yourself.

You specify a set of light color values, then dark color values (there have to be the same amount of dark colors as there are light colors!), and then a name for the color set.
All colors have to be a hex color value.  
Example:
```json
{
	"light" : ["#202020", "#404040", "#808080"],
	"dark" : ["#101010", "#202020", "#404040"],
	"name" : "Example Color Set"
}
```