# RC_SRC
Contains the source code for the RC control and E-Brake systems

## Requirements
- Two Joystick inputs
- Button input for E-brake
- Button input for FWD/REV selection
- Connect to LoRa breakout via SPI
- Send rc control signals & estop signals
- switch selector for control mode (rc vs standard)
- 0.96" oled display controlled via i2c
  - [teensy 4.0 i2c library](https://github.com/Richard-Gemmell/teensy4_i2c)
  - [0.96 inch oled display](https://www.amazon.com/HiLetgo-Serial-128X64-Display-Color/dp/B06XRBTBTB/ref=asc_df_B06XRBTBTB/?tag=hyprod-20&linkCode=df0&hvadid=312232463708&hvpos=&hvnetw=g&hvrand=14642893706602934746&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9016722&hvtargid=pla-563271619351&psc=1&tag=&ref=&adgrpid=57656765450&hvpone=&hvptwo=&hvadid=312232463708&hvpos=&hvnetw=g&hvrand=14642893706602934746&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9016722&hvtargid=pla-563271619351)
- potentiometer for max-speed setting
