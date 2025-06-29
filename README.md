# SRAM-PROJECT
This repository contains design and verification of a low-power high-speed CMOS SRAM cell. The project showcases the full VLSI flow including schematic entry, layout generation, simulation analysis, and timing validation. Designed using 0.25μm CMOS technology in Microwind and DSCH tools, the project verifies function,optimized switching and memory.
# Low Power High Speed CMOS SRAM Design

## Project Overview

This project focuses on the design and simulation of a low power high speed CMOS SRAM Static Random Access Memory cell. It uses CMOS technology to achieve a balance between speed power consumption and area. The design includes both schematic simulation and layout verification using standard VLSI tools.

## Tools Used

- Microwind DSCH and Layout Editor
- SPICE or Analog Simulation
- Technology 0.25 micrometer CMOS

## Design Details

### Features

- Low power dissipation during read and write operations
- High speed switching response
- Verified using analog simulation waveform outputs
- Layout verified with stick diagram and DRC checks

### Simulation Results

- Write Operation  
  Data equals 1, DataBar equals 0  
  When Wordline is high, the data is latched in the cell

- Read Operation  
  After writing, during wordline activation, out1 and out2 reflect stored values

- Waveforms confirm correct SRAM behavior and fast transition at output nodes

### Screenshots

- Waveform Output  
  Shows successful data storage and retrieval operations with proper voltage levels at out1 and out2

- Layout Design  
  Clearly marked VDD, VSS, and connections  
  PMOS and NMOS transistors properly placed  
  Data, DataBar, Wordline, Out1, and Out2 clearly routed

## Project Files

- Schematic Design
- Layout Design
- Simulation Waveforms
- Technology File
- DRC Clean Layout

## How to Run

1. Open the layout and schematic in Microwind or DSCH
2. Apply input vectors Data, DataBar, and Wordline as shown in waveform
3. Run the analog simulation
4. Observe outputs at out1 and out2 to verify SRAM functionality

## Conclusion

This project successfully demonstrates a low power high speed SRAM cell using CMOS technology. It includes full design flow from schematic to simulation to layout making it suitable for VLSI mini project or academic submission.

## Author

- Name Sai Ganesh Deepak
- Branch ECE
- Toolchain Microwind and DSCH
- 
