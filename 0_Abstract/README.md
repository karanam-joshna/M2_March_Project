INTRODUCTION
-----------------------------------------------
atmega full form is Advanced Technology for Memory and Logic.
ATMega Microcontrollers belong to the AVR family of microcontrollers and is manufactured by Atmel Corporation. An ATMega Microcontroller is an 8-bit microcontroller with Reduced Instruction Set (RISC) based Harvard Architecture.
__________________________________________________________________________
ABOUT PROJECT AND WORKING
------------------------------------------------
Here we are going learn how to control the working of two LED’s using a push button switch.First we will connect the 2 LEDs with PB2 and PB3 of  PORTB of the microcontroller. A push button switch is then attached to PB0 pin and pulled-up using a 10K resistor. The remaining terminal of the switch is grounded. The function of a pull-up resistor is to insure that while leaving the switch as not pressed, the status of the PB0 pin should remain high. There are 20K pull-up resistors built into the ATmega chip that can be accessed from software also. But here  we are using an external pull-up circuit. When the switch is pressed, the two LED’s will glow and will turn off while we release the switch. This is how the circuit will work.
________________________________________________________________________________________________
