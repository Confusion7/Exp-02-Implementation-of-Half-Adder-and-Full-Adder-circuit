# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

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

## Program:

Developed by: MOHAMMED SAAJID S

Register Number: 212223240093

## CODE:

### HALF ADDER:

![Exp3 ha code](https://github.com/Confusion7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/141727149/6c3bab21-c4b8-4e7b-9f1d-ac24e46fcc4b)

### FULL ADDER:

![Exp3 fa code](https://github.com/Confusion7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/141727149/2dee1f7b-1f98-4c7a-8176-e216f8287e61)



## Output:
## RTL:

### HALF ADDER:

![Exp3 ha RTL diagram](https://github.com/Confusion7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/141727149/e5cdaadc-7113-4178-89e1-d1856750bd35)


### FULL ADDER:

![Exp3 fa RTL diagram](https://github.com/Confusion7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/141727149/8fd7952c-b8b2-4945-8fcb-2e1433087dc6)


## TRUTH TABLE:

### HALF ADDER:

![Exp3 truthtable (ha)](https://github.com/Confusion7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/141727149/251c2953-0a87-4d64-b473-33176455e816)

### FULL ADDER:

![Exp3 truthtable (fa)](https://github.com/Confusion7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/141727149/c32a3fe2-5708-4e25-832e-52bacc9a69ff)


## TIMING DIAGRAM:

### HALF ADDER:

![WhatsApp Image 2023-11-26 at 11 49 06 AM](https://github.com/Confusion7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/141727149/f2be5d0f-9954-40c3-ba02-caf386354e82)

### FULL ADDER:

![WhatsApp Image 2023-11-26 at 11 49 07 AM](https://github.com/Confusion7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/141727149/7ef169ab-9d53-4362-bc03-5da2626d3de4)




## Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog programming.
