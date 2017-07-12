# UART Serial Mezzanine
This adapter is a USB to UART interface to be used with any base board compatible with the 96Boards Consumer Edition or Enterprise Edition specifications.

It makes it easy to connect your PC to the serial console on the 96Boards low-speed expansion connector, without worrying about pinout or level shifting for 1.8V IO. It also provides remote control of the power button and reset signals so that the base board can be completely controlled over a single USB cable.

Since it uses the FT230X chip from FTDI, when it is connected to your PC over USB, it appears as a normal UART interface on a PC, Macintosh or Linux computer with an FTDI UART driver installed.

## Features
- 2 x 20 2.0mm pitch male header that attaches to 96Boards low-speed (LS) expansion connector
- FT230X USB to UART adapter chip	 
- USB bus powered. Doesn’t disconnect when base board power is cycled	 
- Switchable between LS UART0 and UART1. (UART1 is the default console)	 
- CTS/RTS with using UART0	 
- TX and RX LEDs	 
- Remote control of baseboard reset and power signals	 
- Base board reset button	 	 
- User LED connected to GPIOB (GPIOA on v1.0 of the adapter)

## Buy Now
[SeeedStudio](http://linaro.co/uart-seeed)