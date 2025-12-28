PCB/README.md
# PCB Design – Class D Amplifier

This PCB is designed for a Class D Audio Amplifier using discrete components
such as NE555 timer and LM358 comparator.

## Software Used
- EasyEDA 

## PCB Specifications
- Board Size: ~42 mm × 28 mm
- Layers: 2-layer PCB
- Copper Thickness: 1 oz
- Minimum Track Width: 0.4 mm
- Ground Plane: Bottom layer
- Power Input: 12V DC

## Design Approach
- NE555 generates high-frequency triangular waveform
- LM358 is used as comparator for PWM generation
- IRLZ44N MOSFET used as power switching device
- LC filter used to recover audio from PWM
- Proper component placement done to reduce noise

## Notes
- This PCB is designed for learning and internship assignment purpose
- Not optimized for high power output

