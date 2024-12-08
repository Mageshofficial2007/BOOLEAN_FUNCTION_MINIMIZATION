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


i)
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```
ii)
```
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

```
Developed by: MAGESH BOOPATHI.M

RegisterNumber:24900855   

*/


**RTL realization**
**Output:**

![WhatsApp Image 2024-12-08 at 19 39 35_e2a1eead](https://github.com/user-attachments/assets/051a7459-ab65-4a7a-b93c-65c3e46014ce)


![WhatsApp Image 2024-12-08 at 19 39 39_53219871](https://github.com/user-attachments/assets/40a3d412-d08e-4a34-a65b-4060e2435c86)


**RTL**

**Timing Diagram**

![WhatsApp Image 2024-12-08 at 19 39 51_77ed130c](https://github.com/user-attachments/assets/07689aeb-525b-40df-8d14-fd1e0c41930d)


![WhatsApp Image 2024-12-08 at 19 39 54_dbff4869](https://github.com/user-attachments/assets/e80b3ad3-416b-48c1-8582-d003a828d458)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

