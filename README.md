# st7920_cheatsheet
cheatsheet for ST7920 128x64 SPI/Parallel Display

## SPI Mode
|LCD pin|Pin Name|Function|
|--|--|--|
 | 1 | GND| GND|
 | 2 | VCC |VCC(5V)|
 | 4 | RS |  CS |
 | 5 | R/W |  Data In(connect to MOSI) |
 | 6 | E | SCK |
 | 15 | PSB | Mode(0: SPI, 1: Parallel) |
 | 19 | BLA | Backlight Anode(+) |
 | 20 | BLK | Backlight Cathode(-) |
 ## Parallel Mode
 todo

 
## Contrast
### models with potentiometer
turn the potentiometer
### models without potentiometer
1. solder JP4 pad.
2. connect voltage source to VO(V0) Pin
