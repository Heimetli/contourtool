Experimental tool to dump data from a Bayer Contour Next USB meter
==================================================================

Introduction
------------

This is a fork of https://github.com/bnjones/contourtool.

Read the full description there.

The tool communicates with a Bayer Contour Next USB blood glucose
meter. It dumps data stored on the device to a CSV file.

Important safety information
----------------------------

**This program is experimental software, not developed or supported by
Bayer. It might damage your meter or render it unreliable. Use this
software at your own risk. You have been warned!**

Ported to Python 3
------------------

This version was tested with python 3.7 on a Debian linux, with a
Contour Next connected via USB.

Only the contourtool.sh was used in the tests, neither setup.py
nor the udev rules were checked.

The error ``Expected to see '\x05'`` still occurs.
