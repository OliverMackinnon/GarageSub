# Materials

## Why use aluminum extrusions?

Aluminum extrusions are a great choice for an ROV because of how easily
configurable they are. The slots in combination with the sliding
hardware allow for easy repositioning of components throughout the ROV.
The 20x20mm size is easy to work with allowing people to cut it to
whatever size is needed. Furthermore, aluminum is a strong material
capable of withstanding various shocks.

## Purpose of polyurethane foam

The buoyancy for an ROV can be made with expanding polyurethane foam.
This is a great material for this because of its strength, easy molding
capabilities, and its ability to withstand pressure.

# Design Principles

## Stability in your design

The most critical goal of frame design is to allow your ROV to stable in
the water. The stability of an underwater vehicle is largely determined
by its relationship between its center of mass, and center of buoyancy.
The center of mass (CM) is the point where the ROVs totally weight is
concentrated. The center of buoyancy (CB) is the center of the volume of
water the ROV displaces. For general stability, the point CM bust be
below the point CB with these points lining up with the vertical axis of
your ROV. A practical example of this would be:

- Batteries, electronics, ballast weights, and other heavy components as
  low on the ROV as possible

- All buoyancy materials should be as high on the frame as possible
  located above the heavy components

## Choosing the thruster configuration for your ROV

The layout of your frame and your thruster layout go hand in hand. In
the case you are using Ardusub, the following thruster configurations
are provided. An ROV is not limited to these configurations, although
these have been tested and work well.

![Frame Configuration Advantages / Disadvantages - Build - Blue Robotics
Community Forums](./media/media/image1.png){width="5.308003062117235in"
height="5.329166666666667in"}

A common choice for ROVs is the vectored configuration. This offers 4
degrees of freedom (DOF) allowing for easy movement when in use. An
alternative is the vectored configuration with four vertical thrusters.
This offers 6 degrees of freedom allowing for the ROV to tilt forwards
or backwards. Another common option is the use of two thrusters pointing
forwards, with one or two pointing upwards. This is useful for ROVs with
budget or power constraints.

Ultimately, the choice of thruster configuration will decide where the
supporting pillars on your frame have to be located, as it is important
that the thrusters are connected to something structurally sound where
their flow is not blocked.

# Buoyancy Calculations and Implementation

## How buoyancy works

In order for an ROV to be neutrally buoyant, the weight of the ROV must
equal the weight of the displaced water. Because saltwater is more dense
than water, this means that your ROV will never be neutrally buoyant in
freshwater and saltwater so you must plan for only one.

## How to calculate for neutral buoyancy

There are two methods for making your ROV neutrally buoyant. You can do
it by taking the dry weight and then measuring the volume of your ROV,
or you can do it by finding the submerged weight and then adding
buoyancy on after. The wet weight method is easier but will require
submerging a scale underwater.

## Dry Weight Method:

1.  Measure the weight of your robot on land

2.  Find the volume of your robot based on either accurate CAD models,
    or tested data

    a.  Volume of your robot can be measured by placing robot in a
        container of water filled up completely. The volume will can be
        found my measuring the amount of water that has overflowed from
        the container.

3.  Do calculations to find either excess weight or buoyancy of ROV and
    find what is required to counteract that

4.  Add necessary foam or weight to ROV for neutral buoyancy

## Wet Weight Method:

1.  Submerge your robot in water and measure the weight in water

2.  Based on excess weight, do calculations to find what necessary
    materials need to be added to counteract force

3.  Add necessary foam or weight to ROV for neutral buoyancy

## Creating buoyancy with expanding polyurethane foam

1.  Find your necessary volume of foam.

2.  Create a mold that will be filled with foam

3.  Mix the foam -- fill a container with two part foam and mix
    thoroughly

4.  Pour mixed foam into molds -- The foam will expand around 30 times
    of its liquid volume

5.  Allow foam to fully cure

6.  Remove foam blocks from molds (or keep them within molds if you will
    attach your molds to your ROV if so remove excess foam from molds)

7.  Attach foam to frame
