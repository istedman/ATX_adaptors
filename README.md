# ATX_adaptors
ATX power adaptors for the Amiga and other retro computers. Allows easy access to an ATX replacement supply. The +5V, +12V and -12C supplies are available on screw terminal connectors for easy retro fit. The Multi-purpose design can also supply -5V, the 50/60Hz tick signal and a Power_good signal.

The schematics and PCB files are included here in Eagle CAD format, V7 or later is required to open the files.

The adaptors use a Microchip PIC10F200 microcontroller to debounce the switch and to turn on/off the power. The same micro is used to provide a 50/60Hz 'tick' signal. Accuracy was ~0.5Hz using internal oscillator. A Tag-connect MCP2030 is required to program the device. The ATX_PICV1.zip file has the software. MplabX and XC8 compiler required to rebuild. A hex file is within the archive.

#2021 Update

I'm discontinuing sales of all Amiga related projects. Reduced order volumes and extra issues with order post Brexit have not made it viable to continue.
All information, including BOMs, Gerbers and notes are now in the repository, if you want to build your own.
