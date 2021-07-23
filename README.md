![Inertial Data Collection Device](https://raw.githubusercontent.com/Wanghley/Inertial-Data-Collection-Device/main/images/cover.png)<br>
[![license](https://img.shields.io/badge/CC_BY--NC--SA_4.0-A5ACA6?style=for-the-badge&logo=Creative-Commons&logoColor=black)](https://github.com/Wanghley/Inertial-Data-Collection-Device/blob/main/LICENSE) [![version](https://img.shields.io/badge/Version-3.1-00C160?style=for-the-badge&logo=&logoColor=white)](https://github.com/Wanghley/Inertial-Data-Collection-Device/releases) ![cpp](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white) ![eagle](https://img.shields.io/badge/Eagle-D57A21?style=for-the-badge&logo=autodesk&logoColor=white)  [![sponsors](https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/wanghley)


>  printed circuit board and code for collecting inertial data to research purposes of movements.

## About
Hardware developed to collect inertial data of humans (i.e. Accelerometer, Giroscope) and temperature in order to provide an open source hardware for researchs related to the analysis of human movements for many purposes.<br>
This project was tested in the diagnosis and prognosis of neuromotor diseases - Parkinson's disease mostly as part of the project of scientific research [**"Visualization Strategies to Online Big Data applied in individualized medicine"**](https://github.com/Wanghley/PIBIC-Strategies-Data-Visualization-Medicine).

## Requirements
| Dependency | Platform | Description |
| :--------- | -------- | :---------- |
| [arduino_2012](https://github.com/Wanghley/Inertial-Data-Collection-Device/blob/main/lib/arduino_2012.lbr) | eagle lib | arduino schematic and layout to **Eagle** project |
| [con-headers-jp](https://github.com/Wanghley/Inertial-Data-Collection-Device/blob/main/lib/con-headers-jp.lbr) | eagle lib | schematic and layout of female pin bars to **Eagle** project |
| [DIY modules](https://github.com/Wanghley/Inertial-Data-Collection-Device/blob/main/lib/diy-modules.lbr) | eagle lib | bluetooth adaptor fotoprint and symbol to **Eagle** project |
| [KRE](https://github.com/Wanghley/Inertial-Data-Collection-Device/blob/main/lib/kre.lbr) | eagle lib | borne connector fotoprint and symbol to **Eagle** project |
| [pinhead](https://github.com/Wanghley/Inertial-Data-Collection-Device/blob/main/lib/pinhead.lbr) | eagle lib | added in the **Eagle** project for auxiliary view of pin bars |
| [TimerOne 1.1.0](https://github.com/Wanghley/Inertial-Data-Collection-Device/blob/main/lib/TimerOne-1.1.0.zip) | arduino lib | allow running a periodic interrupt function based in finer PWM control |
| [MPU6050 0.2.1](https://github.com/Wanghley/Inertial-Data-Collection-Device/blob/main/lib/MPU6050-0.2.1.zip) | arduino lib | allow MPU6050 easy control and manipulation |
| [Wire](https://www.arduino.cc/en/reference/wire) | arduino lib | allow communication over I2C protocol |
| [SoftwareSerial](https://www.arduino.cc/en/Reference/softwareSerial) | arduino lib | allow serial communication on other digital pins of the Arduino |

## Bill of Materials
| # | Designator | Qty | Description | Obs |
| - | :--------- | --- | :---------- | :---------- | 
| 1 | R1, R2 | 2 | Resistor 220R 5% (1/4W) | Used for digital protection of bluetooth module RX |
| 2 | HC-05 | 1 | HC-05 Bluetooth Module | Module of Low supply consumption for prototype communication |
| 3 | PUSH | 2 | Push Button Long Head | Push button for hardware control and operation  |
| 4 | ON/OFF | 1 | 255sb sliding switch | Sliding switch to control energy supply of the prototype |
| 5 | LED1 | 1 | COM-09590 | 2.25 V Red LED 5mm Cylindrical indicates the hardware is ready for collection |
| 6 | LED2 | 1 | COM-09590 | 2.25 V green LED 5mm Cylindrical indicates the hardware operation mode and collection in process |
| 6 | Arduino Nano | Arduino Nano | | mother board and controller |
| 7 | KRE-2P | 1 | Borne Connector | Connector to the batery |
| 8 | BATTERY CHARGER | 1 | TP4056 | Power supply adn voltage regulator to the batery |
| 9 | RGB_LED | 1 | LED RBG 5MM | RGB LED 5mm Cylindrical indicates the mode of operation of the device |

## Development
In order to run and contribute to the PCB development you must have **Eagle**  installed in your computer and then use the .sch to work on the circuit itself and the .brd to work in the layout design.

Now, for the development under de code of hardware control you must have Arduino IDE or similar to work on the .ino code.

## Versioning
We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/Wanghley/Inertial-Data-Collection-Device/tags).

## Authors
*   **Wanghley Soares Martins** - *junior researcher* - [wanghley](https://github.com/wanghley)
*   **Fábio Henrique Monteiro Oliveira** - *research advisor* - [oliveirafhm](https://github.com/oliveirafhm)

See also the list of [contributors](https://github.com/Wanghley/PIBIC-Strategies-Data-Visualization-Medicine/contributors) who participated in this project.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledge
*   Remember, the project is free for you to use, manipulate, change and distribute. However, I am just asking you to mention us in any copy, modification as the root of your development.
*   I would advice you to try out the hardware with an analysis of the result data.
*   If you want an easier software for hardware control, check out the [CONTROL SOFTWARE](https://github.com/Wanghley/PIBIC-Strategies-Data-Visualization-Medicine)

## Gallery
General view of the projected PCB. For more images go to [images/](https://github.com/Wanghley/Inertial-Data-Collection-Device/tree/main/images) and if you still want to see more you can see 3D views on [view/](https://github.com/Wanghley/Inertial-Data-Collection-Device/tree/main/view)

![3d](https://raw.githubusercontent.com/Wanghley/Inertial-Data-Collection-Device/main/images/motion%20sense%20rev2%20assembled.png)

| ![3d](https://raw.githubusercontent.com/Wanghley/Inertial-Data-Collection-Device/main/images/board%20rev2%20-%20top.png) | ![3d](https://raw.githubusercontent.com/Wanghley/Inertial-Data-Collection-Device/main/images/board%20rev2%20-%20botton.png)|
|-|-|

![3d](https://raw.githubusercontent.com/Wanghley/Inertial-Data-Collection-Device/main/images/diagram%20rev2.png)
