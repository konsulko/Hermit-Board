Hermit Board
============

This is an isolator board meant for use with Atlas Scientific OEM boards.

Pin mapping:

+ Pin 1 - 5V
+ Pin 2 - 5V
+ Pin 3 - VCC to buffer (NC on Rev A3)
+ Pin 4 - SDA
+ Pin 5 - INT
+ Pin 6 - SCL
+ Pin 7 - NC
+ Pin 8 - GND
+ Pin 9 - GND
+ Pin 10 - GND

Changes from v3 to v4
=====================

* Change buffer host side power supply from +5V rail to VCC
* Add VCC power plane
* Add pullup resistors to host side

Changes from v4 to v5
=====================

* Move host pullups to top side
* Add M2 screwholes
* Slightly cleanups to part placement
* Increase drill hole size for BNC connector

Changes from v5 to v6
=====================

* Corrected footprint for Atlas part
