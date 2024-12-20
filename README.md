# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

/* 1.Type the program in Quartus software.
2.Compile and run the program.
3.Generate the RTL schematic and save the logic diagram.
4.Create nodes for inputs and outputs to generate the timing diagram.
5.For different input combinations generate the timing diagram. */

**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by:Nara Guna Susmitha RegisterNumber:24010204
 
![Screenshot 2024-12-20 051357](https://github.com/user-attachments/assets/b219e647-c9a9-47f8-8ef7-1d4ef50295ac)

 
*/

**RTL LOGIC FOR 4 Bit Ripple Counter**

![Screenshot 2024-12-20 051417](https://github.com/user-attachments/assets/e7453960-1c04-434b-9ba3-eb0eca98e950)


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![Screenshot 2024-12-20 051647](https://github.com/user-attachments/assets/13be85a0-dd67-44b8-a0ef-b296418aa478)


**RESULTS**

Thus implement 4 Bit Ripple Counter using verilog and validating their functionality using their functional tables is done successfully.
