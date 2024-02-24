# reader00
<a href="https://raja.rocks/projects/E120P1010A00.html"><img alt="Static Badge" src="https://img.shields.io/badge/raja.rocks-E120P1010A00-lightgray?style=flat-square"></a>

The objective of reader00 is to read the memory off of a flash memory IC found
inside of consumer electronics. It is unknown if the memory on the chip is 1.
recoverable or 2. publishable.

## Chip details

The IC in question is an MX29GL128FHT2I-90G loaded with unknown data, presumably
audio files. It uses a 18.4mm x 14mm 56-pin TSOP casing.

To read the data off of the chip, I use an Arduino Nano socket on a
custom-designed PCB board. Onto this PCB board, I sotter the flash memory onto
before putting a programmed Arduino to read off of the flash memory.
