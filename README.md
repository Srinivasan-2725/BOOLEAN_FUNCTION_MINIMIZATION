# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)| (~a&b&d)| (a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule 

Developed by: Srinivasan P RegisterNumber:25017988


**RTL realization**
<img width="976" height="703" alt="image" src="https://github.com/user-attachments/assets/75547ff3-50b7-446d-959e-a0f9edd0579e" />


**Output:**
<img width="1425" height="718" alt="image" src="https://github.com/user-attachments/assets/d5cf5f10-9d89-4313-9d9a-97fadfcf54ce" />


**RTL**
<img width="1080" height="660" alt="image" src="https://github.com/user-attachments/assets/d89e56f2-9811-4a54-90e7-a1b58e7b9260" />

**Timing Diagram**
<img width="1389" height="835" alt="image" src="https://github.com/user-attachments/assets/fc979923-379a-4cbf-aa68-3552b0a5a816" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

