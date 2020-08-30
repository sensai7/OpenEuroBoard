# OpenEuroBoard
Kicad and Gerber (TBD) files for the manufacturing of electronic synthesizers prototyping and developing, focusing on utilities to prototype Eurorack modules. All the sections in the board are independent from each other (except the Gate/CV generators) that need the 5V regulator part, and can be disregarded if they're not needed for the user application.

![Board](https://i.imgur.com/G72g0NL.jpg)

![Board](https://i.imgur.com/hLiPsu5.jpeg)

## Feature List:
 * Size adjusted to fit exactly a standard sized breadboard.
 * SSD1306 driver based Screen interfaces, with sockets for both 128x64px and 128x32px versions.
 * 2x quad op-amps (TL074) for custom use.
 * 5V regulator and power bus.
 * 4x custom push buttons.
 * MIDI IN/OUT interfaces. MIDI IN is isolated through a optocoupler, MIDI OUT is buffered.
 * 8x custom Minijack sockets.
 * 5x pots, 2x custom pots to connect any desired value. The pots can be easily shorted to ground, +12V, or between their own pins using a jumper.
 * 4x custom SPDT switches.
 * 4x custom LEDs.
 * Small jumper storage.
 * A stereo buffered out with a stereo minijack socket.
 * Custom test points and power bus test points.
 * 2x Gate and CV generators, Both signals being 0~5V.
 * 2x oscillators with low (LFO) and high (Audio rate) range switches and frequency pots.
 * Screw mount holes

## Bill Of Materials:
TBD
