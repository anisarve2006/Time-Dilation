# Time Machine Simulation

Overview

This project is a Time Machine Simulation that visually demonstrates the concept of gravitational time dilation using General Relativity. The simulation models how time slows down near a massive object, such as a black hole or a neutron star, compared to an observer at a distance.

It features:

Real-time visualization using Matplotlib's 3D plotting.

Interactive controls to modify mass, radius, and number of points.

Time dilation calculation based on gravitational potential.

Live clocks displaying inside vs. outside time progression.

Features

Graphical User Interface (GUI) powered by PyQt5.

Real-time 3D visualization of a massive spherical object.

Configurable parameters via sliders:

Number of points representing mass

Mass per point

Radius of the gravitational object

Live Time Dilation:

Displays inside and outside time using digital clocks.

Uses Einstein’s relativity equations to simulate time slowing down.

Interactive zooming & resetting options.

Installation

Prerequisites

Ensure you have Python 3 installed and install the required dependencies using:

pip install numpy pyqt5 matplotlib

Running the Simulation

Run the following command:

python time_machine_simulation.py

How It Works

User Adjusts Parameters: Modify mass, radius, and point density using sliders.

Time Dilation Calculation:

Uses Einstein's equation:



More massive and compact objects cause stronger time dilation.

Visualization Updates:

Generates a Fibonacci sphere to represent a massive object.

Shows a safe radius where time is less affected.

Time Progression:

External time moves normally.

Inside time progresses slower due to gravitational effects.

Controls

Sliders: Adjust number of points, mass, and radius.

Zoom In/Out: Modify the visualization scale.

Reset Clocks: Restart the time progression.

Future Enhancements

Add realistic event horizon visualization.

Implement test particle motion.

Convert to a web-based version using Three.js.
