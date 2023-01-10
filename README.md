## Adafruit PCA9546 4-Channel I2C Multiplexer PCB

<a href="http://www.adafruit.com/products/5663"><img src="assets/5663.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>
<br>
<a href="http://www.adafruit.com/products/5664"><img src="assets/5664-01.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit PCA9546 4-Channel I2C Multiplexer and STEMMA QT / Qwiic PCA9546 Breakout. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5663
* https://www.adafruit.com/product/5664

### Description

You just found the perfect I2C sensor, and you want to wire up two or three or more of them to your Arduino when you realize "Uh oh, this chip has a fixed I2C address, and from what I know about I2C, you cannot have two devices with the same address on the same SDA/SCL pins!" Are you out of luck? You would be if you didn't have this ultra-cool PCA9546 1-to-4 I2C multiplexer!

Finally, a way to get up to 4 same-address I2C devices hooked up to one microcontroller - this multiplexer acts as a gatekeeper, shuttling the commands to the selected set of I2C pins with your command.  If you need to have up to 8 multiplexed devices, check out the 8-channel TCA9548 version of this board.

Using it is fairly straight-forward: the multiplexer itself is on I2C address 0x70 (but can be adjusted from 0x70 to 0x77) and you simply write a single byte with the desired multiplexed output number to that port, and bam - any future I2C packets will get sent to that port. In theory, you could have 8 of these multiplexers on each of 0x70-0x77 addresses in order to control 8*4 = 32 of the same-I2C-addressed-part.

Like all Adafruit breakouts, we put this nice chip on a breakout for you so you can use it on a breadboard with capacitors, and pullups and pulldowns to make usage a snap. Some header is required, and once soldered, you can plug it into a solderless breadboard. The chip itself is 3V and 5V compliant, so you can use it with any logic level.

Comes with only the assembled PCB, no cables or sensors included (we have tons available though!)

The Adafruit STEMMA QT / Qwiic PCA9546 Breakout - 4 Channel has five JST SH 1mm connectors: 1 input and 4 outputs. There's one port at the end that connects to your I2C controller (there are also breadboard breakout pins if you need them). Use this breakout to add as many I2C devices to the bus as you need. Complete with mounting holes so the board can be added to any system. A small power LED lets you know that the hub board has connectivity.

There's even an onboard 3.3V 500mA regulator, so if you're using this with a 5V microcontroller like an Arduino 328-compatible, you can level shift all the QT ports to have 3V power and logic level. Simply cut/solder the jumper on the bottom of the PCB to change the power and logic level to be forced 3V.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
