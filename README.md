# Arduino Engine

A simple test for making a basic software engine

## Getting Started

Use the [arduino-cli](https://arduino.github.io/arduino-cli/latest/getting-started/) to
get this project set up.

### Connect arduino

Connect your arduino device to your computer via USB cable and then follow the instructions in the arduino-cli docs linked above:

```bash
# update index, maybe not necessary but good practice
arduino-cli core update-index
# find your board (searches serial ports so you might see other non-arduino things here)
arduino-cli board list
# install the core for your board (arduino:avr in my case)
arduino-cli core install YOUR_BOARDS_CORE_HERE
# verify installation - you should see your board's core here
arduino-cli core list
```

### Compiling the program

