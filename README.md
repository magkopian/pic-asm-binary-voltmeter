<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
</head>

<body>

<h3>Description:</h3>
<p>
This is a very simple 8-bit binary voltometer. It is just a very simple way to test the ADC module of your PIC, by using just 8 LEDs instead of 10.
</p>


<h3>Configuration:</h3>
<p>
To test the code after you upload it to your PIC, you can connect a potentiometer to PA0 pin and 8 LEDs to the pins of PORTB.
</p>

<h3>Hardware Support:</h3>
<p>
This code will work with any PIC that has a 10-bit ADC module and an 8-bit port available. 
You will have although to use the appropriate PROCESSOR, INCLUDE and __CONFIG.
</p>
<p>
The code is written to work with a 3-5MHZ clock, it is tested with 4MHz XTAL. If you use a different clock you will need to change the ADC_INIT subroutine, 
check out the datasheet of your PIC to find out what value to use for ADCS2, ADCS1 and ADCS0 bits of ADCON0 and ADCON1 registers.
</p>
</body>
</html>

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/magkopian/pic-binary-voltometer/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

