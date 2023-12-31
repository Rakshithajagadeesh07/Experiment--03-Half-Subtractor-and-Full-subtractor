# Experiment-04-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
 Hardware – PCs, Cyclone II , USB flasher
 
 Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor and Full Subtractor:
## Half Subtractor:
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.

![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)

Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor:
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 

![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)

Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
1.Use module projname(input,output) to start the Verilog programmming.

2.Assign inputs and outputs using the word input and output respectively.

3.Use defined keywords like wire,assign and required logic gates to represent the boolean expression.

4.Use each output to represnt onre for differnce and the other for borrow.

5.End the verilog program using keyword endmodule.

## Program:
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

Developed by: RAKSHITHA J

RegisterNumber: 212223240135

## Code:
HALF SUBTRACTOR:

![Exp4 hs code](https://github.com/Rakshithajagadeesh07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147081797/bb9c7f07-ad8a-4c97-8c83-592b76024714)

FULL SUBTRACTOR:

![Exp4 fs code](https://github.com/Rakshithajagadeesh07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147081797/df8286c7-5865-4e83-9620-d33374ce3909)

## RTL realization:
HALF SUBTRACTOR:

![Exp4 hs RTL diagram](https://github.com/Rakshithajagadeesh07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147081797/3e85e259-fdf2-473a-834a-259442187e45)

FULL SUBTRACTOR:

![Exp4 fs RTL diagram](https://github.com/Rakshithajagadeesh07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147081797/c6fa92c2-abe6-47cb-a845-47046b2cd103)

## Truth Table:
HALF SUBTRACTOR:

![Exp4 truthtable hs](https://github.com/Rakshithajagadeesh07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147081797/9cbd307b-5e06-41fd-a248-f7de5e4c9327)

FULL SUBTRACTOR:

![Exp4 truthtable fs](https://github.com/Rakshithajagadeesh07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147081797/f30f73bc-9e70-46a2-8e91-607e5b48591c)

## Timing diagram:
HALF SUBTRACTOR:
![hs wave](https://github.com/Rakshithajagadeesh07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147081797/cc2a58bb-1563-4f99-80c6-5bf4f73c2db2)

FULL SUBTRACTOR:
![fs wave](https://github.com/Rakshithajagadeesh07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147081797/5d6054c1-40ad-45ef-9969-e50cf18f4473)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
