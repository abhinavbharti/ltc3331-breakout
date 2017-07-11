
## Open, low-cost experimentation board for the LTC3331 power harvesting chip
	
This project contains design- and production-files for a
low-cost LTC3331 power harvesting development-, breakout- and test-board.

It's specifically designed to be inexpensive, yet open and comprehensive:
* Full design files for KiCad EDA
* 10cm x 10cm PCB with 2 layers
* Full pin breakout
* Less-comprehensive headers for pins usually required
* LIR2032 holder and alternative battery port
* All default options can be jumpered on or off
* Supercap pads provided

![PCB rendering from KiCad](https://github.com/dpiegdon/ltc3331-breakout/blob/master/production/ltc3331-breakout-v0.1.jpg?raw=true)

(Image rendered by KiCad EDA)



## Releases and History

All production files for releases can be found in the
production/ directory. All required production files for
PCB production should be zipped in a way that allows immediate upload
to your preferred online PCB manufacturer.

v0.1 is the FIRST version of the PCB that is on its way to me.
Thus, design verification is pending.
It should NOT be considered production-ready for now.



## Prior Art and Alternatives

Please note: personally I did not obtain any of the following
alternatives, so any comparison is a rough guess.

DC2151A is the de-facto standard demo- and dev-board that
Linear Technology created for this chip.
However, it's really expensive. (200+ €/$)

The "LTC3331 Energy Harvester, DC Converter and Charger"
by Blue Spark Labs is a much cheaper alternative to the
official dev-board.
But it seemingly does not offer comprehensive access to all pins
and full breakout options. Also, worldwide shipping can be
quite expensive, it seems.



## Use

When you want to use or modify the design in KiCad, you should get used
to handling git-submodules. I keep my custom footprints and symbols in
a separate repository so I can re-use them.

Have fun!



## Feedback

If you have design improvements, find it useful or stupid, or
want to let me know anything else, just let me know ;).



## License, copyright

The design is released under the OSHW 1.0 license as defined
by [https://www.oshwa.org/definition/].



