# MSP430-Lock

*      Description *:     
                        This program in assembly first begins with the blinking
                        on and off of the decimal point. The purupose of this is
                        to represent a locked state. To unlock the device the user
                        must input 2231. Once the user inputs a 2, the decimal
                        will stop blinking. As the next correct digit is entered
                        the code will step through, waiting for the next correct
                        digit. If a incorrect digit is entered in such a way to 
                        where the pattern can not be 2231, such as 22231, the 
                        device will go back to the blinking of the decimal, waiting
                        for the correct code once again. Once the correct code
                        sequence is entered the device will blink a 'E'. To relock
                        the device, press the button on the bottom left hand side.
