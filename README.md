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
<img width="1920" height="1080" alt="Screenshot 2025-10-07 142828" src="https://github.com/user-attachments/assets/0892df32-2043-467d-8d85-24f7d5aa72e5" />
<img width="1920" height="1080" alt="Screenshot 2025-10-07 143930" src="https://github.com/user-attachments/assets/9f889852-5ab6-43bb-a5c9-714542ea861c" />


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

Developed by:Varsha M  RegisterNumber:25001006


**Output:**
<img width="1920" height="1080" alt="Screenshot 2025-10-07 142828" src="https://github.com/user-attachments/assets/05dc2c8c-80a7-44dc-b0b6-1b6077b23899" />
<img width="1920" height="1080" alt="Screenshot 2025-10-07 143930" src="https://github.com/user-attachments/assets/607df0f5-6c94-465e-9a1a-ce1a504e002c" />

**RTL**
<img width="1920" height="1020" alt="Screenshot 2025-10-07 213212" src="https://github.com/user-attachments/assets/d1be3152-2e71-4046-8cf7-f718a957b8bf" />
<img width="1920" height="1080" alt="Screenshot 2025-10-07 144323" src="https://github.com/user-attachments/assets/992c5705-9020-427d-9261-d2088e478e35" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

