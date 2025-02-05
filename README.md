# Marlin 3D Printer Firmware
<<<<<<< HEAD
<img align="top" width=175 src="Documentation/Logo/Marlin%20Logo%20GitHub.png" />
 Additional documentation can be found in [The Marlin Wiki](https://github.com/MarlinFirmware/Marlin/wiki).

## Release Candidate -- Marlin 1.1.0-RC6 - 24 April 2016

__Not for production use – use with caution!__

You can download earlier versions of Marlin on the [Releases page](https://github.com/MarlinFirmware/Marlin/releases). (The latest "stable" release of Marlin is 1.0.2-1.)

You'll always find the latest Release Candidate in the ["RC" branch](https://github.com/MarlinFirmware/Marlin/tree/RC). Bugs that we find in the current Release Candidate are patched in the ["RCBugFix" branch](https://github.com/MarlinFirmware/Marlin/tree/RC), so during beta testing this is where you can always find the latest code on its way towards release.

Future development (Marlin 1.2 and beyond) takes place in the [MarlinDev repository](https://github.com/MarlinFirmware/MarlinDev/).

## Recent Changes
- RCBugFix
  - Throw error if compiling with older versions (<1.60) of Arduino due to serious problems with outdated Arduino versions
  - Please upgrade your IDE at least to Arduino 1.6.0. Thanks.

- RC6 - 23 Apr 2016
  - Completed support for CoreXY / CoreXZ in planner
  - Changes to positioning behavior
  - Various issues fixed. More details pending.

- RC5 - 01 Apr 2016
  - Warn if compiling with older versions (<1.50) of Arduino
  - Fix various LCD menu issues
  - Add formal support for MKSv1.3 and Sainsmart (RAMPS variants)
  - Fix bugs in M104, M109, and M190
  - Fix broken M404 command
  - Fix issues with M23 and "Start SD Print"
  - More output for M111
  - Rename FILAMENT_SENSOR to FILAMENT_WIDTH_SENSOR
  - Fix SD card bugs
  - and a lot more
  - see https://github.com/MarlinFirmware/Marlin/releases/tag/1.1.0-RC5 for details

- RC4 - 24 Mar 2016
  - Many lingering bugs and nagging issues addressed
  - Improvements to LCD menus, CoreXY/CoreXZ, Delta, Bed Leveling, and more…

- RC3 - 01 Dec 2015
  - A number of language sensitive strings have been revised
  - Formatting of the LCD display has been improved to handle negative coordinates better
  - Various compiler-related issues have been corrected

- RC2 - 29 Sep 2015
  - File styling reverted
  - LCD update frequency reduced

- RC1 - 19 Sep 2015
  - Published for testing

## Submitting Patches
Proposed patches should be submitted as a Pull Request against the [RCBugFix](https://github.com/MarlinFirmware/Marlin/tree/RCBugFix) branch.

- Don't submit new feature proposals. The RCBugFix branch is for fixing bugs in existing features.
- Do submit questions and concerns. The "naive" question is often the one we forget to ask.
- Follow the proper coding style. Pull requests with styling errors will be delayed. See our [Coding Standards](https://github.com/MarlinFirmware/Marlin/wiki/DNE-Coding-Standards) page for more information.

## Current Status: Testing

Please test this firmware and inform us if it misbehaves in any way. Volunteers are standing by!

[![Coverity Scan Build Status](https://scan.coverity.com/projects/2224/badge.svg)](https://scan.coverity.com/projects/2224)
[![Travis Build Status](https://travis-ci.org/MarlinFirmware/MarlinDev.svg)](https://travis-ci.org/MarlinFirmware/MarlinDev)

##### [RepRap.org Wiki Page](http://reprap.org/wiki/Marlin)

## Credits

The current Marlin dev team consists of:

 - Scott Lahteine [@thinkyhead] - English
 - [@Wurstnase] - Deutsch, English
 - F. Malpartida [@fmalpartida] - English, Spanish
 - Jochen Groppe [@CONSULitAS] - Deutsch, English
 - [@maverikou]
 - Chris Palmer [@nophead]
 - [@paclema]
 - Edward Patel [@epatel] - Swedish, English
 - Erik van der Zalm [@ErikZalm]
 - David Braam [@daid]
 - Bernhard Kubicek [@bkubicek]
=======
<img align="right" src="Documentation/Logo/Marlin%20Logo%20GitHub.png" />

 Additional documentation can be found in [our wiki](https://github.com/MarlinFirmware/Marlin/wiki/Main-Page).

## Release Branch

The Release branch contains the latest tagged version of Marlin (currently 1.0.2-1 – January 2015). It also includes a version 1.0.1 (December 2014). Any version of Marlin before 1.0.1 (when we started tagging versions) can be collectively referred to as Marlin 1.0.0.

## Patches - 1.0.x Branch

Any patches developed for this family of releases will be found on the [1.0.x branch](https://github.com/MarlinFirmware/Marlin/tree/1.0.x) of this repository.

## This Repository is Not For Feature Development

Development of future versions of Marlin is ongoing. However, to keep issues separate, that effort takes place in a companion [Development Repository](https://github.com/MarlinFirmware/MarlinDev/). Please make all suggestions for future features in that project. Issues raised here should be restricted to errors in the tagged releases.

## Current Status: In Development

Marlin development is being accelerated to catch up with a long list of issues. Check the Issues and Pull Requests links on the right to to see what we are currently working on.

[![Coverity Scan Build Status](https://scan.coverity.com/projects/2224/badge.svg)](https://scan.coverity.com/projects/2224)
[![Travis Build Status](https://travis-ci.org/MarlinFirmware/Marlin.svg)](https://travis-ci.org/MarlinFirmware/Marlin)

##### [RepRap.org Wiki Page](http://reprap.org/wiki/Marlin)

## Contact

__Google Hangout:__ <a href="https://plus.google.com/hangouts/_/gxn3wrea5gdhoo223yimsiforia" target="_blank">. Hangout</a> We have a hangout every 2 weeks. Search the issue list for "Hangout" to determine the time and date of the next event.

## Credits

The current Marlin dev team consists of:

 - Scott Lahteine [@thinkyhead] - English
 - Andreas Hardtung [@AnHardt] - Deutsch, English
 - [@Wurstnase] - Deutsch, English
 - [@fmalpartida] - English, Spanish
 - [@CONSULitAS] - Deutsch, English
 - [@maverikou]
 - Chris Palmer [@nophead]
 - [@paclema]
 - [@epatel]
 - Erik van der Zalm [@ErikZalm]
 - David Braam [@daid]
 - Bernhard Kubicek [@bkubicek]
 - Richard Wackerbarth [@Wackerbarth] - English
>>>>>>> origin/1.0.x
 - Roxanne Neufeld [@Roxy-3DPrintBoard] - English

More features have been added by:
  - Alberto Cotronei [@MagoKimbra]
  - Lampmaker,
  - Bradley Feldman,
  - and others...

## License

<<<<<<< HEAD
Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ErikZalm&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)
=======
Marlin is published under the [GPL license](/COPYING.md) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ErikZalm&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)
>>>>>>> origin/1.0.x
