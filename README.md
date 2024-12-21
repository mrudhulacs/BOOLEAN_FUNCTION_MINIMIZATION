
**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**minimization**

F1

![F1](https://github.com/user-attachments/assets/d0bae9fe-4b8f-4d46-9f2a-8cd5c40b8f6b)

F2





![TRUTH TABLE](https://github.com/user-attachments/assets/e79cf50c-faa9-4171-be0c-e0350488a607)





**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:CHITTOOR SARAVANA MRUDHULA                                         RegisterNumber:24003790

```
module funct_1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1 = ((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
```

```
module funct_2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2 = ((~y&z)|(w&y)|(x&y));
endmodule
```


**Output:**

F1

![Experiment 2     DE](https://github.com/user-attachments/assets/48c5d253-fb8c-4ce6-a7ac-cfcc829b67a9)

 F2

![Experiment 2 1  DE](https://github.com/user-attachments/assets/300c6f6a-2860-424c-ac17-fa277a902e4b)



**RTL**

F1

![Experiment 2    DE](https://github.com/user-attachments/assets/08049f27-a8d4-40ae-96da-f2bfe62b6285)

F2 

![Experiment 2 1    DE](https://github.com/user-attachments/assets/24a56b75-cc56-4866-a6a6-2f2a1d64aae3)


**Timing Diagram**




**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

