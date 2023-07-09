## Description

![alt text](docs/pics/header_image.png "Firmware Toolbox")

Sets of various small helper functions useful when developing firmware.

I have been collecting this functions during years of work. Some of it I wrote  by myself others I found somewhere and added into this repository.
Main goal creation of this repository was to make life firmware engineers little bit easier because each firmware engineer know this pain when you need to write
some helpful function by your own hand because you did not find or can`t add necessary library.

So please feel free to use this toolbox and add code to this toolbox if you want.

## Documentation

All documentation generated by [Doxygen](https://github.com/doxygen/doxygen) you can find in [docs](https://github.com/Zamuhrishka/FWToolbox/tree/develop/docs) folder.

## Repository structure

Structure of repository:

- [align](https://github.com/Zamuhrishka/FWToolbox/tree/develop/src/align) - functions and macros which used for data align.
- [conversion](https://github.com/Zamuhrishka/FWToolbox/tree/develop/src/conversion) - functions which used for conversion different data type to each other.
- [crc](https://github.com/Zamuhrishka/FWToolbox/tree/develop/src/crc) - functions for calculate CRC.
- [delay](https://github.com/Zamuhrishka/FWToolbox/tree/develop/src/delay) - functions for time delays.
- [endian](https://github.com/Zamuhrishka/FWToolbox/tree/develop/src/endian) - functions which use for work with different byte endian order.
- [environment](https://github.com/Zamuhrishka/FWToolbox/tree/develop/src/environment)
  - [compiler.h](https://github.com/Zamuhrishka/FWToolbox/blob/develop/src/environment/compiler.h) - compiler abstraction layer.
  - [constants.h](https://github.com/Zamuhrishka/FWToolbox/blob/develop/src/environment/constants.h) - common constants.
  - [host.h](https://github.com/Zamuhrishka/FWToolbox/blob/develop/src/environment/host.h) - host specific function and macros.
- [macros](https://github.com/Zamuhrishka/FWToolbox/tree/develop/src/macros)
  - [arithmetics.h](https://github.com/Zamuhrishka/FWToolbox/tree/develop/src/macros/arithmetics.h) - macros for arithmetics operations.
  - [bits.h](https://github.com/Zamuhrishka/FWToolbox/tree/develop/src/macros/bits.h) - bits operation macros.
  - [guards.h](https://github.com/Zamuhrishka/FWToolbox/tree/develop/src/macros/guards.h) - guards macros.
  - [misc.h](https://github.com/Zamuhrishka/FWToolbox/tree/develop/src/macros/misc.h) - various useful macros.
- [types](https://github.com/Zamuhrishka/FWToolbox/tree/develop/src/types) - specific and useful types and functions for work with it.
- [random](https://habr.com/ru/articles/121849/) - under construction.

## Installation

For installation you need to do 2 simply steps:

- Copy necessary ``c`` and ``h`` to your project
- Add ``#include "xxx.h"`` into your source code.

## Unit tests

All unit tests in this project was write by using this [framework](https://github.com/ThrowTheSwitch/Ceedling).
So for run unit tests you need to install this framework using instruction from framework [repository](https://github.com/ThrowTheSwitch/Ceedling).

## Contributing

Bug reports and/or pull requests are welcome.

## Disclaimer

This software is provided 'as-is', without any express or implied warranty. In no event will the authors be held liable for any damages arising from the use of this software.

## License

Permission is granted to anyone to use this software for any purpose, including commercial applications.
