

# Interfacing Wemos S2 Mini with 1.69-inch LCD Module (240 x 280)

This repository provides the necessary code and instructions to interface a Wemos S2 Mini with a 1.69-inch LCD Module. The LCD Module has a resolution of 240 x 280 pixels.

## Hardware Requirements

- Wemos S2 Mini
- 1.69-inch LCD Module (240 x 280)
- Jumper wires
- Breadboard (optional, depending on your setup)

## Software Requirements

- Arduino IDE
- ESP8266 board support for Arduino IDE

## Installation

1. Clone or download this repository.
2. Open the Arduino IDE.
3. Install ESP8266 board support if not already installed. (Go to `File > Preferences`, then add `http://arduino.esp8266.com/stable/package_esp8266com_index.json` to the "Additional Board Manager URLs" field. Then, go to `Tools > Board > Boards Manager`, search for "esp8266", and install it.)
4. Connect your Wemos S2 Mini to your computer via USB.
5. Open the `wemosdisplay.ino` file in Arduino IDE.
6. Select the appropriate board and port from the `Tools` menu.
7. Click on the upload button to upload the code to your Wemos S2 Mini.

## Usage

1. After uploading the code successfully, connect the 1.69-inch LCD Module to your Wemos S2 Mini according to the pin configuration specified in the code.
2. Power on your Wemos S2 Mini.
3. The LCD Module should now display the output as programmed in the code.

## Troubleshooting

- If you encounter any issues, double-check the wiring connections between the Wemos S2 Mini and the LCD Module.
- Ensure that you have selected the correct board and port in the Arduino IDE.
- Check the serial monitor in the Arduino IDE for any error messages.

## Contributing

Contributions are welcome! If you have any improvements or bug fixes, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

