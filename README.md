# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure
## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: Meetha Prabhu
RegisterNumber:  212222240065

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D

module exp2f1(A,B,C,D,f1);

input A,B,C,D;

output f1;

assign f1=(~B&~D)|(A&B&~C)|(~A&B&D);

endmodule

F2=xy’z+x’y’z+w’xy+wx’y+wxy

module exp2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=(~y&z)|(x&y)|(w&y);

endmodule

*/

## Output:
F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
![image](https://github.com/Meetha22003992/Experiment--02-Implementation-of-combinational-logic-/assets/119401038/9250a6c5-bf04-49f1-9929-b1800ba23fe2)

F2=xy’z+x’y’z+w’xy+wx’y+wxy
![image](https://github.com/Meetha22003992/Experiment--02-Implementation-of-combinational-logic-/assets/119401038/dbfeafa3-58b3-4aa8-bd2c-a7fafea848de)

Timing Diagram:
F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
![image](https://github.com/Meetha22003992/Experiment--02-Implementation-of-combinational-logic-/assets/119401038/de7f968b-bf5c-41e7-91b9-c72564c4be94)

F2=xy’z+x’y’z+w’xy+wx’y+wxy
![image](https://github.com/Meetha22003992/Experiment--02-Implementation-of-combinational-logic-/assets/119401038/fd697c78-7b10-4125-9b3a-990466defa75)

#Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
