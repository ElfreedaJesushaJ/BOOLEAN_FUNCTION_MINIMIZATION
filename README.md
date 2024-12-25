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
Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:ELFREEDA JESUSHA J
RegisterNumber:24900146
```
```
module boolmin(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=(~b&~d)|(~a&b&d)|(a&b&~c);
endmodule

```


**RTL realization**
![Screenshot 2024-12-25 113004](https://github.com/user-attachments/assets/f2932bc0-d01c-4da8-bf15-5843949bf3ad)



**Output:**
![boolmin rtl](https://github.com/user-attachments/assets/3914b6d1-de14-4fce-8026-18f3ff03555c)


**RTL**

**Timing Diagram**
![boolmin wf](https://github.com/user-attachments/assets/c436c916-7a4a-4174-b51e-bfd87c9834f6)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

