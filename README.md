
## Open, low-cost experimentation board for the LTC3331 energy harvesting chip
	
This project contains design- and production-files for a
low-cost LTC3331 energy harvesting development-, breakout- and test-board.

It's specifically designed to be inexpensive, yet open and comprehensive:
* Full design files for KiCad EDA
* 10cm x 10cm PCB with 2 layers
* Full pin breakout
* Less-comprehensive headers for pins usually required
* LIR2032 holder and alternative battery port
* All default options can be jumpered on or off
* Supercap pads provided

![PCB v0.1 rendering from KiCad](https://github.com/dpiegdon/ltc3331-breakout/blob/master/production/ltc3331-breakout-v0.1.jpg?raw=true)

(Above: v0.1, image rendered by KiCad EDA)

![PCB v0.1 photo](https://github.com/dpiegdon/ltc3331-breakout/blob/master/production/ltc3331-breakout-v0.1.photo.jpg?raw=true)

(Above: v0.1, actual photo of both sides)



## Releases and History

All production files for releases can be found in the
production/ directory. All required production files for
PCB production should be zipped in a way that allows immediate upload
to your preferred online PCB manufacturer.

v0.1 is the first version of the PCB. It has a few minor issues
(see Errata), but is fine for testing.


## Errata

### v0.1

v0.1 works fine, but there are a few issues that should be
addressed for another release:

* footprints for 22uF inductors on bottom layer are way too large.
  a Taiyo-Yuden NR-30xx handsoldering footprint would be fine and should
  be moved to the front side. then there would be no components on the bottom.

* jumper for BBIN-BATIN connection probably is not needed.
  TBD: verify from datasheet and then remove.

* replace all capacitance footprints >= 10uF with larger
  footprint for e.g. tantalum capacitor.

* pdf schematic was missing in release files (was added later).
  next release should contain that immediately.



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



