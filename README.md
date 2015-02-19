# Running Linux on TSAR

This repository contains various HOWTOs about running GNU/Linux on the
[TSAR](https://www-soc.lip6.fr/trac/tsar) processor architecture, from the Linux
kernel alone to a "full-fledge" [Busybox](http://www.busybox.net/)-based system.

## HOWTOs

1. [Howto](10-linux-simple.mdwn): compile the [Linux
   kernel](http://en.wikipedia.org/wiki/Linux_kernel) for the TSAR architecture
   and run it
2. [Howto](11-hello-world.mdwn): run a _hello world_ assembly application
3. [Howto](12-klibc.mdwn): create a simple system based on
   [klibc](http://en.wikipedia.org/wiki/Klibc)
4. [Howto](20-crosstool-ng.mdwn): generate an
   [uClibC](http://www.uclibc.org/)-based cross-toolchain for TSAR with
   [crosstool-ng](http://crosstool-ng.org/)
5. [Howto](30-buildroot): build a complex system with
   [Buildroot](http://buildroot.uclibc.org/)

## Credits

Copyright (C) 2013-2015 Pierre and Marie Curie University<br />
Joël Porquet `<joel.porquet@lip6.fr>`
