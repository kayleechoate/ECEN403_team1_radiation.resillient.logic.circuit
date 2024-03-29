# ECEN 403-904
# Team 1: Radiation Resilient Logic Circuit Study based on Wide Bandgap Devices

This repository contains all the updates, reports, and presentations regarding the first semester of this capstone project.

# Weekly Updates
Week (9/18-9/22): 
- Worked on Midterm Presentation
- Worked on Functional System Requirements
- Worked on Interface Control Document
- Worked on the Execution Plan
- Worked on the Validation Plan
- Met with Sandia Sponsor (9/22)

    Nomar:
    - Completed Execution Plan for Midterm Presentation
    - Researched 4:1 MUX validation tests for the Validation Plan
    - Began finalizing electrical and physical requirements of MUX for FSR
    
    Kaylee:
    - Worked on solution proposal, subsystem progress, and task partition slides for midterm presentation
    - Researched tests for validation plan for ring oscillator
    - Completed purpose and scope for FSR
    
    Nia:
    - Worked on problem statement, subsystem progress, and task partition slides for midterm presentation
    - Researched 1x4 SRAM Memory Cell Array validation tests
    - Noted interfacing ideas and constraints in ICD

Week (9/25-9/29):
- Presented Midterm Presentation (9/25)
- Worked on Functional System Requirements
- Worked on Interface Control Document
- Edited Validation and Execution Plan based on feedback from Midterm Presentation

    Nomar:
    - Completed the Thermal Interface, User Control Interface, and Communication Sections in the ICD
    - Outlined the functional, physical and electrical requirements of the 4:1 MUX in the FSR
    - Described the Support requirements in the FSR
 
    Kaylee: 
    - Completed Reference Documents, System Definition overview and ring oscillator paragraph, and Failure Propagation for FSR
    - Completed functional, electrical and physical requirements for the seven stage ring oscillator in FSR
    - Completed Primary Input Power, Signal Interfaces, and Dimension section in the ICD

    Nia:
    - Worked on Overview and Physical Characteristics in the ICD
    - Detailed the functional, physical and electrical requirements of the SRAM array in the FSR
    - Created first iteration of SRAM array layout

Week (10/2-10/6):
- Working on the finalization of circuit schematics
- Working on circuit simulations in LTSpice
- Researching converting PMOS to NMOS transistors

    Nomar:
    - LTSpice schematics and simulations
 
    Kaylee: 
    - LTSpice schematics and simulations

    Nia:
    - Researching additional circuitry for SRAM read/write
    - Working on LTSpice schematic and simulations for SRAM array using general MOSFETs

Week (10/9-10/13):
- Continuing LTSpice schematics and simulations
- Worked on Status Update Presentation
- Preliminary PCB layout design
- Attended Blitz to make progress on schematics, simulations, and layout design

    Nomar:
    - LTSpice schematics and simulations
 
    Kaylee: 
    - LTSpice schematics and simulations

    Nia:
    - Confirmed proper operation of each cell in general MOSFET SRAM array in simulations
    - Working on proper operation for full array row (switching 1 pair of write and write_ circuits among all 4 cells)
    - Started GaN version of SRAM array schematic

Week (10/16-10/20):
- Continuing LTSpice schematics and simulations
- Ordering parts for PCB (GaN FETs)
- PCB designing in Altium

    Nomar:
    - LTSpice schematics and simulations
    - PCB design
 
    Kaylee: 
    - LTSpice schematics and simulations
    - PCB design

    Nia:
    - Working on full array row simulations
    - Working on GaN single cell simulations

Week (10/23-10/27):
- Finalize PCB design
- Order PCB (deadline extended to 10/24)

    Nomar:
    - Finalized PCB Design
    - Ordered PCB on 10/24
 
    Kaylee: 
    - Finalized PCB Design
    - Ordered PCB on 10/24
 
    Nia:
    - Finalized PCB Design
    - Ordered PCB on 10/24

Week (10/30-11/03):
- Research on radiation testing
- Determined how to simulate effect of radiation during board testing (AC pulse, prolonged DC charge)
- Received PCBs
- Received parts from Digikey and picked up transistors from Sandia
- Began soldering

    Nomar:
    - Received PCB
    - Upon arrival and inspection, 4 out of the 6 transistors had their pads mirrored in Altium Designer to create a symmetrical 
      design which resulted in the physical transistor pads not aligning with the mirrored pads on the PCB
    - Began working on a new design that does not require the transistor pads to be mirrored, instead only rotated
    - Restarting PCB allowed for smarter and more calculated placement of components based on previous mistakes
    - Received parts
 
    Kaylee: 
    - Received PCB
    - Received parts

    Nia:
    - Received PCB
    - Received parts
    - Began soldering

Week (11/06-11/10):
- PCB Soldering
- PCB Reorder
  
    Nomar:
    - Created 2nd Revision of 4:1 MUX PCB with the resistors closer together and the transistor pads oriented correctly
    - Edited the resistor pad layout for easier and faster soldering, will look to implement into all 3 PCB designs in 404
    - Increased via size to allow for larger currents as well as added radiation injection test points
    - Reordered PCB from JLCPCB
    - Began practicing soldering with the small surface mount GaN transistors
 
    Kaylee: 
    - PCB Soldering

    Nia:
    - PCB Soldering

Week (11/13-11/17):
- PCB Soldering
- PCB Testing
- PCB Reorder

    Nomar:
    - 2nd Revision of PCB with corrected transistor orientation received
    - Soldered PCB with new transistor and resistor pad layouts
    - Shorted LEDs on PCB for user interface because there was too much voltage drop, will work to implement them in 404 design
    - Applied power to PCB and began performing preliminary tests to verify the soldering and circuit design
 
    Kaylee: 
    - PCB reorder (switch wired incorrectly)

    Nia:
    - Preliminary PCB testing: test operation of write circuits and 1 SRAM cell
    - TO DO: type up basic report of test results
    - TO DO: finish soldering other 3 cells if testing goes well

Week (11/20-11/28):
- PCB Soldering
- PCB Testing
- DEMO DAY 11/28

    Nomar:
    - Finished PCB Testing
    - Work on Final Report
 
    Kaylee: 
    - Finished PCB Testing
    - Work on Final Report

    Nia:
    - Finished PCB Testing
    - Work on Final Report
