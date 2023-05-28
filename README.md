# Design-and-Simulation-of-4-bit-adder
In this project, we will design a 4-bit adder which we will further use to design an 8-bit pipelined adder.

Steps:

1. Create a schematic diagram for the 4-bit adder using the single-bit adder we designed.

2. A symbol is laid out for a 4-bit adder.

3. A layout is drawn for the 4-bit adder, similar to the 1-bit adder.

4. A testbench is created to test the Circuit Under Test (CUT) by applying voltages at the input pins and load at the output pins.

5. Post-layout simulations are performed by extracting the circuit parasitics.

6. Observing the outputs of the 4-bit adder after post-layout simulations for the following inputs:

A=0000, B=1111, Carry In=1 

A=1010, B=0101, Carry In=0

A=1010, B=0101, Carry In=1 

A=1100, B=1000, Carry In=0

7. Calculate the delay on the output pin for each of the above cases. 

Four-bit Adder Schematic:

![schm](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/f26dcbff-0a87-41b7-a72e-174d443bda59)

Four-bit Adder Symbol:

![symbol](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/cebf7553-ef10-425d-a650-6ebdadd2c454)

Four-bit Adder Layout:

![Layout](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/da465651-81cb-4663-9c1b-4235bde872da)

Four-bit Adder Test-bench:

![Schematic](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/fcccf261-145c-40d3-87ac-e72bf17291d5)

Simulation Results:

Condition 1: A=0000, B=1111, Carry In=1

Plot:

![1a](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/1816f424-763e-4a08-a948-fd9eacb3002d)

![1b](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/63c1c674-d1f0-46b0-b326-741dc1eeab36)

Table:

![image](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/611d0fc5-e059-462b-9d55-d7b128c77bff)

![image](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/e128fec1-c55b-46b2-8d12-85328fbca1ca)

Condition 2: A=1010, B=0101, Carry In=0

Plot:

![2a](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/d7922349-8f1f-4a27-845e-c89e5327153f)

![2b](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/cd44c855-3422-4fcd-91e4-074bcd5d22c7)

Table:

![image](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/79cb41fa-4bf7-4f21-85fe-21ec52667496)

![image](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/6b970525-5a4e-4627-acf8-50c26b64c511)

Condition 3: A=1010, B=0101, Carry In=1

Plot:

![3a](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/e88d0b98-b0f9-4b41-977b-c96dc8f88d0a)

![3b](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/defb3d63-fbdb-4244-a978-62768aad53db)

Table:

![image](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/23eb9c36-5aea-46a7-9279-082a360b46a8)

Condition 4: A=1100, B=1000, Carry In=0

Plot:

![4a](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/89f89e4b-50dd-481d-a70d-ef6a130979d2)

![4b](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/5a4769dc-9ec9-4f57-8e8d-6c19b6b96e0a)

Table:

![image](https://github.com/RoshiniUdayaKumar/Design-and-Simulation-of-4-bit-adder/assets/133715179/b7949eb9-2f4d-451d-8559-056304752309)

Conclusion:

Measured delay with each input case and noticed that the delay error percentage is less than 10%.
