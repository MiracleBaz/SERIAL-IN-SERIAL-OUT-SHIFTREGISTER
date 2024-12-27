# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

BASIC MOVEMENT TO SHIFT REGISTER

![ss1](https://github.com/user-attachments/assets/868677f2-7e76-4e66-bad6-88fef39737a1)


**Procedure**

/* write all the steps invloved */

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.


**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by:E Subash Miracle Raj RegisterNumber:24000572

*/

![ss2](https://github.com/user-attachments/assets/a8e20d53-a481-4660-8165-a795ac3febd8)

**RTL LOGIC FOR SISO Shift Register**

![ss3](https://github.com/user-attachments/assets/7ea5dc2f-ed4d-4497-8444-4769a185f4da)

**TIMING DIGRAMS FOR SISO Shift Register**

![ss4](https://github.com/user-attachments/assets/0f17379b-2d51-49f7-853a-402fee7130de)


**RESULTS**

Thus, the Serial-In Serial-Out (SISO) Shift Register is implemented using Verilog, and its functionality is validated with the truth table and timing diagrams.
