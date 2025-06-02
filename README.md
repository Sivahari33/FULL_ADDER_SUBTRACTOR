NAME:SIVHARIBALAN
REG NO:212224220103
# FULL ADDER SUBTRACTOR

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

![image](https://github.com/user-attachments/assets/5bed67a9-12de-4261-92e5-9db10904321a)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![300521081-02b24f51-ab51-4304-9ad6-7b81ffc1ead5](https://github.com/user-attachments/assets/4c5adeb1-bf07-44b7-8698-865dd4ee71a1)


Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![391088496-3a93e910-461f-4e76-8565-a18d9014d0a8](https://github.com/user-attachments/assets/bd047613-1a73-4357-89ee-3df2e19dea00)

**Procedure**
Write the detailed procedure here

1 Type the program in Quartus software.

2 Compile and run the program. 

3 Generate the RTL schematic and save the logic diagram.

4 Create nodes for inputs and outputs to generate the timing diagram.

5 For different input combinations generate the timing diagram.

**Program:**

![391082567-9ee22bc1-825a-41ca-b19c-38b9c05d3fa0](https://github.com/user-attachments/assets/94090f0e-fd8f-4835-b9af-2799e66bdcb2)


**RTL Schematic**
![391082756-97ab4fe5-d382-4d0c-a461-30ad8b182437](https://github.com/user-attachments/assets/32e93a04-65d2-47ee-b803-addfc9fbb45f)

**Output Timing Waveform**
![391082802-4cfc2e62-4396-41f9-b584-cba1a3419c49](https://github.com/user-attachments/assets/8caed757-52e4-445a-aae6-2bc81c3f1055)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



