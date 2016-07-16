Hermit Board
============

This is an isolator board meant for use with Atlas Scientific OEM boards.

* IMPORTANT NOTE: will unlikely work for the electroconductivity sensor due to
  the requirement the isolated ground plane to run under at least half of the
  sensor IC.

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

* IMPORTANT NOTE: Do not populate the pullups R2 and R5 since INT is actually driven
* Corrected footprint for Atlas part
