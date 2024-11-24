# Exp-5: 32Bit-ALU_Synthesis

## Aim :

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :

![Screenshot (163)](https://github.com/user-attachments/assets/72c5e803-7de6-4507-8b96-30c853b7ab60)



#### Area report:

![Screenshot (175)](https://github.com/user-attachments/assets/2fd05f3a-2d57-4f7b-9eb1-5f59e0bb8389)


#### Power Report:

![Screenshot (174)](https://github.com/user-attachments/assets/e01acf11-42d3-4913-b3b1-33a3aef842be)


#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
