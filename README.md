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
![WhatsApp Image 2024-12-03 at 10 44 02 PM](https://github.com/user-attachments/assets/58ab3e60-b2e0-4113-a9ae-0322f122c377)
![WhatsApp Image 2024-12-03 at 10 44 01 PM](https://github.com/user-attachments/assets/95d09b22-b860-46ab-9124-f0e0fb2bf96d)

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/
![Screenshot 2024-12-03 222842](https://github.com/user-attachments/assets/632a7ee8-c441-4906-9552-71d9c02a1bda)
![Screenshot 2024-12-03 223736](https://github.com/user-attachments/assets/4d6d7e08-2441-418c-94ed-f8aa371eab0b)
Designed by: Sukanth K R
Registered Number: 24000723
**RTL Schematic**
![Screenshot 2024-12-03 222901](https://github.com/user-attachments/assets/a5b6b61c-3f6f-4ee1-a1b5-42e2adbe1edb)
![Screenshot 2024-12-03 223736](https://github.com/user-attachments/assets/0427b480-efe7-48e9-822a-9ef5c33a1052)

**Output Timing Waveform**
![Screenshot 2024-12-03 223130](https://github.com/user-attachments/assets/fe6a4a35-bbe7-4a39-94e5-0a93e4f77020)
![Screenshot 2024-12-03 224000](https://github.com/user-attachments/assets/61b0b4b2-de0d-471c-bdd8-82c3c00bb13e)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



