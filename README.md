# HAGIWO Diode Distortion Eurorack Module
<img src="images/in_rack.jpg" width="25%" height="25%">
Through-hole 4HP  PCB version of the HAGIWO distortion eurorack module. 
### Current Status: Confirmed working, will update build guide and files later today.

## Hardware and PCB

<img src="images/front.jpg" width="15%" height="15%"> 
You can find the schematic and BOM in the root folder. 
For the PCBs, the module has one circuit PCB and one panel PCB. 
You can order them on any common PCB manufacturing service, I used JLCPCB. For the circuit PCB, standard settings should be fine.
For the panel, since it has copper exposed, make sure to choose a lead free surface finish (LeadFree HASL, ENIG) and/or spraypaint your panels so that you don't get lead on your hands.
<img src="images/pcbs.jpg" width="15%" height="15%">

Build is super straight forward, but the 250K Pots specified by HAGIWO can be hard to source. I just used 1M instead, which probably changes how gain and distortion 
behave, but it still works so you can try that instead if you have a hard time sourcing 250k.
<img src="images/side.jpg" width="15%" height="15%"> <img src="images/back.jpg" width="20%" height="20%">
