# RobotSimulation

This is a collection of files in which I'm working through the process of creating a simple simulator
for FIRST-style robots for Team 4061 - Palouse SciBorgs.

RobotPhysics is, so far, just about exploring ways to represent a robot's acceleration profile.

RobotSimulationBits has my first go at a full simulator (minus physics); it includes visualization using vpython. It has a design
for autonomous that represents auto programs as function closures. While this is clever, it is sufficiently hard to keep straight in one's head without
strong typing that I think I will ultimately prefer the approach used in Tutorial Simulator that represents programs as objects.

Tutorial Simulator is what I've been working on in discussion with the software team. It has a different design
for autonomous using obects to represent programs instead of function closures.
