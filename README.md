# dihool

dihool.com electric linear actuators service menu description

Enter service menu:
a) press S+A for ~3 seconds after that you'll get "---" on the screen
b) press 1+2+3 at the same time
c) use A/V to slide the options
D) S to set setting and S+V to store setting in the eeprom

Description for 2 actuators and 4 actuators setup:

name DEFAULT2 DEFAULT4 DESCRIPTION
00   176      200      speed
01   24       25       ?
02   1        1        ?
03   0.7      0.5      ? (changes when switch between cm/in)
04   65       22.7     span (changes when switch between cm/in)
05   60       37       min height (changes when switch between cm/in)
06   5.0      2.7      ? (changes when switch between cm/in)
07   4        4        ?
08   224      230      voltage threshold? (incorrect setting forces controller to stop operation)
09   128      76       ?
10   2        4        number of actuators (can be only decreased)

On the board you can find EEPROM 24C02. To set default just set it to 0xFF.

Manual:

## Timer menu
press 1+S and set desired time

## Lock/Unlock
press 2+S and wait to lock/unlock
