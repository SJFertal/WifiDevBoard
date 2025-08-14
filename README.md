# WifiDevBoard
STM32 based development board with 2.4Ghz communication capabilities

This board serves as my first experience with RF PCB design.
This PCB has features such as:
  -Linear power regulation for low noise power supply
  -Proper impedance traces for RF and diff pair signal integrity
  -4 layers for consistent power plane coupling on signal layers
  -ESD protection for input signals
  -Proper antenna isolation
  -Signal layer ground pour and high stitching via count to reduce etching and improve coupling
  -Multiple GPIOs for application breadth
MCU: STM32G47CB
Transciever: NRF24L01P
Regulator: LD1117
