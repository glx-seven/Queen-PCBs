# Queen-PCBs
These are some Blinky-LED pendants I made a while ago. 

The main components are:
* BQ25570 energy harvesting controller
* KXOB25-05X3F mini solar cell
* MAL219691153E3 4F super-cap (probably has to be replaced with something else due to availability)
* PIC16LF18346-E/GZ (QFN20) MCU (if you're using 1.8V turn off the brown-out detection to make it run properly)

The programming pins match the PICKIT debugger, so you can stick some pogo-pins in the connector and hold it onto the pins to flash th firmware.
I did also upload the MPLAB-X project files for the firmware, it's not very good or complex tho, it just blinks some LEDs. 
