# Full-Wave-Rectifier
Project Overview

This project is a Full Wave Rectifier designed using KiCad. A full wave rectifier converts an AC (Alternating Current) input into a pulsating DC (Direct Current) output by using both the positive and negative half cycles of the AC waveform.

Unlike a half-wave rectifier, which uses only one half cycle of the AC signal, a full wave rectifier provides a more efficient conversion because both halves of the AC waveform are utilized.

This project can be used as a basic electronics learning project to understand AC-to-DC conversion, diode rectification, filtering, and PCB design.

🎯 Objectives
Convert AC voltage into DC voltage.
Understand the working of a full wave rectifier.
Learn how diodes are used for rectification.
Reduce output voltage ripple using a capacitor.
Design the complete circuit using KiCad.
Create the schematic and PCB layout.
Practice footprint assignment, PCB routing, ERC, and DRC.
⚙️ Working Principle

The circuit uses four diodes connected in a bridge configuration, commonly called a Full Wave Bridge Rectifier.

During the positive half cycle of the AC input, two diodes conduct and allow current to flow through the load in one direction.

During the negative half cycle, the other two diodes conduct. Although the AC input polarity has reversed, the current through the load still flows in the same direction.

Therefore, both half cycles are converted into pulsating DC.

A capacitor can be connected across the output to smooth the pulsating DC and obtain a more stable DC voltage.


✅ Advantages
Uses both halves of the AC waveform.
Higher efficiency than a half-wave rectifier.
Produces lower ripple compared with a half-wave rectifier.
Does not require a center-tapped transformer.
Simple and widely used circuit.
Suitable for basic AC-to-DC power supplies.
⚠️ Limitations
Four diodes are required.
Current passes through two diodes during each half cycle.
Therefore, there is a forward voltage drop across two diodes.
Output still contains ripple without a filter capacitor.
The diode ratings must be selected according to the input voltage and load current.
🔍 Testing

After completing the PCB design:

Check the schematic connections.
Verify diode orientation.
Check capacitor polarity.
Assign the correct footprints.
Run ERC.
Correct any ERC errors.
Update the PCB.
Place the components.
Route the tracks.
Run DRC.
Inspect the PCB using the 3D Viewer.

For practical testing, use a safe low-voltage AC source appropriate for the component ratings.

🛡️ Safety

⚠️ Do not connect the circuit directly to 230 V AC mains unless the entire design is specifically rated and designed for mains voltage.

For a beginner project, use a low-voltage isolated AC source or transformer secondary.

Important considerations include:

Correct diode voltage and current ratings.
Correct capacitor voltage rating.
Proper PCB clearance and creepage.
Correct polarity of electrolytic capacitors.
Proper fuse and protection where required.
Never touch exposed mains-voltage circuitry while powered.
🚀 Future Improvements

The project can be improved by adding:

Voltage regulator such as 7805.
Larger filter capacitor for lower ripple.
LED power indicator.
Fuse and protection circuit.
Screw-terminal connectors.
Adjustable voltage regulator.
PCB test points.
Reverse-polarity protection.
Complete regulated DC power supply.
📚 Learning Outcomes

By completing this project, you can learn:

AC-to-DC conversion.
Full-wave bridge rectification.
Diode operation.
Capacitor filtering.
Ripple voltage.
Schematic design in KiCad.
Footprint assignment.
PCB layout and routing.
ERC and DRC.
PCB 3D visualization.
👨‍💻 Software

KiCad 9.0
