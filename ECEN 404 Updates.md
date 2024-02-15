# ECEN 404-904
# Team 1: Radiation Resilient Logic Circuit Study based on Wide Bandgap Devices

This repository contains all the updates, reports, and presentations regarding the second semester of this capstone project.

# Weekly Updates
Week (1/16 - 1/19)

General:
- Worked on Status Update Presentation #1
- Contacted Sandia's sponsor to update them after break

Kaylee:
- Researched implementation for a RC snubber
- Working on adding the RC snubber to the schematic

Nia:
- Researched gate drivers/equivalent circuits to rectify level-shifting error
- Working on implementing possible circuit modifications

Nomar:
- Researched gate drivers to verify 5V from gate to source
- Looking into a source to ground 4:1 MUX design for better data stability

Week (1/22 - 1/26)

General:
- Presented Status Update Presentation #1
- Discussed circuit modifications with Sandia sponsor

Kaylee:
- Simulated a voltage spike in ltspice similar to the the voltage spike in the output of the ring oscillator
- implemented the RC snubber in ltspice to correct the voltage spike

Nia:
- Modified circuit in LTSpice and verified correct operation in simulations

Nomar:
- Began implementing


Week (1/29 - 2/2)

General:
- Testing gate driver, decoupling capacitor, and RC snubber circuits in LTSpice
- Troubleshoot PCBs to begin implementing circuit modifications

Kaylee:
- Implementing a RCD snubber instead of RC snubber because its more robust
- Working on finding exact values to use for the resistor and capacitor in the RC snubber

Nia:
- Modified existing PCB (opened and shorted traces) to new circuit design
- Tested modified circuit on bench
- Successful switching and latching of significant low (~100mV) and high (~1.6V) values

Nomar:
- Tested voltage divider gate driver in LTSpice, with minimal success
- Powered up PCB and troubleshot by measuring voltages at different locations
- TA advised looking into a decoupling capacitor to smoothen spikes in the output waveform

Week (2/5 - 2/9)

General:
- Presented Status Update Presentation #2
- Finished individual subsystem modifications
- Began/continued integrated system design
  
Kaylee:
- Modified Altium design for addition of RCD snubber
- Ordered new PCB for testing of RCD snubber
- Working on integrated LTspice design

Nia:
- Update individual subsystem LTSpice and Altium with new design
- Worked on integrated system LTSpice and verified correct total system function

Nomar:
- Implemented decoupling capacitor at the output of MUX in LTSpice
- Decoupling capacitor greatly improved voltage spikes in low value (see presentation #2)
- Tested decoupling capacitor using the PCB on test bench, with positive results
- Continue working on integrated LTSpice design

Week (2/12 - 2/16)

General:
- Worked on integrated LTspice design
- Verified functionality of integrated LTspice design

Kaylee:
- Worked on integrated system LTspice design
- Waiting for PCB to come in 

Nia:

Nomar:

Week (2/19 - 2/23)

General:

Kaylee:

Nia:

Nomar:

Week (2/26 - 3/1)

General:

Kaylee:

Nia:

Nomar:

Week (3/4 - 3/8)

General:

Kaylee:

Nia:

Nomar:

Week (3/11 - 3/15)

General:

Kaylee:

Nia:

Nomar:

Week (3/18 - 3/22)

General:

Kaylee:

Nia:

Nomar:

Week (3/25 - 3/29)

General:

Kaylee:

Nia:

Nomar:

Week (4/1 - 4/5)

General:

Kaylee:

Nia:

Nomar:

Week (4/8 - 4/12)

General:

Kaylee:

Nia:

Nomar:

Week (4/15 - 4/19)

General:

Kaylee:

Nia:

Nomar:

Week (4/22 - 4/26)

General:

Kaylee:

Nia:

Nomar:

Week (4/29 - 5/3)

General:

Kaylee:

Nia:

Nomar:
