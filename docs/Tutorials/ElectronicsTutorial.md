Wiring Your ROV
===============

For an ROV to work properly, the power must be properly distributed to each individual component.

High Power System (14.8V distribution from battery)
---------------------------------------------------

The battery will need to connect to each component in parallel. The easiest way to distribute this power is with terminal blocks. Here, you wire the positive output of the battery into one and then the negative into another. Each individual component is connected allowing to the positive and negative terminals for parallel power distribution. Be careful of polarity when wiring components to terminal blocks!

Low Power System (5V distribution)
----------------------------------

Run the output of the 5V converter into new terminal blocks. Currently, the only uses for the 5V supply are the flight controller, and the raspberry pi. Adding a manipulator, or other sensors may require a 5V supply so if you plan to do this using a larger terminal block could be useful.

Other Connections
-----------------

-       Each ESC has a 3 wire output into the motors. Wire each of these output from the ESC to the three wire cable. The 3 wire cable goes through the penetrator, and attaches to the motor on the other side.

-       ESCs also have a smaller white and black wire. This is the signal and ground wire to communicate with the flight controller.

-       The Raspberry Pi camera has a ribbon connector that gets pushed into the input for the camera ribbon connector on the Raspberry Pi. After pushing it in, push the surrounding plastic down to lock it in place.