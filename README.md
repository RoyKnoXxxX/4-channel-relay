## 4-Channel Isolated Relay Module with Arduino Uno

A complete, fully verified *4-Channel Relay Board* designed in KiCad. This project acts as an automated system shield that allows an Arduino Uno to safely switch four independent high-power high-voltage loads using low-voltage digital pins (D2-D5).

## Key Features

Full Optical Isolation: Uses *PC817 Optocouplers* to completely separate the sensitive Arduino logic circuit from the inductive relay coil kickbacks.

Intelligent Automation:Integrated an *Arduino Uno R3* footprint directly onto the board layout to act as the automated controller brain.

Rugged Outputs: Outfitted with 3-pin heavy-duty *Phoenix Screw Terminals* for secure high-current external appliance wiring.

Robust Power Traces:Hand-routed bold *1.5 mm thick copper traces* on the high-power relay outputs to manage large electrical currents safely without overheating.

Dual Ground Planes: Utilizes complete Front (F.Cu) and Back (B.Cu) *GND Copper Filled Zones* for noise reduction.

## Component Specifications (Through-Hole Layout)
Relays: Standard 5V/12V Sanyou SRD Series (Form C / SPDT)
Optocouplers: PC817 (DIP-4)
Switching Transistors:BC547 / 2N3904 (TO-92)
Flyback Protection Diodes: 1N4007 (DO-41)
Indicators:3mm/5mm Signal LEDs

##  Project Structure
* /PCB-mesl.kicad_sch: Complete verified schematic diagram (Passes ERC with 0 errors).
* /PCB-mesl.kicad_pcb: Board layout footprint placements and copper trace routing paths.
* /gerber/: Pre-generated industrial production files ready to be sent to manufacturing plants (JLCPCB, PCBWay, etc.).

