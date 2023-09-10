## F1rmw4r3.bin - [EMBEDDED]

1. First connected the given Arduino Board with PC.

2. Searched how to extract Firmware from an Arduino Board.

3. Opened Linux terminal in the PC.

4. Executed "sudo avrdude -p m328p -c arduino -P /dev/ttyUSB0 -b 115200 -U flash:r:firmware.hex:i" to extract the Firmware.

5. Coverted the .hex file to .bin file .

6. Opened the .bin file in strings and used grep function to get the flag.

Flag - wired{...}
