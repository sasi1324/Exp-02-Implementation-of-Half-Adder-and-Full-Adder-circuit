# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit


i)Hald Adder



![image](https://github.com/sasi1324/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313315/062fcdb7-c981-4871-9a35-8a82b056a85e)



ii)Full Adder


![image](https://github.com/sasi1324/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313315/e59591f7-7249-4adf-9d7d-851542c98382)



Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by:Sasinthara
RegisterNumber: 23005130  
*/
Logic symbol & Truthtable
RTL realization

### Output:
### RTL

i)Half Adder






![image](https://github.com/sasi1324/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313315/2a91dfbc-8bb7-4770-ba56-17477ed96235)








ii)Full Adder








![image](https://github.com/sasi1324/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313315/93b81a40-674e-4fa5-a6f1-6fe6202f2d07)




### TIMING DIAGRAM



i)Half Adder





![image](https://github.com/sasi1324/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313315/a055ce01-6c00-4955-8ed5-81fa21f75c37)





ii)Full Adder






![image](https://github.com/sasi1324/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313315/e8a7fd14-23f4-4d4e-82a7-f3b8e10e5943)



### TRUTH TABLE 




i)Half Adder





![image](https://github.com/sasi1324/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313315/347d70b3-1a09-4446-aef1-5fedbb78c4e1)





ii)Full Adder






![image](https://github.com/sasi1324/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313315/cb544279-f06b-48ac-b256-f33d521ebd88)








### Result:

To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
