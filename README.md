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
### Full Adder:
![Screenshot 2024-03-23 233917](https://github.com/Aadithya2201/FULL_ADDER_SUBTRACTOR/assets/145917810/68b6f7f5-1d76-46ec-a7ee-259a45cad994)

### Full Subtractor:
![Screenshot 2024-03-23 233945](https://github.com/Aadithya2201/FULL_ADDER_SUBTRACTOR/assets/145917810/5a3e012b-20ca-4b24-85b6-e29a45bcee6a)

**Procedure**
  STEP 1: Use module project name(input,output) to start the Verilog programmming.
  STEP 2: Assign inputs and outputs using the word input and output respectively. 
  STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean expression. 
  STEP 4: Use each output to represnt onre for differnce and the other for borrow. STEP 5: End the verilog program using keyword endmodule.

**Program:**
```
/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:Rehan jeyan
RegisterNumber:212223040167
*/
```
### Full Adder:
![image](https://github.com/RehanJeyan/FULL_ADDER_SUBTRACTOR/assets/165877134/c2adaa2c-8402-40bb-80c9-7e0c5f783b33)


### Full Subtractor:
![image](https://github.com/RehanJeyan/FULL_ADDER_SUBTRACTOR/assets/165877134/109d8fba-a7b2-4369-b749-f5bbf5fc4f66)

**RTL Schematic**
### Full Adder:
![image](https://github.com/RehanJeyan/FULL_ADDER_SUBTRACTOR/assets/165877134/f503201c-40fc-42e3-b970-4ea0ee372e95)


### Full Subtractor:
![image](https://github.com/RehanJeyan/FULL_ADDER_SUBTRACTOR/assets/165877134/ac96933b-f7fe-4b95-a9cd-c11741739451)


**Output Timing Waveform**
### Full Adder:
![image](https://github.com/RehanJeyan/FULL_ADDER_SUBTRACTOR/assets/165877134/4a4d0013-642f-480c-ac0a-3e764455c868)


### Full Subtractor:
![image](https://github.com/RehanJeyan/FULL_ADDER_SUBTRACTOR/assets/165877134/43c3079e-1109-493b-a418-9f5014f3802c)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



