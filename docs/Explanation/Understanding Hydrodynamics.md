# What is Hydrodynamics:

Hydrodynamics is "the branch of science concerned with forces acting on
or exerted by fluids (especially liquids)." This is basically how
liquids in motion interact with solid objects. With regards to an ROV,
hydrodynamics is what is behind how efficiently a vehicle moves, how
stable it is, and how much power it needs to operate. It is the
underwater equivalent to aerodynamics and follows much of the same
principles.

##  Key Forces Regarding Hydrodynamics

Drag -- This is the resistance that an ROV encounters as it moves. There
are many different types of drag, with the most significant being the
following:

- Form Drag -- How the shape of your vehicle affects its ability to flow
  through water.

- Skin Friction -- How the friction force of water flowing over an ROVs
  surface affects its flow. A smoother object will encounter less
  resistance than a rough object.

- Tether Drag -- How the data / power connection cord going to the
  surface affects your vehicle's maneuverability

- Interference Drag -- This is the forces that occur with regards to
  airflow around different components. For example, the turbulent water
  coming off a frame member can disrupt the inlet of a thruster. This
  could also be a component blocking the inlet or outlet of a thruster.

Drag follows the following equation:

$$D = \frac{1}{2}\rho v^{2}c_{d}A$$

Where:

- $D$ is the force of drag

- $\rho$ (rho) is the density of the liquid

- $v$ is the velocity of the vehicle

- $c_{d}$ is the drag coefficient (a number depending on the shape of
  the object)

- $A$ is the cross sectional area of the ROV facing the flow

# How to Optimize an ROV to Reduce Drag

There are a lot of ways to decrease the drag of an ROV but some general
strategies are apparent when looking at the drag equation.

1.  Streamlining the overall shape (lowering $c_{d}$):

- Streamlining the ROV: The best shape for an object is a teardrop form.
  This allows water to flow past with minimal disturbance. Making your
  front surfaces curved will allow water to flow around the body more
  easily.

<!-- -->

- Adding fairings or shrouds: In an ROV, an open structure creates a lot
  of turbulence. By implementing smooth panels around your vehicle, this
  guides water smoothly around the body of the ROV instead of letting it
  pass through the turbulent internal structure. Even two flat panels
  along the sides can make a large difference.

2.  Minimizing the cross sectional area (lowering $A$):

> The frontal area is the largest directly proportional to the drag on a
> vehicle. To minimize drag, one of the best ways to do this is to
> minimize the area. The best way to do this is to create a compact
> design where objects are positioned behind each other. For example, a
> tall wide ROV will have a lot more drag than a long thin one.

3.  Manage Wires (lowering $c_{d}$ and $A$):

> Routing all wires along the frame rather than letting them loosely
> hang around the components will allow the water to flow past them more
> efficiently. Loose wires create complex shapes causing turbulence.

4.  Optimize Thruster Placement (minimizing effects of $v^{2}$):

> The fastest place that water moves on your vehicle is where the
> thrusters are. Pushing water around at high speeds maximizes the
> effects of drag. Because of this for your ROV to move effectively, it
> is crucial that the flow of water around your thrusters is not
> blocked. Avoid placing the frame or other components in front of or
> behind thrusters.

5.  Tether Drag:

> Just like your vehicle, your tether also experiences drag. To minimize
> the effects, keep the following in mind:

- Using thinner wires: A thinner wire has less area, making it have
  significantly less drag.

- Decreasing the number of wires: Using fewer wires, or combining wires
  into one single wrap reduces the complexity of the flow around them
  reducing the drag

- Remove wire loops: Leaving loops in the wires in your tether can lead
  to increased drag. Ideally all of your wires will be tightly combined
  together

- Considering Buoyancy: Any force that a tether has acting on it will
  act on the ROV itself. If your tether is not neutrally buoyant, it
  will either push your ROV up or drag it down. Because of this it is
  important that your tether is neutrally buoyant.
