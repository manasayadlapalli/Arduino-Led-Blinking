# Arduino-Led-Blinking
This is a simple Arduino project that demonstrates how to control two LEDs to blink alternately using an Arduino board. This project is suitable for beginners who are getting started with Arduino programming.

## Components Needed
Arduino board (e.g., Arduino Uno)
2 LEDs (different colors)
2 x 220-ohm resistors
Breadboard and jumper wires

## Circuit Diagram
      LED1         LED2
       |            |
D13 --|>|-- RES --|>|-- RES -- GND

<br/>
Connect the anode (longer lead) of each LED to a digital pin (D13 for LED1 and D12 for LED2) through a 220-ohm resistor. Connect the cathode (shorter lead) of each LED to the ground (GND) pin on the Arduino.

## Installation
Arduino IDE: If you don't have the Arduino IDE installed, download and install it from the Arduino website.

Clone Repository: Clone this repository to your local machine using Git or download the ZIP file and extract it.

Open Sketch: Open the Arduino IDE and navigate to File > Open. Browse to the location where you cloned/extracted the repository and select the arduino_2_led_blink.ino file.

Select Board: Go to Tools > Board and select your Arduino board (e.g., Arduino/Genuino Uno).

Select Port: Go to Tools > Port and select the appropriate port to which your Arduino board is connected.

Upload Sketch: Click the upload button (right-pointing arrow) to compile and upload the sketch to your Arduino board.

## Usage
After successfully uploading the sketch, the two LEDs should start blinking alternately with a certain delay. You can adjust the blinking rate by modifying the delay values in the sketch.

## Modification
Feel free to modify the code to experiment with different blinking patterns, add more LEDs, or adjust the timing. The provided code is a basic starting point for understanding how to control digital pins on an Arduino board.
