# Case for OnePlus 6T (Openpilot)


### Fully Functional Progress

I've Decided to go with a 3-4 piece design simular to the [FREON-case](https://github.com/RetroPilot/FREON-case). Planning on using a [40mm Noctua Fan](https://www.amazon.com/Noctua-Cooling-Bearing-NF-A4X10-FLX-5V/dp/B00NEMGCIA) for the cooling on this unit. Havent deciding if i should use some heat sinks on the back of the phone to cool the SoC but soon enough i can test that once i get my car running OpenPilot. I was thinking of routing the USB C cable to the rear of the case using a USB C ribbon cable but i don't think im going to do that for this model. Main priority is getting OpenPilot running in my Kia Sedona 2004 that I'm RetroFitting.

Images from latest development v0.1.1:

<img src="https://github.com/Paperboypaddy/6TCase/blob/main/images/v0.1.1%20Front.jpg" width="600">
<img src="https://github.com/Paperboypaddy/6TCase/blob/main/images/v0.1.1_Rear.jpg" width="600">
<img src="https://github.com/Paperboypaddy/6TCase/blob/main/images/v0.1.1_Rear_side.jpg" width="600">

*Images may not be up to date*

<img src="https://github.com/Paperboypaddy/6TCase/blob/main/images/Test_fit_1.jpg" width="600">
<img src="https://github.com/Paperboypaddy/6TCase/blob/main/images/Test_fit_2.jpg" width="600">
<img src="https://github.com/Paperboypaddy/6TCase/blob/main/images/Test_fit_3.jpg" width="600">

### BatteryLess Mod

Testing voltage and resistant's from the battery. The marked pads are main voltage about 3.5v from my reading at the time. Battery is rated for 3.85v max 4.4v. 

<img src="https://github.com/Paperboypaddy/6TCase/blob/main/images/6T_Mainboard.jpg" width="300">

So i was doing some testing on using the battery board to see if that was an easier/safer way to go batteryless. And it seems like the battery board isnt for some reason liking that the battery voltage is going to 0v when its unplugged. It seems its fine once it gets plugged into USB power and starts its "charging". I think its still going to be best to use a Buck Converter and a super capacitor thats getting power off of the 5v from the USB C port to power the phone just like how the Comma 2/EON did it. 

### OLD INFORMATION:
~~DO NOT try to solder the battery connectors off. The heat transfers to the battery very fast and you can damage or even explode the battery from excessive heat. Just take a pair of small angle cutters and be careful not to short anything, just snip the two battery terminals. Once you've disconnected the battery from the bcm you can now solder wires to the buck converter. Document before hand the polarity of the battery leads so you solder correctly.~~

<img src="https://github.com/Paperboypaddy/6TCase/blob/main/images/6T_Battery.jpg" width="300">
<img src="https://github.com/Paperboypaddy/6TCase/blob/main/images/6T_BatteryLess_Mod.jpg" width="300">
<img src="https://github.com/Paperboypaddy/6TCase/blob/main/images/6T_BatteryLess_in_action.jpg" width="300">





### Case Printing

More stuff here:

More images ofc



