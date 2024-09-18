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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/
```
Devoped by:Prasana v
RegisterNumber:21223040150
```

**Program:**
```
module de_exp_2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d) | (a & b & ~c) | (~a & b & d));
endmodule


module proj23(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2= ((~y&z)|(w&y)|(x&y));
endmodule

```



**output**

![368438773-6a3f7a61-4175-4183-bb22-e91ce1e5bfea](https://github.com/user-attachments/assets/03dc7af0-fc68-4fbb-aa61-0b75cc7a0603)

![368438829-a94b9962-e99c-4028-a265-5c906cca8121](https://github.com/user-attachments/assets/5fa6e569-6d29-4e7b-b112-f028e247cca2)

**RTL**
![368436506-14fd6235-76f8-4953-b16d-cb6df525c75e](https://github.com/user-attachments/assets/88c8bb68-7c42-4d81-919e-994a0660c229)
**Output:**![368436599-f615456c-3bf8-4097-b535-73a881238b97](https://github.com/user-attachments/assets/2c877ba4-4d91-4645-98fc-8fbaebe2553f)

**Timing Diagram**
![368436783-1b416323-e578-499c-9147-a1f![368436861-6035bc00-a957-4f97-9ae5-da1ebf80a64e](https://github.com/user-attachments/assets/aab76887-e429-40f5-b6cc-b60d618c6339)
2514fbbcb](https://github.com/user-attachments/assets/457856f2-4e37-4f0f-941c-1faf86527a83)

![368436861-6035bc00-a957-4f97-9ae5-da1ebf80a64e](https://github.com/user-attachments/assets/3b396071-adec-44d8-8d16-4fc724c2d61d)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

