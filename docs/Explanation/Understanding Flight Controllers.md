## What is a Flight Controller?

A flight controller is a small computer board with built in and support
for external sensors responsible for real-time control of a vehicle's
movement. Some tasks it is responsible for are:

- Stabilization -- Using the internal IMU equipped in many flight
  controllers, it is able to keep an ROV properly moving on course.

- Executing Commands: The flight controller is in charge of receiving
  commands from the companion computer and then interpreting it into
  actual movements for the ROV.

- Sensor Integration -- Many ROVs use external sensors such as pressure
  sensors or sonar. The flight controller is in charge of interpreting
  the outputs of these sensors into something understandable for the
  companion computer to use.

- Low Level Control -- The flight controller directly talks to the ESCs
  for each motor. It contains the proper ports equipped to handle the
  PWM signals ESCs use.

## What is ArduSub and Why is it Important?

ArduSub is a powerful open-sourced firmware that is specifically
designed to be loaded onto a flight controller in use of ROVs and AUVs.
It's a subsection of the larger ArduPilot ecosystem which is meant to
control drones, planes, and rovers. ArduSub is especially useful for
ROVs because it is designed to handle the physics of underwater
movement. ArduSub also comes equipped with features offering prebuilt
compatibility with existing sensors such as

- Integration with MS5837 pressure sensor offering depth holding

- Integration with the onboard compass allowing it to lock onto a
  specific heading

- Multiple modes of flight designed for use in different tasks

## Why is the SpeedyBee F405 Wing a Good Choice?

The SpeedyBee F405 Wing is a cost effective flight controller with 12
different PWM outputs, and various sensors included by default. It has
the F405 processor which is known for its high computational power
allowing for the complex calculations needed for underwater physics
responses with sensor inputs. Finally, it is fully compatible with the
ArduSub firmware making it a great choice for a flight controller on an
ROV.
