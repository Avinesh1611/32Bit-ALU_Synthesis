# EXP 5: 32 Bit ALU-Synthesize the Gate Level Netlist and tabulate Area and Power reports.

## Aim:

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

![Screenshot (22)](https://github.com/user-attachments/assets/df25ee7c-ae17-412f-9198-f6c118823522)


#### Area report:
![Screenshot (25)](https://github.com/user-attachments/assets/92014451-35e1-4df5-af27-5c03b3f94ad9)


#### Power Report:

![Screenshot (26)](https://github.com/user-attachments/assets/484c8163-e79b-42c3-ace2-834485321de6)


#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
