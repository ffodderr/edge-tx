# EDGE-TX
Just stuff... might be useful

# Welcome to my little EDGE-TX repo
**Some stuff that I have had a play with making**<br>Currently, there is a Midland Helicopters theme, which only includes overrides for the splash screen, colour settings and a background. The rest of the theme will use the fallback theme.<br><br>
I have also added a ModelImg widget, which is useful for adding a relevant model image to the screen when using a single model memory for multiple helicopters.<br>It uses the Model Name from the flight controller to load the relevant model image that you are connected to. See usage details below.

** **NO warranties are expressed or implied** **

** USE AT YOUR OWN RISK **

### About
Just me having a play around, trying to add some stuff I want, that I haven't yet been able to find...

### Release notes
- 2025.07.03 - First release

### Requirements / dependencies
- RadioMaster Tx16s (large color screen)
- EdgeTx 2.10 or later
- RotorFlight 2 or later (Tested using a Nexus FBL)


### Midland Helicopters Theme

** This is a work in progress, and not much to it currently - feel free to use it if you want :-) **

**Install and activate the theme**

**Step 1.** Copy the THEMES folder to the root folder of your SD Card. This will create a new folder in the THEMES folder of your transmitter called Midland_Helicopters.

**Step 2.** Activate the theme

![image](https://github.com/ffodderr/edge-tx/blob/main/assets/1-activatetheme.jpg)

Now you should have a Midland Helicopters opening splash screen when you power on your TX16S transmitter, and a carbon look background for the screen. Colours have been themed into blues in general.


### Model Image Widget

** **First release - it seems to work as intended!** **

** Comments and suggestions for improvements are always welcome! **

**Install the widget**

Step 1. Copy the ModelImg folder to the WIDGETS folder of your SD Card.

**Using the widget**

**Step 1.** Locate a suitable spot on your screen layout to add the model image widget. Check screenshot for a suitable size and location option...

![image](https://github.com/ffodderr/edge-tx/blob/main/assets/1-setupscreenwidget.jpg)

**Step 2.** Press to "select Widget" from the widgets menu, and choose ModelImg from the list.

![image](https://github.com/ffodderr/edge-tx/blob/main/assets/2-selectmodelimgwidget.jpg)

**Step 3.** Close out of the screen editor, back to the home screen.

![image](https://github.com/ffodderr/edge-tx/blob/main/assets/3-widgetready.jpg)

When you are not connected to a model, it will not show a model image. Instead it will show some text telling you what image it was looking for to load onto the screen, including the path to that image. If the image doesn't exist (in the IMAGES folder) then no image will be displayed.

If you want to set a default image to appear when you are not connected to a model, create an image using the name displayed on the screen, and save it in the IMAGES folder. In the Step 3 screenshot above, you can see the missing image is called Rotorflight.png. If a Rotorflight.png image (192 x 114 pixel dimensions) existed in the IMAGES folder, that would be displayed here, when not connected to a model.


### I hope it is useful!
