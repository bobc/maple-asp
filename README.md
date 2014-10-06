Arduino Support Package For Maple
=================================

Background
----------

Maple is a series of Arduino like boards created by LeafLabs (http://www.leaflabs.com/).
LeafLabs provided a version of the Arduino IDE tailored for Maple https://github.com/leaflabs/maple-ide
but it is no longer supported, and uses an old version of the Arduino IDE.

maple-asp provides support for Maple compatible boards for use with the "new" Arduino IDE 1.5.x, without requiring
any modifications to the Arduino IDE. 
The bulk of maple-asp is the libmaple code https://github.com/leaflabs/libmaple, in the form of an Arduino add on package.    

maple-asp
---------

Currently the following boards are supported:

- Maple Rev 3+


Installing
----------

Pre-requisites:

- Arduino IDE version 1.5.7 or later

Installation procedure:

1. Copy the Arduino/hardware/ folder to your sketchbook folder (e.g. ~/Arduino)
2. Restart Arduino IDE

Note: maple-asp is designed to be installed into your sketchbook, not the Arduino program folder, otherwise
it will not work properly.

TODO
----

- Implement all the board/memory variants
- create wrapper utility for DFU download
- support for linux
- build and test examples 

Licenses
--------

maple-asp is an Open Source project.

libmaple is mostly licensed with MIT license. 

Other files are licensed as GPL or BSD.

Please see individual files for Copyright notices.

Main Contributors
-----------------

- LeafLabs (maple-ide, libmaple)
- Bob Cousins
