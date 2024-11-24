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

Developed by: Varshinee.S
RegisterNumber:*/ 24001721

(i)
module exp2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule

(ii)
module exp22(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(w&y)|(x&y));
endmodule


**RTL realization**
![Screenshot (1)](https://github.com/user-attachments/assets/ba17caae-155d-46ea-90de-b3910259740e)

![Screenshot 2024-11-24 080703](https://github.com/user-attachments/assets/2e53fedc-5fa6-4fc3-8961-2cb357f2ddf5)

**Timing Diagram**
![Screenshot (2)](https://github.com/user-attachments/assets/69165981-49c0-459a-bfcf-64f2962bf5dd)

![Screenshot 2024-11-24 080455](https://github.com/user-attachments/assets/17cd932a-c168-48de-8d65-e5797fecdabf)
**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

