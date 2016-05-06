PiMiner
=======

Software Image Source for [Resin.io](http://resin.io) to deploy to a variable cluster of Raspberry Pi nodes with ASIC bitcoin miners attached.

Each node will have a dashbaord containing 



Development
-----------
Python
- Flask


Original Project tutorial: http://learn.adafruit.com/piminer-raspberry-pi-bitcoin-miner


Contributors
-------------
Original codebase written by Collin Cunningham for Adafruit Industries. BSD license, all text above must be included in any redistribution.


Changes
-------------
Version 1.2.0 (forked by DavidAwad)
- starting a dashboard for node stats

Version 1.1.1 (forked by denmojo)
- Added support for bitstamp exchange rates (less price deviation than mt.gox) in screen selection 3.
- Retained compatibility with mtgox.

Version 1.1
- Added mining auto-start after boot (see tutorial)
- Time format changed to dd:hh:mm
- Abbreviated large share count; ex. "1k2"
- Revised error % calculation: 100 * HW / (diff1shares + HW)
- Added MtGox last, high, & low price ("currency" var can be set in script)
- Misc. tutorial revisions

Version 1.0
- Initial release
