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
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Harshavarthan K P
RegisterNumber:24900031*/
```
```
module exe_2(f_and,f_or,f_not,f_nor,f_nand,f_xor,f_xnor,a,b);
input a,b;
output f_and,f_or,f_not,f_nor,f_nand,f_xor,f_xnor;
and(f_and,a,b);
or(f_or,a,b);
not(f_not,a);
nand(f_nand,a,b);
nor(f_nor,a,b);
xor(f_xor,a,b);
xnor(f_xnor,a,b);
endmodule
```



**Output:**
![WhatsApp Image 2024-11-26 at 13 58 01_c98d1a0c](https://github.com/user-attachments/assets/ec3ec0e0-194d-4669-a6b4-a692e4ba1642)


**Timing Diagram**
![WhatsApp Image 2024-10-30 at 08 39 28_f8dd9f63](https://github.com/user-attachments/assets/606ba53c-5fb9-45a1-96d2-dbb20fcf342e)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

