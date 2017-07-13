![](https://cloud.githubusercontent.com/assets/549567/17456391/c1ea2736-5bf3-11e6-83c5-cbfb60a02cc9.png)

# RandomColors
Sketch App Plugin For Applying Random Colors To A Selection Of Objects.


[](https://cdn-images-1.medium.com/max/1600/1*snjYmA8TIYxC1KHFSQZUfQ.gif)


---
## Installation
Install with [Sketch-Toolbox](sketchtoolbox.com) or copy and paste RandomColors.sketchplugin file to your sketch app’s plugin folder.

## Basic Usage

**1. Define Colors**
Skip this step if you want to use default colors to be used.

		
		// Default colors
		
		var color1 =  "#FC583B"
    var color2 =  "#FFD100"
    var color3 =  "#3ADCBE"
    var color4 =  "#5071FF"
    var color5 =  "#014EEF"
    var color6 =  "#FFF200"
    var color7 =  "#78379D"
    var color8 =  "#FE4F20"
    var color9 =  "#40BE65"
    var color10 = "#EDC054"
    var color11 = "#EDC054"
    
    // Change the hex code to your desired colors. You can also change the number of color by adding or removing *color* variables.
    


**2. Select Shape Objects**

Select all objects you want to have random colors.


**3. Apply Random Colors**
Run the RandomColors plugin from plugins menu.

---
**Note:** The plugin only works with *Shape Layers*, support for *Text* and *Path Layers* and objects inside a *Group* will be added next. In case you would like to contribute, please implement any of these features, and raise a pull request.
