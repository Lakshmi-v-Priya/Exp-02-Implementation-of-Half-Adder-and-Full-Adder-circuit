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
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program: Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: LAKSHMI PRIYA V
RegisterNumber: 212223220049 

### CODE:
FULL ADDER 
![Exp3 fa code](https://github.com/Lakshmi-v-Priya/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151720706/7c579faf-0a87-42a3-a96d-ced8a655a62e)

HALF ADDER 
![Exp3 ha code](https://github.com/Lakshmi-v-Priya/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151720706/82efe3d2-6721-454f-9191-f44c1d8943c4)

### TRUTH TABLE :
FULL ADDER 
![Exp3 truthtable (fa)](https://github.com/Lakshmi-v-Priya/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151720706/5e952c1d-d55c-4380-a188-1f4925f69939)

HALF ADDER 
![Exp3 truthtable (ha)](https://github.com/Lakshmi-v-Priya/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151720706/ef4d1133-79f6-4147-80d3-24565c853c0a)

### RTL DIAGRAM :
FULL ADDER 
![Exp3 fa RTL diagram](https://github.com/Lakshmi-v-Priya/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151720706/f804f1d2-224b-4f37-be57-ee379a720309)

HALF ADDER:
![Exp3 ha RTL diagram](https://github.com/Lakshmi-v-Priya/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151720706/1391a789-f569-4bc8-a290-fcd8da28a678)

### OUTPUT :
FULL ADDER :
![exp 3 fa wave](https://github.com/Lakshmi-v-Priya/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151720706/09807ec1-6fe2-460c-892b-9300f74f0bd7)

HALF ADDER :
![exp3 ha wave](https://github.com/Lakshmi-v-Priya/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151720706/4d9ab3bd-4c8b-4604-9aea-479013c7742a)



### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog
programming
