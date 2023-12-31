Adafruit AS7341 Build Status
This is the Adafruit AS7341 11-Channel Spectral Sensor for Arduino

Tested and works great with the Adafruit AS7341 Breakout Board  This chip uses I2C to communicate, 2 pins are required to interface

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Installation
To install, use the Arduino Library Manager and search for "Adafruit AS7341" and install the library.

Dependencies
Adafruit_BusIO
Contributing
Contributions are welcome! Please read our Code of Conduct before contributing to help this project stay welcoming.

Documentation and doxygen
Documentation is produced by doxygen. Contributions should include documentation for any new code added.

Some examples of how to use doxygen can be found in these guide pages:

https://learn.adafruit.com/the-well-automated-arduino-library/doxygen

https://learn.adafruit.com/the-well-automated-arduino-library/doxygen-tips

Formatting and clang-format
This library uses clang-format to standardize the formatting of .cpp and .h files. Contributions should be formatted using clang-format:

The -i flag will make the changes to the file.

clang-format -i *.cpp *.h
If you prefer to make the changes yourself, running clang-format without the -i flag will print out a formatted version of the file. You can save this to a file and diff it against the original to see the changes.

Note that the formatting output by clang-format is what the automated formatting checker will expect. Any diffs from this formatting will result in a failed build until they are addressed. Using the -i flag is highly recommended.

clang-format resources
Binary builds and source available on the LLVM downloads page
Documentation and IDE integration
About this Driver
Written by Bryan Siepert for Adafruit Industries. BSD license, check license.txt for more information All text above must be included in any redistribution