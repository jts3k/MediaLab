# How to use the LED lighting system in the Media Lab like a champion

The LED lighting system is controlled by sending lists of color values to a DMX controller on a local area network.  This cab be done via ethernet (the Black ethernet cable labelled "LTG" will typically be connected to the Mac Pro desktop computer), or by joining the *MediaLabLighting* wireless network (the password is "the media lab").

Many different softwares can send the color values to the DMX controller.  We have provided a [handy Max patch](https://github.com/jts3k/MediaLab/blob/master/lighting/mlab-lights-color.maxpat) to get you started.  The patch makes use of the third-party [imp.artnet.controller](http://www.theimpersonalstereo.com/impdmx/) object, so make sure the object exists in your Max library.

If you need to power cycle the lighting system you can do so using the power strip attached the unistrut grid near the sound mixing console (you will need a step ladder to reach this.)
