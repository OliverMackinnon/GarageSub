## Center of Mass (CM) and Center of Buoyancy (CB)

The center of mass is the center of where the gravitational force acts
on your ROV. The center of buoyancy is the center of where the buoyant
force acts on your ROV. Your ROV will be most stable when CB is directly
in line above CM.

Resulting pitch of CB to the right of CM

CB to the right of CM causing CCW rotation

Ideal ROV -- CB above CM

Having a distance d between CM and CB will result in torque on your ROV
forcing it to pitch out of position. Having a higher force of CB and CM
makes an ROV increases its self-righting tendency. Increasing these
values leads to a higher inertia, making an ROV more difficult to move.

## Thruster Placement

The placement of your thrusters largely determines their effectiveness.
If your goal is to rotate your ROV as fast as possible, having your
thrusters further from the center will result in a higher torque causing
faster movement. Keep the following designs in mind.

![A blue and white drawing of a robot AI-generated content may be
incorrect.](./media/media/image4.png){width="2.5203543307086615in"
height="1.8785586176727909in"}![A green and black machine with four
wheels AI-generated content may be
incorrect.](./media/media/image5.png){width="3.1092366579177604in"
height="1.6382731846019247in"}

The following rules must be followed to ensure thrusters work properly:

1.  Horizontal thrusters must be placed in line horizontally with CM:
    Thrusters placed below or above will cause torque on the robot
    pitching it out of line.

![A blueprint of a machine AI-generated content may be
incorrect.](./media/media/image6.png){width="2.4406211723534557in"
height="1.4995734908136482in"}

2.  Vertical thruster(s) must be in line vertically with CM and CB: In
    the example ROV even though neither thruster is in the direct line
    with CM and CB, the resulting upwards force will not create any
    torque.

![A diagram of a machine AI-generated content may be
incorrect.](./media/media/image7.png){width="2.7780336832895887in"
height="1.6644455380577428in"}

3.  In order to rotate your robot, your motors must be a distance away
    from the vertical line with CM and CB. The further away this
    distance is, the more torque they will have on the body of the ROV.

![A drawing of a square object AI-generated content may be
incorrect.](./media/media/image8.png){width="2.4193897637795274in"
height="2.6116983814523183in"}

Maintaining Thruster Efficiency

A thruster's ability to move an ROV relies on its ability to accelerate
water smoothly. Any parts of the frame, tools, sensors, or components of
the ROV that get in the way will obstruct the inflow or outflow of the
water. This generates turbulence that disrupts the flow and reduces the
thruster's efficiency.

## Principles of Neutral Buoyancy

The term neutral buoyancy refers to the state an object in water is in
when its buoyant force is equal to the force exerted on it by gravity.
In general, the buoyant force of an object is equal to the mass of the
water displaced by the volume of the object. If the buoyant force is not
initially enough to counteract the gravitational force, a less dense
material such as pressure resistant foam could be added to increase the
volume while marginally increasing the weight. In general, a slightly
above neutral buoyant force should be used. If an ROV is carrying a
material back up to the surface, it helps to have extra help.
Alternatively, if an ROV experiences a failure while in flight, the
vehicle will return to the surface.

## Integrating Manipulators and Tools

A manipulator arm located on the front of an ROV will introduce
significant forces and torques on the vehicle. An arm on the front of
the ROV will cause significant torque when moving up. To counteract
this, vertical thrusters should be positions to create an opposing
torque. Placing thrusters further forwards if an arm on the front was
added will resist the pitching motion caused by the arm.

## Designing for Future Expansion

Over the course of an ROV's life, it will have many different components
added and removed. Because of this, it's important for a design to be
modular. Designing your frame, power systems, electronics systems, and
more to be modular will allow for the various updates that will
inevitably be needed without requiring a full redesign of the robot.
