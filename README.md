<!-- background: #fff4e3 -->
<!-- color: #2d2422 -->

# Mind Building Machine
Overview: Full life-cycle of Build, Configure, Calibrate and Operate an Ink Plotter to create PCBs.

## PCB
A Printed Circuit Board ([PCB](https://en.wikipedia.org/wiki/Printed_circuit_board)) mechanically supports and electrically connects electronic components or electrical components using conductive tracks, pads and other features etched from one or more sheet layers of copper laminated onto and/or between sheet layers of a non-conductive substrate. Components are generally soldered onto the PCB to both electrically connect and mechanically fasten them to it. 

Circuit board Prototypes can be created using breadboards or PCB Proto boards, but the PCB will be used to move the prototype version into a production component that can be used in creating electronic devices.

## PCB Plotter

The plotter is a computer printer for printing vector graphics. This is a DIY PCB Ink Plotter using Arduino and GRBL CNC.  Using a pen, we will plot a circuit board configuration onto the target media in a precise and controlled manner.  Using a tin plate as the target, we can deliver the designed board onto a physical media.  Later projects will use this output for etching and milling the board.

Plotter System components include:
* Electrical schematic
* Physical Structure
* Software
![alt text][plotter]

## A.) Fabrication, Construction, Assembly
You can watch the MBM YouTube channel for this projects play list.  It will include videos on Circuits, Motors, Servos and Construction materials.

## B.) Operation & Calibration
Using the software needed, we will program the Plotter to use GRBL files.  Additionally, we will walk through the design software and options available.  This will help you create your PCBs and go from Digital to Physical.  Calibration techniques are included to obtain the precisions needed for a successful 'print-job'.

## Cloud Integration
C. Connect to the Plotter, for remote access to the newly created plot and to access previous designs.  On-Click printing operationalizes the device for quick usage and design turn-around.  This enables future usage with our Augmented Reality dashboard projects.

[plotter]: https://github.com/btowner01/mbm-pcbplotter/blob/master/images/PCBcloudPlotter.png?raw=false "PCB plotter build v1"
[guide]: https://github.com/btowner01/mbm-pcbplotter/blob/master/docs/PCBguide.pdf?raw=false "PCB instructions"
