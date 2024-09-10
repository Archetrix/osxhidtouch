osxhidtouch
===========

(forked from dcomputare who forked from daniel5151, forked from kyewei, who forked from astarasikov) 

User-space HID multitouch touchscreen driver for Mac OS X

Adapted to fit the Iiyama TW2424AS

Multifinger tracking was in the code, but doesn't work properly.
In fact i had to strip it down even more because the HID data from my touch device did not match expectations in code.
Integer overflows occurred crashing the driver.
