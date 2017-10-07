# Larduino_HSP
#
//==============================================================

Ardunio 3rd-party hardware package for LGT8F
Installation Guide

//==============================================================

= Features
------------------------------------------------
	- Support arduino 1.0.x/1.5.x/1.6.x
	- Support bootloader by optiboot
	- Bootloader baudrate: 57600bps
	- Support board: Larduino & LGT8F88A MiniDev
	- Support board: Larduino w/ LGT8FX8D and LGT8FX8P

= Package contents
------------------------------------------------
	Larduino_HSP_v3.6 : package root directory
	|
	+ hardware : 3rd party hardware support package
	|    |
	|    + LGT : package for support arduino 1.5.x/1.6.x
	|    |
	|    + LGT8F : package for support arduino 1.0.x
	|
	+ libraries : 3rd party hardware library

= Installation:
-----------------------------------------------
	- Unzip Larduino_HSP_v3.6.rar
	- Copy [sketches], [hardware] and [libraries] directories to arduino's sketchbook direcotry
	- Restart Arduino, you will see new board from [Tools]->[Border] menu.

= About arduino's sketchbook directory:
-----------------------------------------------
	You can always find this directory from [File]->[Preferences] menu.
	Here is the default sketchbook directory for most popluar system:
	- Windows: C:\Users\<Username>\Documents\Arduino
	- Mac OSX: /Users/user/Documents/Arduino
	- LINUX: /home/<Username>/sketchbook

