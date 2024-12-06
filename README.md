![Experiment 2 1  DE](https://github.com/user-attachments/assets/2c7c1672-793f-4d57-b1a2-f55cd4e7a0df)# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions


**Logic Diagram**

![WhatsApp Image 2024-12-03 at 1 57 46 PM](https://github.com/user-attachments/assets/76112939-14d0-4894-80ed-4e5d497cf63d)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


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

![Experiment 2     DE](https://github.com/user-attachments/assets/48c5d253-fb8c-4ce6-a7ac-cfcc829b67a9)

![Experiment 2 1  DE](https://github.com/user-attachments/assets/300c6f6a-2860-424c-ac17-fa277a902e4b)



**RTL**

![Experiment 2    DE](https://github.com/user-attachments/assets/08049f27-a8d4-40ae-96da-f2bfe62b6285)


![Experiment 2 1    DE](https://github.com/user-attachments/assets/24a56b75-cc56-4866-a6a6-2f2a1d64aae3)


**Timing Diagram**

![87c5bc07-e6f1-43f6-8852-135e82674d74](https://github.com/user-attachments/assets/41ff91fa-9fc7-49af-8ca1-fe352a882119)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

