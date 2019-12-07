# LoconetLayoutControlPanel
## License: MIT License

A standalone controller which will generate LocoNet commands when a button is pressed to:
  * Turn track power on and off, with a LED to indicate state.
  * Generate a master E-Stop, with a LED to indicate state.
  * Clear all slots in a command station

Hardware needed:
  * RX and TX Loconet Hardcoded to use ICP pin 8 (port PINB bit PB0) for LocoNet input and a user define'd pin for output/transmit
  * 3 pushbuttons and associated LEDs plus a Loconet Shield
