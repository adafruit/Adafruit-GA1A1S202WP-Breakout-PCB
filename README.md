## Adafruit GA1A1S202WP Breakout PCB

<a href="http://www.adafruit.com/products/1384"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit GA1A1S202WP Light Sensor. Format is EagleCAD schematic and board layout
* https://www.adafruit.com/products/1384

### DESCRIPTION
Upgrade a project that uses a photocell with the GA1A12S202 analog light sensor. Like a CdS photo-cell, the sensor does not require a microcontroller, the analog voltage output increases with the amount of light shining on the sensor face. This sensor has a lot of improvements that make it better for nearly any project.

The biggest improvement over plain photocells is a true log-lin relationship with light levels. Most light sensors have a linear relationship with light levels, which means that they're not very sensitive to changes in darkened areas and 'max' out very easily when there's a lot of light. Sometimes you can tweak a resistor to make them better in dark or bright light but its hard to get good performance at both ends. This sensor is logarithmic over a large dynamic range of 3 to 55,000 Lux, so it has a lot of sensitivity at low light levels but is also nearly impossible to "max out" so you can use it indoors or outdoors without changing code or calibration. Since the sensor is fabricated on a chip, there are also fewer manufacturing variations, so you won't have to calibrate the sensor from one board to another.

Using the sensor is easy as pie: connect the Vin to 2.3-6VDC, Gnd to ground and measure the analog output on OUT. It will range up to 3V (at extremely bright outdoor sunlight). On an Arduino, just use analogRead() with the OUT pin connected to an analog pin. For more information including graphs, power consumption, etc check out the datasheet in the Tech Details tab. On this breakout we placed a 68KΩ resistor from OUT to ground to turn the current into a voltage.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit.com](https://www.adafruit.com)!

Designed by Adafruit Industries. 

Creative Commons Attribution, Share-Alike license, check license.txt for more information All text above must be included in any redistribution - see license.txt for more information.
