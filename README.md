# Time Machine Simulation

## Overview

This project is a **Time Machine Simulation** that visually demonstrates **gravitational time dilation** using General Relativity. The simulation models how time slows down near a massive object, such as a **black hole** or **neutron star**, compared to an observer at a distance.

### Features

- **Real-time 3D Visualization** using Matplotlib.
- **Graphical User Interface (GUI)** powered by PyQt5.
- **Interactive Controls** to modify:
  - **Mass** per point
  - **Radius** of the gravitational object
  - **Number of points** representing mass
- **Live Time Dilation:**
  - Displays **inside vs. outside time** using digital clocks.
  - Uses **Einstein’s relativity equations** to simulate time slowing down.
- **User Controls:**
  - **Zooming & Resetting** options.

## Installation

### Prerequisites

Ensure you have **Python 3** installed and install the required dependencies using:

```bash
pip install numpy pyqt5 matplotlib
```

### Running the Simulation

Run the following command:

```bash
python time_machine_simulation.py
```

## How It Works

1. **User Adjusts Parameters**
   - Modify **mass**, **radius**, and **point density** using sliders.

2. **Time Dilation Calculation**
   - Uses **Einstein's equation**:
   - **More massive and compact objects → Stronger time dilation**

3. **Visualization Updates**
   - Generates a **Fibonacci sphere** to represent a massive object.
   - Shows a **safe radius** where time is less affected.

4. **Time Progression**
   - **External time** moves normally.
   - **Inside time** progresses **slower** due to gravitational effects.

## Controls

- **Sliders** → Adjust mass, radius, and number of points.
- **Zoom In/Out** → Modify visualization scale.
- **Reset Clocks** → Restart the time progression.

## Future Enhancements

- **Realistic Event Horizon Visualization**
- **Implement Test Particle Motion**
- **Convert to Web-Based Version using Three.js**
