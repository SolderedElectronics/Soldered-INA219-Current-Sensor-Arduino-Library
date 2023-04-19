# Voltage & current sensor INA219 breakout Arduino library

[![Make docs and publish to GitHub Pages](https://github.com/SolderedElectronics/Soldered-INA219-Current-Sensor-Arduino-Library/actions/workflows/make_docs.yml/badge.svg?branch=dev)](https://github.com/SolderedElectronics/Soldered-INA219-Current-Sensor-Arduino-Library/actions/workflows/make_docs.yml)
[![Arduino Library Manager Compatibility](https://github.com/SolderedElectronics/Soldered-INA219-Current-Sensor-Arduino-Library/actions/workflows/arduino_lint.yml/badge.svg?branch=dev)](https://github.com/SolderedElectronics/Soldered-INA219-Current-Sensor-Arduino-Library/actions/workflows/arduino_lint.yml)


| ![Voltage & current sensor INA219 breakout](https://upload.wikimedia.org/wikipedia/commons/8/8f/Example_image.svg) |
| :----------------------------------------------------------------------------------------------------------------: |
|                      [Voltage & current sensor INA219 breakout](https://www.solde.red/333066)                      |

The INA219 is a digital device that allows the measurement of current, voltage, and therefore power. Simply, connect wire serial through this device and it will give all the information provided via I2C communication. It is very simple and reliable to use. It has a jumper for making changes to the I2C address so you can connect more than one INA219 to single microcontroller.

The maximum current of the measurement is determined by the shunt resistor found on the plate which is 0.1ohm (± 3.2A). Yes, it can measure the power in both directions! If you want to measure other currents or smaller currents more precisely, check out the datasheet to change that resistor. The maximum voltage that can be measured is 26V.

- Power supply voltage: 3V - 5V
- Maximum measuring voltage: 26V
- Maximum measuring current: 3.2A
- ADC: 12-bit
- Dimensions: 38 x 22mm (https://www.soldered.com/en/easyC)

### Repository Contents

- **/src** - source files for the library (.h & .cpp)
- **/examples** - examples for using the library
- **_other_** - _keywords_ file highlights function words in your IDE, _library.properties_ enables implementation with Arduino Library Manager.

### Hardware design

You can find hardware design for this board in [_Voltage & current sensor INA219 breakout_](https://github.com/SolderedElectronics/Voltage---current-sensor-INA219-breakout-hardware-design) hardware repository.

### Documentation

Access Arduino library documentation [here](https://SolderedElectronics.github.io/Soldered-INA219-Current-Sensor-Arduino-Library/).

- Tutorial for using the Voltage & current sensor board
- Installing an Arduino library

### Board compatibility

The library is compatible with board & microcontroller families shown in green below:

[![Compile Sketches](http://github-actions.40ants.com/e-radionicacom/Soldered-INA219-Current-Sensor-Arduino-Library/matrix.svg?branch=dev&only=Compile%20Sketches)](https://github.com/SolderedElectronics/Soldered-INA219-Current-Sensor-Arduino-Library/actions/workflows/compile_test.yml)

### About Soldered

<img src="https://raw.githubusercontent.com/e-radionicacom/Soldered-Generic-Arduino-Library/dev/extras/Soldered-logo-color.png" alt="soldered-logo" width="500"/>

At Soldered, we design and manufacture a wide selection of electronic products to help you turn your ideas into acts and bring you one step closer to your final project. Our products are intented for makers and crafted in-house by our experienced team in Osijek, Croatia. We believe that sharing is a crucial element for improvement and innovation, and we work hard to stay connected with all our makers regardless of their skill or experience level. Therefore, all our products are open-source. Finally, we always have your back. If you face any problem concerning either your shopping experience or your electronics project, our team will help you deal with it, offering efficient customer service and cost-free technical support anytime. Some of those might be useful for you:

- [Web Store](https://www.soldered.com/shop)
- [Tutorials & Projects](https://soldered.com/learn)
- [Community & Technical support](https://soldered.com/community)

### Original source
​
This library is possible thanks to original [Arduino-INA219](https://github.com/jarzebski/Arduino-INA219) library. Thank you, Korneliusz Jarzębski.

### Open-source license

Soldered invests vast amounts of time into hardware & software for these products, which are all open-source. Please support future development by buying one of our products.

Check license details in the LICENSE file. Long story short, use these open-source files for any purpose you want to, as long as you apply the same open-source licence to it and disclose the original source. No warranty - all designs in this repository are distributed in the hope that they will be useful, but without any warranty. They are provided "AS IS", therefore without warranty of any kind, either expressed or implied. The entire quality and performance of what you do with the contents of this repository are your responsibility. In no event, Soldered (TAVU) will be liable for your damages, losses, including any general, special, incidental or consequential damage arising out of the use or inability to use the contents of this repository.

## Have fun!

And thank you from your fellow makers at Soldered Electronics.
