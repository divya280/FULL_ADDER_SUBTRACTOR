# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
FULL ADDER:

![image](https://github.com/divya280/FULL_ADDER_SUBTRACTOR/assets/82276099/1738ba8b-0254-4b75-a652-8db25e1624df)

FULL SUBTRACTOR:


![image](https://github.com/divya280/FULL_ADDER_SUBTRACTOR/assets/82276099/9d818c85-a61d-4ed5-8832-a4d3c168d26f)


**Procedure**

STEP 1: Use module project name(input,output) to start the Verilog programmming.

STEP 2: Assign inputs and outputs using the word input and output respectively.

STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean expression.

STEP 4: Use each output to represnt onre for differnce and the other for borrow.

STEP 5: End the verilog program using keyword endmodule.



**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
Developed by:V.Divyashree
RegisterNumber: 212223230051
FULL ADDER


![Screenshot 2024-04-02 081947](https://github.com/divya280/FULL_ADDER_SUBTRACTOR/assets/82276099/4c33ad52-7978-45af-9625-1572a88e8f0d)

FULL SUBTRACTOR:


![image](https://github.com/divya280/FULL_ADDER_SUBTRACTOR/assets/82276099/49c84607-fe95-4d8b-8ac7-795972e6da9a)

*/

**RTL Schematic**

FULL ADDER:


![image](https://github.com/divya280/FULL_ADDER_SUBTRACTOR/assets/82276099/445aab80-80e7-4660-a049-beffcd3bd33e)

FULL SUBTRACTOR:


![image](https://github.com/divya280/FULL_ADDER_SUBTRACTOR/assets/82276099/701b179d-ed82-49e8-ba54-79d36ae6fdae)


**Output Timing Waveform**
FULL ADDER:


![image](https://github.com/divya280/FULL_ADDER_SUBTRACTOR/assets/82276099/469ebfef-f9a0-4b0d-9405-67b88b783ab0)

FULL SUBTRACTOR:


![image](https://github.com/divya280/FULL_ADDER_SUBTRACTOR/assets/82276099/15ee41f4-f284-4b78-a59e-d1777c50f071)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



