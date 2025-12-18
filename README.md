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


module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule


**RTL realization**: **RTL**

<img width="1232" height="208" alt="Screenshot 2025-12-18 104134" src="https://github.com/user-attachments/assets/91880c12-795a-47b7-87a0-cbbabd252ada" />


**Output:**

<img width="1216" height="628" alt="Screenshot 2025-12-18 104119" src="https://github.com/user-attachments/assets/cacac754-242d-49ce-ad58-d58837f186e4" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

