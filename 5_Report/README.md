                                           Control Two LED’s using a Push button switch
                                           ------------------------------------------------

INTRODUCTION
---------------------------------------------------
atmega full form is Advanced Technology for Memory and Logic. ATMega Microcontrollers belong to the AVR family of microcontrollers and is manufactured by Atmel Corporation. An ATMega Microcontroller is an 8-bit microcontroller with Reduced Instruction Set (RISC) based Harvard Architecture.

ABOUT PROJECT AND WORKING
------------------------------------------------
Here we are going learn how to control the working of two LED’s using a push button switch.First we will connect the 2 LEDs with PB2 and PB3 of PORTB of the microcontroller. A push button switch is then attached to PB0 pin and pulled-up using a 10K resistor. The remaining terminal of the switch is grounded. The function of a pull-up resistor is to insure that while leaving the switch as not pressed, the status of the PB0 pin should remain high. There are 20K pull-up resistors built into the ATmega chip that can be accessed from software also. But here we are using an external pull-up circuit. When the switch is pressed, the two LED’s will glow and will turn off while we release the switch. This is how the circuit will work.
__________________________________________________________________________________
objective:
to glow led using reset buttons
________________________________
Components:
--------------------------
1.ATmega 328

2.resistor(10k and 330 ohms)

3.supply(fixed voltage)

4.LED'S

5.push buttons(reset buttons)

6.Ground(0v)
_________________________________________
output:led is on when simulation is running..



