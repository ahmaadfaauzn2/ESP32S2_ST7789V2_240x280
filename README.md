# Interfacing Wemos S2 Mini with 1.69-inch LCD Module (240 x 280)

This repository provides the necessary code and instructions to interface a Wemos S2 Mini with a 1.69-inch LCD Module. The LCD Module has a resolution of 240 x 280 pixels.

## Hardware Requirements

- Wemos S2 Mini ESP32-S2FN4R2 4MB FLASH WIFI Board ESP32-S2 MicroPython
- 1.69-inch LCD Module (240 x 280) ([Product Link](https://www.waveshare.com/wiki/1.69inch_LCD_Module))
- Jumper wires
- Breadboard (optional, depending on your setup)

## Software Requirements

- PlatformIO IDE
- ESP8266 board support for PlatformIO
- [TFT_eSPI library](https://github.com/Bodmer/TFT_eSPI.git?utm_source=platformio&utm_medium=piohome)


## SPI Pinout

- TFT_MOSI: GPIO 35 (aka SDA)
- TFT_SCLK: GPIO 36 (aka SCL)
- TFT_CS: GPIO 34 (Chip select control pin)
- TFT_DC: GPIO 17 (Data Command control pin)
- TFT_RST: GPIO 15 (Reset pin, could connect to Arduino RESET pin)
- TFT_MISO: GPIO 1 ("For some reason DMA requires that a MISO pin is defined" - [Discussion](https://github.com/Bodmer/TFT_eSPI/discussions/2233)

## Installation

1. Clone or download this repository.
2. Open the project folder in PlatformIO IDE.
3. Ensure that ESP8266 board support is installed. (If not, you can install it via PlatformIO IDE.)
4. Connect your Wemos S2 Mini to your computer via USB.
5. Compile and upload the code to your Wemos S2 Mini.

## Usage

1. After uploading the code successfully, connect the 1.69-inch LCD Module to your Wemos S2 Mini according to the pin configuration specified in the code.
2. Power on your Wemos S2 Mini.
3. The LCD Module should now display the output as programmed in the code.

## Troubleshooting

- If you encounter any issues, double-check the wiring connections between the Wemos S2 Mini and the LCD Module.
- Ensure that you have selected the correct board and port in the PlatformIO IDE.
- Check the serial monitor in the PlatformIO IDE for any error messages.

## Issue 
## Pixel not fit and rendered to the screen
![Wemos S2 Mini with 1.69-inch LCD Module](https://i.imgur.com/HU0WPhU.jpeg)



## Contributing

Contributions are welcome! If you have any improvements or bug fixes, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
