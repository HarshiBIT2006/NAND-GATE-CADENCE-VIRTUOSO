# NAND-GATE-CADENCE-VIRTUOSO
This project presents the design, simulation, and verification of a 2-Input CMOS NAND Gate using Cadence Virtuoso. The gate is implemented at the transistor level using Complementary Metal-Oxide-Semiconductor (CMOS) technology. The objective is to design a functional NAND gate, verify its logical operation through transient simulations, and validate the layout using physical verification techniques.

Objective
Design a CMOS 2-input NAND gate.
Create the transistor-level schematic.
Generate the layout.
Perform transient simulation.
Verify the design using DRC and LVS.
Analyze the output waveform.

Theory- A NAND (NOT-AND) gate is a universal digital logic gate that performs the inverse of the AND operation. The output becomes LOW (logic 0) only when both inputs are HIGH. For all other input combinations, the output remains HIGH (logic 1).
Boolean Expression : Y = (A · B)'
truth table
+---------+---------+------------+
| Input A | Input B | Output (Y) |
+---------+---------+------------+
|    0    |    0    |     1      |
|    0    |    1    |     1      |
|    1    |    0    |     1      |
|    1    |    1    |     0      |
+---------+---------+------------+

In CMOS implementation, the Pull-Up Network (PUN) consists of two PMOS transistors connected in parallel, while the Pull-Down Network (PDN) consists of two NMOS transistors connected in series. This arrangement realizes the NAND logic function efficiently with low static power consumption.

Software Used
Cadence Virtuoso
Virtuoso Schematic Editor
Virtuoso Layout Editor
Spectre Simulator
Assura/Pegasus (for DRC and LVS)

Design Flow-
1. Create a new library.
2. Design the transistor-level NAND gate schematic.
3. Verify the schematic connectivity.
4. Create the testbench.
5. Apply input pulse signals.
6. Run transient simulation.
7. Observe the input and output waveforms.
8. Design the physical layout.
9. Perform Design Rule Check (DRC).
10. Perform Layout Versus Schematic (LVS).
11. Confirm successful verification.
12. Simulation

Design Flow-
1. Create a new library.
2. Design the transistor-level NAND gate schematic.
3. Verify the schematic connectivity.
4. Create the testbench.
5. Apply input pulse signals.
6. Run transient simulation.
7. Observe the input and output waveforms.
8. Design the physical layout.
9. Perform Design Rule Check (DRC).
10. Perform Layout Versus Schematic (LVS).
11. Confirm successful verification.

Simulation- Transient analysis is performed by applying all possible input combinations.
Expected Output:
1. Output is HIGH when either or both inputs are LOW.
2. Output is LOW only when both inputs are HIGH.

Layout Verification-
1. DRC (Design Rule Check)- ✔ No DRC Errors
2. LVS (Layout Versus Schematic)- ✔ LVS Matched

Results-
1. Successfully designed the CMOS NAND gate.
2. Correct logical operation verified through simulation.
3. Transient waveform generated successfully.
4. DRC passed without errors.
5. LVS matched successfully.

Applications-
1. Universal Logic Gate Design
2. Digital Logic Circuits
3. Arithmetic Logic Units (ALUs)
4. Flip-Flops and Latches
5. Multiplexers
6. Memory Circuits
7. Microprocessors
8. Embedded Systems

Conclusion- The CMOS 2-input NAND gate was successfully designed, simulated, and verified using Cadence Virtuoso. The simulation confirmed the correct NAND logic operation for all input combinations. Physical verification using DRC and LVS ensured that the layout conforms to fabrication rules and accurately matches the schematic. This project demonstrates the complete CMOS custom IC design process from schematic entry to layout verification.

Author- Aditi Bhatnagar
