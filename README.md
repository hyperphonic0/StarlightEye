# StarlightEye: OpenSource IMX585 Camera Board for Raspberry Pi
![](/img/PCBA.jpg)


## Introduction
Welcome to the **StarlightEye** project, an open-source camera board designed for Raspberry Pi Compute Module 4 boards using the IMX585. This project aims to provide a high-quality, affordable, and accessible camera module for advanced Raspberry Pi projects. The board is designed using KiCad v6, a popular open-source electronics design automation (EDA) software.

StarlightEye captures stunning high-resolution images and videos with improved low-light performance and dynamic range. It's perfect for photography enthusiasts, developers, and makers who want to level up their Raspberry Pi projects with a powerful camera.

## Features
* IMX585 sensor
* **Open-source hardware and software**
* Integrated IR filter switch control via I2C based on CH32V003
* Integrated TMP117 temperature sensor
* Compatible with Raspberry Pi5 and Raspberry Pi Compute Module 4 boards with a 22-pin FPC connector and 4-lane MIPI-CSI (same pinout as Raspberry Pi Compute Module 4 IO Board)

## Notes
* The latest v1.6 design requires additional 5V power input to function
* Gerber and CPL file for JLCPCB is under /Gerber
* Bom for interactive bom html [provided by InteractiveHtmlBom
](https://github.com/openscopeproject/InteractiveHtmlBom) and JLCPCB BOM under /bom
* Source Code for CH32V003 based I2C controlled IR Filter Switch and Python code on RPI under /software


## Support
For questions, issues, or suggestions, please open an issue in the [GitHub repository](https://github.com/will127534/StarlightEye/issues)

## Schematic
![](/img/sch.jpg)
