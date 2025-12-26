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

**Procedure**
```
TYPE THE CODE IN THE QUARTUS SOFTWARE
COMPILE AND RUN THE CODE
GENERATE THE RTL VIEWER
CREATE NODES FOR INPUT AND OUTPUT NODES TO GENERATE TIMING DIAGRAM
FOR DIFFERENT COMBINATIONS OF INPUT GENERATE THE TIMING DIAGRAM
```

**PROGRAM**
<img width="265" height="239" alt="image" src="https://github.com/user-attachments/assets/f3ea921e-86a6-4ddf-add4-06bfa6835ae9" />

Developed by:
S.RITHIKA
RegisterNumber:25015482

**TRUTH TABLE**
| Clock Pulse | sin | q3 q2 q1 q0 | sout |
| ----------- | --- | ----------- | ---- |
| Reset       | X   | 0000        | 0    |
| 1           | 1   | 0001        | 0    |
| 2           | 0   | 0010        | 0    |
| 3           | 1   | 0101        | 0    |
| 4           | 1   | 1011        | 1    |
| 5           | 0   | 0110        | 0    |

**RTL LOGIC FOR SISO Shift Register**
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/859a4145-2123-4ee2-8d06-902c587ed344" />

**TIMING DIGRAMS FOR SISO Shift Register**
<img width="1409" height="790" alt="image" src="https://github.com/user-attachments/assets/4865b6b9-0e03-46e7-8ac5-cb86d7597799" />

**RESULTS**
Thus the verilog gate level code is to implement  SISO Shift Register using verilog and validating their functionality using their functional tables is done
