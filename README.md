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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: ABIRAMI A

RegisterNumber: 24900822

```
module experiment2(A,B,C,D,f1,w,x,y,z,f2);
input A,B,C,D,w,x,y,z;
output f1,f2;
assign f1=((~B&~D)|(~A&B&D)|(A&B&~C));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

**RTL realization**

![image](https://github.com/user-attachments/assets/96f5fc69-4d3e-440c-8218-08be5dcc8912)


**Truth table**

![image](https://github.com/user-attachments/assets/8fb2e396-2fab-416f-bf3b-0f0d07984543)

![image](https://github.com/user-attachments/assets/c6f6cbd4-5215-4752-9aeb-ad4e67c70857)

**OUTPUT**

**RTL**

![image](https://github.com/user-attachments/assets/e8e879c3-6aa4-451a-af37-a892743dc3ec)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

