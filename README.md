## NAME : KAMALESH R
## REGISTER NUMBER : 212223230094

## Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

## Implementation-of-Half-Adder-and-Full-Adder-circuit
## AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
 ## Theory
Adders are digital circuits that carry out addition of numbers.

## Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB
#### Figure -01 HALF ADDER 
 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)



### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin


#### Figure -02 FULL ADDER 
![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)



### Procedure

Connect the supply (+5V) to the circuit Switch ON the main switch If the output is 1, then the led glows.

## Program:

## HALF ADDER 
![image](https://github.com/KAMALESHNITHYA/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743119/ece514ec-bce9-4986-ae89-06812079a5e0)

## FULL ADDER
![image](https://github.com/KAMALESHNITHYA/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743119/ff4187c6-006c-4238-980d-2f21b650cfb6)


### RTL

## HALF ADDER 
![image](https://github.com/KAMALESHNITHYA/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743119/304b3284-dffd-43fd-93c0-bc20423ea8c0)

## FULL ADDER
![image](https://github.com/KAMALESHNITHYA/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743119/10b600cb-2b81-4604-a925-cf68b76a58a1)

### TIMING DIAGRAM

## HALF ADDER 
![image](https://github.com/KAMALESHNITHYA/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743119/6be9217c-6c8d-466a-b41e-b7ec41b4b2f7)

## FULL ADDER
![image](https://github.com/KAMALESHNITHYA/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743119/d3d269a2-4b75-437a-943f-5bde17a2bf65)


### TRUTH TABLE 
## HALF ADDER 
![image](https://github.com/KAMALESHNITHYA/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743119/389b51db-a45c-400b-bb0a-6ab6d0f37414)

## FULL ADDER
![image](https://github.com/KAMALESHNITHYA/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743119/36ab7d62-ec67-4fef-bd60-9d918a8d602e)


### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog programming
