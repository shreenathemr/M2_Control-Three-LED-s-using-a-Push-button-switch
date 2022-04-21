# Control Three LED’s using a Push button switch
## Introduction
ATmega328 is an eight bit AVR (Advanced Virtual RISC) based microcontroller.It is a powerful microcontroller with a built-in  internal memory of around 32Kb.Most Arduino boards consist of an Atmel 8-bit AVR microcontroller with varying amounts of flash memory, pins, and features. Arduino Uno is a microcontroller board based on the ATmega328.

AVR microcontrollers are very easy to use. All AVR microcontrollers require Integrated Development Environment(IDE) such as Atmel Studio. Using this IDE, we can create, compile and debug program on all AVR microcontrollers.
## About Project and Working
Here we are going learn how to control the working of three LED’s using a push button switch. first we will connect the 3 LEDs with PB1 PB2 and PB3 of  PORTB of the microcontroller. A push button switch is then attached to PB0 pin and pulled-up using a 10K resistor. The remaining terminal of the switch is grounded. The function of a pull-up resistor is to insure that while leaving the switch as not pressed, the status of the PB0 pin should remain high. There are 20K pull-up resistors built into the ATmega chip that can be accessed from software also. But here  we are using an external pull-up circuit. When the switch is pressed, the three LED’s will glow and will turn off while we release the switch. This is how the circuit will work.

## Circuit Diagram
![Circuit diagram](https://user-images.githubusercontent.com/101713731/164499500-dabfecea-7d8b-4e9f-93ed-b7e28f38889d.jpg)

