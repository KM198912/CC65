The cc65 cross-compiler suite
=============================

This is a Copy of my version of the CC65 toolset to work specifically with my emulator, it has opcodes, not originally supported by any 6502 based system,
this includes support for 9 general purpose registers, opcodes to directly manipulate video memory, based on sync signal given by the cpu, and more to come,
i dont care much about breaking compability with other targets,
so i highly discourage the use of this on other targets, if you do, i dont take the blame if things break, but i dont claim to have made this, 
the list of people, as taken from the CC65 repository and unmodified is below

## People

cc65 is originally based on the "Small C" compiler by Ron Cain and
enhanced by James E. Hendrix.

### Project founders

* John R. Dunning: [original implementation](https://public.websites.umich.edu/~archive/atari/8bit/Languages/Cc65/)
  of the C compiler and runtime library, Atari hosted.
* Ullrich von Bassewitz:
  * moved Dunning's code to modern systems,
  * rewrote most parts of the compiler,
  * rewrote all of the runtime library.

### Core team members

* [Christian Groessler](https://github.com/groessler): Atari, Atari5200, and CreatiVision library Maintainer
* [dqh](https://github.com/dqh-au): GHA help
* [Greg King](https://github.com/greg-king5): all around hackery
* [groepaz](https://github.com/mrdudz): CBM library, Project Maintainer
* [Oliver Schmidt](https://github.com/oliverschmidt): Apple II library Maintainer

### External contributors

* [acqn](https://github.com/acqn): various compiler fixes
* [jedeoric](https://github.com/jedeoric): Telestrat target
* [jmr](https://github.com/jmr): compiler fixes
* [karrika](https://github.com/karrika): Atari 7800 target
* [Stephan Mühlstrasser](https://github.com/smuehlst): osic1p target
* [Wayne Parham](https://github.com/WayneParham): Sym-1 target
* [Dave Plummer](https://github.com/davepl): KIM-1 target
* [rumbledethumps](https://github.com/rumbledethumps): Picocomputer target

*(The above list is incomplete, if you feel left out - please speak up or add yourself in a PR)*

For a complete list look at the [full team list](https://github.com/orgs/cc65/teams)
or the list of [all contributors](https://github.com/cc65/cc65/graphs/contributors).



[![Snapshot Build](https://github.com/KM198912/CC65/actions/workflows/snapshot-on-push-master.yml/badge.svg)](https://github.com/KM198912/CC65/actions/workflows/snapshot-on-push-master.yml)
