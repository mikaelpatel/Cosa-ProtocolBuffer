# Cosa-ProtocolBuffer

This Cosa library is an implementation of the Google Protocol Buffers
data streaming protocol. It is adapted for AVR/8-bit processors to
allow simple data exchange with hosts. Implements encoding and
decoding of signed/unsigned integers and floating point up to
32-bits. 64-bit integers and double are not supported. Support length
delimited blocks from both SRAM and PROGMEM.

# Install

To use this library you must download and install the [Arduino IDE] (http://www.arduino.cc/en/Main/Software) (or
GCC AVR toolchain) and [Cosa] (https://github.com/mikaelpatel/Cosa).

Download and unzip the Cosa-ProtocolBuffer library into your sketchbook
libraries directory. Rename from Cosa-ProtocolBuffer-master to
ProtocolBuffer.

The ProtocolBuffer library and examples should be found in the Arduino IDE
File>Sketchbook menu. Open the CosaProtocolBuffer example sketch. Select
the Cosa core by selecting one of the Cosa boards in the Tools>Board
menu.

# References

1. Google Protocol Buffers, https://developers.google.com/protocol-buffers/.

