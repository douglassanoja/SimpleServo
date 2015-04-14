# Simple Servo Demo

Playing with a Model Craft ES-05 servo

Need:

* Device: PIC16F1709 (or other PIC16F1 in 20-pin DIP)
* Board: PICDEM(tm) Low Pin Count (use expansion connector) 
* Debugger: PICkit© 3

## The Basic Idea
1. Connect the servo to GND, VDD, RC2 (bottom 3 pins of LPC expansion connector)
2. Launch MPLAB X and MPLAB Code Configurator to quickly initialise all the peripherals: TMR2, PWM1, ADC, I/Os
3. 5 x lines of code (ADC_ISR) is all you need to write (in main)...


## Further development Ideas
* Might want to control multiple servos using the other PWMs (there are 3 more)
* Perhaps use the serial port / BLE Click to control the servo position...

## Related Projects and Demos

* Check the [Simplicity](https://github.com/luciodj/Simplicity) project for more demo like this using the MPLAB Code Configurator and the MikroElektronika Click(tm) boards.
