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
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by:JOTHIKRISHNAA V 
RegisterNumber:212223100017  
*/
Logic symbol & Truthtable
RTL realization

### CODE:
### Half Adder
![program](https://github.com/JothikrishnaaVengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514555/9da19b70-4111-497c-9318-79be73613712)

### Full Adder
![program](https://github.com/JothikrishnaaVengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514555/b16ce2b1-a561-416e-aea0-02056866993b)

### RTL
### Half Adder
![RTL viewer](https://github.com/JothikrishnaaVengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514555/856189e2-49d0-4d97-bdb2-c88b3f960e0b)

### Full Adder
![RTL viewer](https://github.com/JothikrishnaaVengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514555/199d6dbe-3730-4517-8e68-6e91b0360b5f)

### TIMING DIAGRAM
### Half Adder
![Timing diagram](https://github.com/JothikrishnaaVengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514555/c74a943a-9832-42c1-80aa-db6e99b24327)

### Full Adder
![Timing diagram](https://github.com/JothikrishnaaVengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514555/8261e6fd-df3f-40b5-be6c-c02aadec5fe1)

### TRUTH TABLE 
### Half Adder
![truth table](https://github.com/JothikrishnaaVengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514555/2cfe6368-debd-4fab-b6fa-690eec773378)

### Full Adder
![truth table](https://github.com/JothikrishnaaVengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514555/476ae7ea-1051-45cd-91cf-c2a5ce0b1d7c)

### Result:
Thus designed a half adder and full adder circuit and verified its truth table in Quartus using Verilog programming.
