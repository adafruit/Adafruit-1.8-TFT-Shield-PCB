## Adafruit 1.8" 18-bit Color TFT Shield w/microSD and Joystick PCB

<a href="http://www.adafruit.com/products/802"><img src="assets/802.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit 1.8" 18-bit Color TFT Shield. Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/802

### Description

This lovely little shield is the best way to add a small, colorful and bright display to any project. We took our popular 1.8" TFT breakout board and remixed it into an Arduino shield complete with microSD card slot and a 5-way joystick navigation switch and three selection buttons! Since the display uses only 4 pins to communicate and has its own pixel-addressable frame buffer, it can be used easily to add a display & interface without exhausting the memory or pins.

New! We've updated this shield to be 'Arduino R3' format compatible so you can now use it with any and all Arduinos or Metros - including the Metro M0 or M4, Arduino Mega, Zero, etc. We also use Adafruit seesaw for the TFT backlight, TFT reset, and button inputs - you can query the buttons and joystick over I2C now, so only 2 pins are needed to communicate with all 8 switches.

The 1.8" display has 128x160 color pixels. Unlike the low cost "Nokia 6110" and similar LCD displays, which are CSTN type and thus have poor color and slow refresh, this display is a true TFT! The TFT driver (ST7735R) can display full 18-bit color (262,144 shades!).

The shield has the TFT display soldered on (it uses a delicate flex-circuit connector) as well as a ultra-low-dropout 3.3V regulator and a 3/5V level shifter so its safe to use with 3V or 5V Arduino compatibles. We also had some space left over so we placed a microSD card holder (so you can easily load full color bitmaps from a FAT16/FAT32 formatted microSD card), a 5-way navigation switch (left, right, up, down, select) and three tactile buttons marked A BC. The microSD card is not included, but you can pick one up here.

If you just want to display text, shapes, lines, pixels, etc the shield uses the SPI pins (SCK/MOSI/MISO), I2C pins (SDA & SCL) and digital #8. For the microSD card, you'll also give up Digital #4. This shield works with any Arduino UNO and compatibles, Mega, Zero, etc. If it's shield compatible, you're good to go.


### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.