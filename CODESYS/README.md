 # CODESYS Driver

This is the Codesys driver for the [4-RELAYS Heavy Duty Stackable Card for Raspberry Pi](https://sequentmicrosystems.com/product/4-relays-heavy-duty-stackable-card-for-rpi/).

We include the source code library in the package so everyone can modify. Note that it is an open source library with absolutely no warranty.
Checkout our example project for guidance.

For using multiple card in the same time you need to set the card stack lever from jumpers and modify the "I2C address" parameter of the "MEGA4Relay" device, below you find the correspondence between stack level and hardware address:

| Stack Level | I2C address |
| --- | --- |
| 0 | 16#3F |
| 1 | 16#3E |
| 2 | 16#3D |
| 3 | 16#3C |
| 4 | 16#3B |
| 5 | 16#3A |
| 6 | 16#39 |
| 7 | 16#38 |

 # Important Notice
We are thankful to [nikke344](https://github.com/nikke344) who helped to develop the library.
 
