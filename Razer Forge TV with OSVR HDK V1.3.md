#Connecting OSVR V1.3 Head Mounted Display to Razer Forge TV 

###First power up the OSVR HDK with USB connected to system running Ubuntu Studio 15.10 

### Next switch OSVR HDK to side by side mode using 
```
screen /dev/ttyACM0 115200

>#F1s

```

### Next plug Android ADB cable into Razer Forge TV

##NOTE: This will not power the Razer Forge TV unless USB is applied and later removed.

### Next Power up the Razer Forge TV and set up as ADB over USB

###Note: use <http://developer.razerzone.com/forge-tv/developer-setup/>

As a reminder 

# Enabling Developer Mode

Go to “Settings” from the home screen

Go to “About”

Click on the “Build” info until developer mode is unlocked

Go back to the home screen

Go to “Settings”

The “Preferences” row will now have a “Developers options”

Go to “Debugging”

Turn on “USB debugging”

# Switching the USB Port

The single USB port on the back of the Forge can be both a host and device USB port.

By default, the box boots as a host USB port and is not capable of being debugged through USB. 

The following steps will convert the USB port to device mode.

Go to “Settings” from the Forge Home screen

On the “Preferences” row (second row) select the “Developer options” icon (assuming you have done the “Enabling Developer Mode” steps)

Scroll to the bottom of the list and select “Razer Tools”

Select “Device mode”

Select “On”

