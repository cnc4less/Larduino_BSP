# Arduino Hardware Support Package for LGT8F's 

### Summary
Larduino_HSP is a 3rd party hardware support package for the LGT8F core based arduino boards. The backend of the **HSP** is fork from offical arduino distribution. We have try to keep all the standard features compatible with arduino world. So feel free to resuse all of the libraries which designed for arduino platform.

Microcontroller is based on the LGT8F series, e.g LGT8F328P, and has more advanced features which not covered in standard Atmel/Microchip ATmega328 implementation. So there are also many new features merged to this 3rd party package. Important update and new features as following:

* External/Internal crystal can be selected at runtime
* ~~Fast_IO interface for fast I/O speed and small code size~~ Not in 3.6c release
* ~~Full configurable PWM features, including complementary and dead-band control~~ Not in 3.6c release
* Differential Amplifier front-end for 12bit Analog-to-Digital converter
* 1/2 channel 8bit Digtial-to-Analog output, campatible with `analogWrite()`
* More standalone I/Os

> More detail is available on the Wiki page...

### Bootloader 
The Larduino HSP bootloader is based on optiboot. Source can be found inside the [bootloader directory](https://github.com/LGTMCU/Larduino_HSP/tree/master/hardware/LGT/avr/bootloaders/lgt8fx8p)

* *Bootloader upload baudrate: 57600bps*
	
### Installation:
1. Unzip [master.zip](https://github.com/LGTMCU/Larduino_HSP/archive/master.zip)
1. Copy the [**hardware**] directory to Arduino's sketchbook directory (see below to find out where it normally resides)
1. Restart Arduino, you will see new board from [**Tools**]->[**Board**] menu.

### About arduino's sketchbook directory

You can always find this directory via the **[File]->[Preferences]** dialog. But here is the default sketchbook directory for most popluar system:

| System | Path of sketchbook |
| :----- | :----------------- |
| Windows | C:\Users\\<Username\>\Documents\Arduino |
| Mac OSX | /Users/user/Documents/Arduino |
| LINUX | /home/<Username\>/sketchbook |

### Arduino Board based on LGT8F's
Here we list one remarkable arduino board based on the LGT8F, which is designed by **[OCROBOT](http://www.ocrobot.com/doku.php?id=start)**, the [ALPHA 8F382P-U](http://www.ocrobot.com/doku.php?id=ocrobot:alpha:8f328p-u:main) stick with USB to UART on-board. Very affordable, for a low cost of just **RMB 8.00**!

![](http://www.ocrobot.com/lib/exe/fetch.php?w=400&tok=f15324&media=ocrobot:alpha:8f328p-u:328p-u%E4%BE%A7%E9%9D%A2435.png)

Please follow **[OCROBOT ALPHA 8F832P-U](http://www.ocrobot.com/doku.php?id=ocrobot:alpha:8f328p-u:main)** official page for more details.
