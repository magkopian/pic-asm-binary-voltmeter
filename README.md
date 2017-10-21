## Description:
This is a very simple 8-bit binary voltmeter. It is just a very simple way to test the ADC module of your PIC, by using just 8 LEDs instead of 10.

## Configuration:
To test the code after you upload it to your PIC, you can connect a potentiometer to PA0 pin and 8 LEDs to the pins of PORTB.

##Hardware Support:
This code will work with any PIC that has a 10-bit ADC module and an 8-bit port available. You will have although to use the appropriate `PROCESSOR`, `INCLUDE` and `__CONFIG`.

The code is written to work with a 3-5MHZ clock, it is tested with 4MHz XTAL. If you use a different clock you will need to change the ADC_INIT subroutine, check out the datasheet of your PIC to find out what value to use for ADCS2, ADCS1 and ADCS0 bits of ADCON0 and ADCON1 registers.
