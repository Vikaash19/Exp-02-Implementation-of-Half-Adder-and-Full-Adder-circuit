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
### Program:
~~~
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Vikaash K S
RegisterNumber: 23013426
~~~
### Code: 
### Half adder:
![Exp3 ha code](https://github.com/Vikaash19/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514589/3f32909d-40dd-4ba0-a281-72eafa57f461)

### Full adder:
![Exp3 fa code](https://github.com/Vikaash19/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514589/a7e74794-0174-46ed-96ad-59036be247ce)

### Output:
### RTL:
### Half adder:
![Exp3 ha RTL diagram](https://github.com/Vikaash19/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514589/ccffde6a-a441-458a-be4d-7c8d5839d213)

### Full adder:
![Exp3 fa RTL diagram](https://github.com/Vikaash19/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514589/e0670a81-a4d4-4ae2-9dbf-1ab14a0ea494)

### Timing diagram:
### Half adder:
![exp3 ha wave](https://github.com/Vikaash19/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514589/452315e7-25ea-4df9-b9fa-ad903c9f689e)

### Full adder:
![exp 3 fa wave](https://github.com/Vikaash19/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514589/543d036e-361e-43da-8788-a02c0a31a4c6)

### Truth table:
### Half adder:
![Exp3 truthtable (ha)](https://github.com/Vikaash19/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514589/bd488163-a74a-4c8a-acca-c774bafa9f2a)

### Full adder:
![Exp3 truthtable (fa)](https://github.com/Vikaash19/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514589/c410e2b0-cfea-4cff-ac35-34c4cf905519)

### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog
programming.
