# How to use the LED lighting system in the Media Lab like a champion

The LED lighting system is controlled by sending lists of color values to a DMX controller on a local area network.  This can be done via ethernet (the Black ethernet cable labelled "LTG" will typically be connected to the Mac Pro desktop computer), or by joining the *MediaLabLighting* wireless network (the password is "the media lab").

Many different softwares can send the color values to the DMX controller.  We have provided [an app](https://drive.google.com/file/d/1nAiADJne7JqVaCNXszKJtNI7rsUBj-7c/view?usp=sharing) and some [handy Max patches](https://github.com/jts3k/MediaLab/tree/master/lighting) to get you started.  The patches makes use of the third-party [imp.artnet.controller](http://www.theimpersonalstereo.com/impdmx/) object, so make sure the object exists in your Max library.

If you need to power cycle the lighting system you can do so using the power strip attached the column by the sound mixing console.  Turning the power strip off then on again is a good brute-force method for turning all the lights off and resolving problems with controlling the lights.
