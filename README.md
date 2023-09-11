# OpenEuroBoard
Kicad and Gerber files for the manufacturing of electronic synthesizers prototyping and developing, focusing on utilities to prototype Eurorack modules. All the sections in the board are independent from each other (except the Gate/CV generators) that need the 5V regulator part, and can be disregarded if they're not needed for the user application.

![Board](https://i.imgur.com/00jSJdN.png)

![Board](https://i.imgur.com/hLiPsu5.jpeg)
(This is from an older version but the features are the same)

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
|Section          |Type             |Model                   |Amount|
|-----------------|-----------------|------------------------|------|
|General          |Male Header      |2x5 dupont header       |2     |
|                 |Female Header    |1x40 dupont header      |2     |
|                 |Voltage regulator|LM1117-5                |1     |
|                 |LED              |3mm Red LED             |1     |
|                 |Resistor         |2.2k                    |1     |
|                 |Capacitor        |100n                    |2     |
|                 |Elec. Capacitor  |10u                     |4     |
|Screen interfaces|Screen           |SSD1306                 |1     |
|quad op-amps     |Op. amp          |TL074                   |2     |
|                 |Capacitor        |100n                    |4     |
|Push buttons     |Push button      |6mm push                |4     |
|MIDI IN-OUT      |Din-5 Connector  |Din-5 Connector         |2     |
|                 |Optocoupler      |6n139                   |1     |
|                 |Dual inverter    |CD40107BE               |1     |
|                 |Diode            |1n4148                  |1     |
|                 |Resistor         |220                     |3     |
|                 |Resistor         |270                     |1     |
|                 |Resistor         |120                     |2     |
|Minijack sockets |Minijack         |Thonkiconn jack         |8     |
|Potentiometer    |Potentiometer    |Alps vertical pot       |5     |
|Switches         |SPDT             |8.5mm SPDT              |4     |
|LEDS             |LED              |3mm Red LED             |4     |
|                 |Resistor         |1k                      |4     |
|Jumper storage   |Jumper           |2.54mm jumper           |5     |
|Stereo out       |Op. amp          |TL072                   |1     |
|                 |Capacitor        |100n                    |2     |
|                 |Minijack         |Vertical stereo jack    |1     |
|Gate generators  |Push button      |6mm push                |2     |
|                 |Resistor         |4.7k                    |2     |
|CV Generators    |Potentiometer    |Alps vertical pot 100k  |2     |
|Oscillators      |Op. amp          |Tl074                   |1     |
|                 |Capacitor        |100n                    |4     |
|                 |Potentiometer    |Alps vertical pot 1M LOG|2     |
|                 |SPDT             |8.5mm SPDT              |2     |
|                 |Capacitor        |1u                      |2     |
|                 |Capacitor        |22n                     |2     |
|                 |Resistor         |1k                      |4     |
|                 |Resistor         |10k                     |4     |
|                 |Resistor         |100k                    |2     |

## Changelog

V1.0 First version
V1.1 Addressed the issues from [Issue 1](https://github.com/sensai7/OpenEuroBoard/issues/1). Updated Silkscreen