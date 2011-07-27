Dallas Temperature Sensor Arduino Library
=========================================

If you are using a Dallas one-wire temperature sensor then this repo contains the couple of libraries you will need to get up and running. I don't like having to go to different web sites to download libraries and then keep track of updates so I combined the ones I needed to work in a single repo for ease and I thought others might like it.

Contents
--------
* [Dallas Temperature Library 3.71 Beta](http://www.milesburton.com/?title=Dallas_Temperature_Control_Library)
* [OneWire 2.0](http://www.pjrc.com/teensy/td_libs_OneWire.html)

Installation
------------
The best way to install this is to link the directories from where you donwloaded them to your Arduino libraries folder. In that way, when you update the repo it will always be available within the Arduino environment without having to do anything else. To do this on Mac, open up a new Terminal window.

    cd ~/Documents/Arduino/libraries/
    ln -s /location-you-downloaded-repo/DallasTemperature .
    ln -s /location-you-downloaded-repo/OneWire .

Note that using a Macintosh alias (command-option drag) is not the same as using the `ln` command. The Mac alias isn't followed with the current Arduino (v22) app.

Alternatively you can just copy the `DallasTemperature` and `OneWire` folders into your Arduino library folder. On Macintosh this is typically the `~/Documents/Arduino/libraries/` folder.