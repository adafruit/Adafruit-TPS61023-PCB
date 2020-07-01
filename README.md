## Adafruit Adafruit MiniBoost 5V at 1A - TPS61023 PCB

<a href="http://www.adafruit.com/products/4654"><img src="assets/4654.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Adafruit MiniBoost 5V at 1A - TPS61023.

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4654

### Description

This adorable little board will come in very handy whenever you need a good amount of 5V power. It's the size of a linear regulator, but it's actually a mini-booster! Input 2-5VDC on one side, and get 5V at up to 1A supply on the other. Perfect for use with battery-powered projects with 2 or 3 Alkaline, or a single Lithium battery.

This booster uses a very small but thermally efficient chip from TI, the TPS61023. This chip has nearly everything integrated, including dual 3A MOSFET switches. Note that the switch doesn't tell you the max output, see the tables below for that!

We set the feedback resistors to give a 5.2V output, this is a little higher than 5V which helps account for voltage drop over cables. We took some measurements of the input/output current and max draw using a bench-top power supply and electronic load:

    At 2V DC in, max current out at 5V is 300mA (the minimum input voltage that will 'boot' the booster)
    At 2.5V DC in, max current out at 5V is 500mA (two NiMH rechargables)
    At 3V DC in, max current out at 5V is 800mA (two alkalines or a near-dead LiPo)
    At 3.5V DC in, max current out at 5V is 1100 mA (this is a LiPoly nominal voltage)
    At 4V DC in, max current out at 5V is 1400 mA (3 NiMH, or a fresh LiPoly)

Most people will want to use a Lipoly or LiIon battery with a booster, with a nominal voltage of 3.7V. Here's the efficiencies at that voltage:

    5.2V 100mA out requires 160mA in at 3.7V (88%)
    5.2V 250mA out requires 400mA in at 3.7V (88%)
    5.2V 500mA out requires 800mA in at 3.7V (88%)
    5.2V 1000mA out requires 1800mA in at 3.7V (78%)

As you can see, you'll be humming at ~88% as 'lower' currents of about 500mA and less. You can get 1A out but your efficiency will drop a bit to ~78%

You get one fully assembled breakout with a TPS61023 and components, and a small bit of header. Give it 3-5V on the IN and ground pins. Then you'll have 5V on the OUT pin. The enable pin can be pulled low to disable the output, its a 'true disconnect' so the output will be completely de-powered.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution.
See license.txt for additional details.
