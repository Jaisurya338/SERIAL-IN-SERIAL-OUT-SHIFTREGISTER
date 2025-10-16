# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.
 ![WhatsApp Image 2025-10-16 at 16 01 32_93f9833d](https://github.com/user-attachments/assets/801bdbd7-7ff7-408e-8a03-133bd1dc8baf)


Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

/* write all the steps invloved */

**PROGRAM**
<img width="1907" height="900" alt="Screenshot 2025-10-16 173541" src="https://github.com/user-attachments/assets/25eda1b5-abab-4345-852a-f61a4da02014" />

/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by:Ramesh Jaisurya RegisterNumber:25005800
*/

**RTL LOGIC FOR SISO Shift Register**
![WhatsApp Image 2025-10-16 at 16 01 36_a6631a59](https://github.com/user-attachments/assets/8b8b3007-5fba-4ff9-aa8e-5d05af87b8d3)

**TIMING DIGRAMS FOR SISO Shift Register**

**RESULTS**
THUS,THE LOGIC IS STUDIED AND VERIFIED SUCCESSFULLY
