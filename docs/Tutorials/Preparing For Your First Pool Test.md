# Before Heading Out

## Pressure Testing Your ROV

Conducting a pressure test is an excellent way to ensure your ROV is
watertight. When putting your ROV in water, there is a higher pressure
outside of the container than inside of it. You can simulate this with a
vacuum pump. By creating a vacuum inside of your container, you can
ensure that no air is leaking in similar to how water would if you were
to put it in the water.

Using a brake bleeder type of vacuum pump, squeeze the handle a lot of
times. You likely won't see any vacuum on the gauge until roughly 30
pumps. If there is a large leak you won't see any sort of vacuum at all.
For you ROV to be water ready, pump it up to around 8inHg and see if it
drops. If it drops to 0 quickly, your ROV is NOT ready to be put in the
water. Instead, go back and check all of your seals. If your gauge drops
slowly to around 3inHg and stops around there you are probably good to
submerge in shallow depths. If your gauge drops to around 6inHg and
stays there your ROV is fully ready.

## Testing Your Electronics For Shorts

Using a multimeter put it on the continuity mode. Touch the positive
side to the positive terminal of your electronics. Touch the negative
side to your negative terminal. If you have continuity DO NOT plug it
into your battery. There is a short circuit somewhere, and your ROV will
become damaged. If there is no continuity, your ROV is cleared of any
short circuits.

To make sure no short circuits happen later on, observe every joint.
Move the wires around a little. Is everything plugged in and secured
correctly? Could any wires come out and touch anything that they
shouldn't?

If everything looks good, your ROV should be good to plug in.

## Testing Your System

Preparing your system can require a few separate steps.

1.  Plug in your battery and then close off the waterproof cap

2.  Reinstall the plug into the vacuum port.

3.  Plug your ethernet cable into your topside computer.

4.  Open QGroundControl

Your system should take a few minutes to power on, but once powered on
you should see a camera feed, and it should say ready for flight. On
your initial time powering up, it is likely you will need to calibrate
your accelerometer and compass. To do this go to settings by clicking
the Q in the top left corner of the screen. Go through the calibration
steps by selecting calibration and then rotating your ROV to the
configurations shown.

## Checking Motor Directions

Once your sensors are calibrated, it is critical to verify that your
motors are spinning in the correct direction before entering the water.
If they are reversed, your ROV will drive backward or spin
uncontrollably. With the ROV still on the bench, arm the vehicle in
QGroundControl. Gently push the joystick forward. You should feel air
blowing out of the back of the ROV (the thrusters push air backward to
move the ROV forward). Next, push the joystick to the right. You should
feel air blowing to the left side. Finally, push the ascend (up) stick.
You should feel air blowing downward from the vertical thrusters. If any
motor is spinning the wrong way, go into the vehicle setup settings in
QGroundControl and reverse that specific motor.

# At The Pool

## Poolside Safety

Before you put the ROV in the water, take a moment to manage your
tether. Uncoil it fully to prevent tangles. Most importantly, secure the
topside end of the tether to something heavy or a fixed object like a
table leg. If the ROV pulls hard or gets caught on something, you do not
want it to pull your laptop into the pool.

## Emergency Procedures

Before you drive away, make sure you know exactly how to stop the ROV
instantly. If the ROV starts driving erratically, you need to \"Disarm\"
it immediately. Identify the \"Disarm\" switch on your controller or the
button in QGroundControl. Practice hitting this quickly. Disarming cuts
all power to the motors instantly, stopping the ROV and preventing
further damage. If the software crashes or the ROV is unresponsive, the
fail-safe method is to simply unplug the tether from the laptop, which
should trigger the ROV to stop automatically (if your failsafes are
configured correctly). If you see a leak, you need to be able to pull
your ROV to the surface immediately to mitigate any potential damages.

## Ballasting Your ROV

Although you did some calculations to provide the correct flotation it
is likely it's not completely perfect. Gently place the ROV in the water
without arming it. If it sinks immediately, you need to add buoyancy
foam or remove weight. If it floats very high with the frame out of the
water, you need to add ballast weights (like lead weights or large
washers) to the bottom of the frame. Ideally, you want the ROV to be
just slightly positive, meaning it floats with just the very top of the
enclosure breaking the surface. This ensures that if you lose power, the
ROV will slowly drift to the surface rather than sinking.

## The Dunk Test

This is the final and most important safety check. Lower the ROV into
the water until it is fully submerged, but do not release it yet. Hold
it there for about 30 to 60 seconds and watch closely. You are looking
for a steady stream of bubbles. You will likely see a few bubbles coming
from the frame or screw heads, which is just trapped air escaping.
However, if you see a continuous stream of bubbles coming from a cable
penetrator, the main tube, or an end cap, you have a leak. Pull the ROV
out of the water immediately, disconnect the battery, and dry it off.
After the 60 seconds, bring your ROV back up out of the water. Inspect
the bottom of the power bottle. If there is noticeable water in it,
there is a leak that needs to be addressed. If there is no water in the
power bottle, you are clear to continue with your test.

# Ending Your Test

## Retrieving Your ROV

When your test is complete, bring the ROV to the surface and immediately
\"Disarm\" it in QGroundControl. This prevents the motors from
accidentally spinning up while your hands are near them. When lifting
the ROV out of the pool, reach for the frame, not the tether. Pulling it
by the cable can damage the waterproof seal or the internal wiring.

## Fresh Water Rinse

Pool water contains chlorine, and open water contains salt; both will
corrode your aluminum frame, motor bearings, and electrical connectors
very quickly. Before you open anything, rinse the entire ROV thoroughly
with fresh, clean water. If possible, submerge the whole ROV in a tub of
fresh water. If a tub isn\'t available, use a hose to spray down every
nook and cranny, paying special attention to the thrusters. Sand and
salt can build up inside the motor bells, so giving them a good rinse
prevents them from seizing up later.

## Post Dive Inspection

Open your electronics tray. With the electronics tray removed, take a
flashlight and look inside the acrylic tube. You are looking for any
signs of water intrusion---droplets, fogging, or small puddles at the
bottom. Finally, loosen the vent plug. Temperature changes (going from a
cold pool to a hot car) can cause pressure to build up or drop inside
the sealed tube. Loosening the plug allows the pressure to equalize,
protecting your seals during transport.
