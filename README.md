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
module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule

```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:ishwarya S RegisterNumber:212225240053*/


**RTL realization**



<img width="548" height="322" alt="Screenshot 2026-03-22 100613" src="https://github.com/user-attachments/assets/64a1fd83-3e1a-4db7-989f-6b43cce775ef" />


**Output**



<img width="572" height="415" alt="Screenshot 2026-03-22 100629" src="https://github.com/user-attachments/assets/ce197dc1-1ed1-42d3-b19e-ac413805dec7" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

