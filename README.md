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
module Logic(a,b,c,d,f1); input a,b,c,d; output f1; assign f1=((~b & ~d)|(~a &
b & d)|(a & b & ~c)); endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Paveen Kumaran S.V RegisterNumber:*/(24000025)
truth table:
![image](https://github.com/user-attachments/assets/2ae98b5e-a833-4de8-b1a6-4c117e3fbbe7)


**RTL realization**
![image](https://github.com/user-attachments/assets/3daf3808-2594-4548-afd7-9dbd7e865def)

**Output:**
![image](https://github.com/user-attachments/assets/fd48ee16-9561-4a21-b329-81a396c10b5a)

**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

