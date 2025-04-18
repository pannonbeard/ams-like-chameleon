# AMS-Like Chameleon
This was a fun little project to make my own standalone AMS-Like system that uses a 3dChameleon as the filament selector

## Things you'll need... 

## To print
- [3D Chameleon Parts](https://github.com/3DChameleon/3DChameleonMk4)
- [AMS-Like parts](https://github.com/pannonbeard/ams-like-chameleon/tree/main/ams-like-stls)
- [4x AMS-Like Spool Posts](https://github.com/pannonbeard/ams-like-chameleon/blob/main/ams-like-stls/AMS-like%20spool%20post.stl)
- [Spool holders by F1dude on Makerworld](https://makerworld.com/en/models/188682-spool-holder#profileId-208031)
- [A 4 way ptfe/filament combiner](https://www.printables.com/model/466735-4-to-1-bowdenptfe-tube-joinersplitter) of your choice
- Some sort of stand or mount that would work for the Bambu AMS Lite.

## Electronics and other bits
- [Arduino uno, cnc sheild and stepper drivers](https://www.amazon.com/DAOKI-Expansion-Arduino-Heatsink-Engraving/dp/B08KFYKKN4/ref=sr_1_5?crid=O6SY9OGG34GW&keywords=arduino+cnc&qid=1703170197&sprefix=arduino+c%2Caps%2C391&sr=8-5)
- up to 2x Nema 17 stepper motors
- USB cable
- 12-24v power supply
- Extra PTFE tubes and connectors

## Other bits
- A 2 to 4 color holder or stand
- 10x m3x12 flat top screws (For AMS-Like body)
- 4x m3x8 flat top screws (For AMS-Like body)
- Rubber bands for the Spool Holders by F1dude
- Screws and parts for the [3D Chameleon](https://github.com/3DChameleon/3DChameleonMk4)
  - 4x m3x40?? or m3x45 screws to replace the selector motor screws to account for the mount on top of the AMS-Like
  
# Build suggestions...
- Assemble the front and backs separate from each other first before putting the two halves together.
- While it is possible, it's a real pain in the butt to mount the arduino when this whole thing is together, you are best to mount it before putting on the front half of the AMS-Like

# Both Rpi pico and Arduino configs??
You'll notice that there are two configs in the configs folder. I've built by hand a rpi pico interface board to have it connect to the arduino cnc sheild. This was try and work with canbus and the AMS-Like.
It does work, but you need to have some kind of canbus tranceiver and 5v regulator/converter along with the pico and the cnc sheild.

You can however run the rpi pico over usb as well, you would just need to flash it correctly.

## But how do I flash the Arduino!? or the Pico!?
You can checkout my other repository, [klipper_multi_color](https://github.com/pannonbeard/klipper_multi_color), where I have a walk through and hopefully clear instructions on how to do just that.

#Want to contribute?!
Happy to have any help! I am not yet the best will all of the amazing things you can do with klipper, but any other ideas of things we can add or improve with this are greatly appriciated!

Open a issue or possibly a pull request and we can have some fun troubleshooting!
