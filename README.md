## Adafruit AD5693R Breakout Board - 16-Bit DAC with I2C Interface - STEMMA QT / qwiic PCB

<a href="http://www.adafruit.com/products/5811"><img src="assets/5811.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit AD5693R Breakout Board - 16-Bit DAC with I2C Interface - STEMMA QT / qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5811

### Description

Which is better, less bits or more? MORE of course! So why settle for a 12-bit DAC like the MCP4725 when you can go for the 16-bits of the AD5693? OK well there may be some reason to go with 12-bits, say if you don't need high resolution output and want to go with the more affordable DAC. But for those who like the finer things in life, the Adafruit AD5693R Breakout Board is a16-Bit DAC with I2C Interface and temperature compensated 2.5V internal reference  for a compact high-precision output. 

We break out the ADDR/A0 pin so you can connect two of these DACs on one I2C bus, just tie the A0 pin high (or close the jumper on the back) to keep it from conflicting. Also included is a 6-pin header, for use in a breadboard. Works with both 3.3V or 5V logic, and you can have the output max out at 2.5V or 5V (2xVref). If you're powering from 3.3V you will be able to set the output range to 2.5V or Vin.

Some nice extras with this chip: for chips that have 3.4Mbps Fast Mode I2C (Arduino's don't) you can update the Vout at ~200 KHz. There's an EEPROM so if you write the output voltage, you can 'store it' so if the device is power cycled it will restore that voltage. The output voltage is rail-to-rail and proportional to the power pin so if you run it from 3.3V, the output range is 0-3.3V. If you run it from 5V the output range is 0-5V.

We have an easy-to-use Arduino library and tutorial with a sine-wave output example that can be used with just about any microcontroller or microcomputer with I2C host.

Comes with a bit of 0.1" standard header in case you want to use it with a breadboard or perfboard.  Four mounting holes for easy attachment. There's an optional 3.5mm terminal block spot on the PCB - we don't include a 3.5mm terminal block but they're both common and stocked in the shop - that you can solder in place if you like.

To get you going fast, we spun up a custom-made PCB in the STEMMA QT form factor, making it easy to interface with. The STEMMA QT connectors on either side are compatible with the SparkFun Qwiic I2C connectors. This allows you to make solderless connections between your development board and the AD5693R or to chain it with a wide range of other sensors and accessories using a compatible cable.

QT Cable is not included, but we have a variety in the shop. 

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
