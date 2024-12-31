# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![image](https://github.com/user-attachments/assets/d575c524-71d8-4325-9c27-11e4c85946ff)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Harshavarthan K P
RegisterNumber:24900031*/
```
```
module EXP2MAIN(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```



**Output:**
![WhatsApp Image 2024-11-26 at 13 58 01_c98d1a0c](https://github.com/user-attachments/assets/ec3ec0e0-194d-4669-a6b4-a692e4ba1642)


**Timing Diagram**
![WhatsApp Image 2024-10-30 at 08 39 28_f8dd9f63](https://github.com/user-attachments/assets/606ba53c-5fb9-45a1-96d2-dbb20fcf342e)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

