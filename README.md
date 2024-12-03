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
![WhatsApp Image 2024-12-03 at 03 04 25_5f5189d7](https://github.com/user-attachments/assets/190414c0-6752-44dc-b3a5-5ebaf14d47d6)
![WhatsApp Image 2024-12-03 at 03 04 25_2e720974](https://github.com/user-attachments/assets/66cfa781-3025-43b1-b211-bf2b31463409)
![WhatsApp Image 2024-12-03 at 03 04 09_7aaa2520](https://github.com/user-attachments/assets/555669a3-eacb-4638-bdc7-13d9baaac253)


![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![WhatsApp Image 2024-12-03 at 03 04 25_82446c23](https://github.com/user-attachments/assets/71a5b136-e551-48ba-8b93-eef750bfd8c5)
![WhatsApp Image 2024-12-03 at 03 04 25_2dc23fc0](https://github.com/user-attachments/assets/06f95946-0293-4bf5-9096-5a559b06fa21)

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:S.Lokeshwaran RegisterNumber:24901149
*/

**RTL Schematic**

**Output Timing Waveform**

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



