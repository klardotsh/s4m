s⁴m: sanely structured system and service management
====================================================
s⁴m is a set of definitions and standard implementations of protocols and
daemons to manage modern POSIX systems and the services they run.
Philosophically speaking, s⁴m provides a clean definition for describing runtime
targets, events, and commands, and an implementation of how to actually act upon
those. A core goal of s⁴m is that most or all components can be replaced by
alternative implementations that speak the same protocols (in software
development, we call this [duck
typing](https://en.wikipedia.org/wiki/Duck_typing)).

> To answer the inevitable "is it s⁴m or s4m?" question: I don't really care,
> and outside of official documentation, will myself use both. s⁴m is a
> stylization; I fully expect packagers will use s4m because *of course they
> will*. All I ask is that in either the name remains lowercase, mostly because
> I'm not a huge fan of my eyes bleeding.

Compatibility
-------------
On a system level: s⁴m currently only promises support for Linux kernels >= 4.19
(the LTS kernel as of 20th September 2019). Eventually, it'd be great to try to
support one or more BSDs as well.

Inspiration
-----------
- [systemd](https://freedesktop.org/wiki/Software/systemd/)
- [runit](http://smarden.org/runit/)
- [OpenRC](https://wiki.gentoo.org/wiki/Project:OpenRC)
- [sysvinit, especially the flavor Arch Linux used](https://wiki.archlinux.org/index.php/SysVinit)

Authors and Contributors
------------------------
In order of first contribution date:

> Feel free to add your name to the end of this list when you submit patches!

- [klardotsh (Josh Klar)](mailto:josh+s4m@klar.sh) - on [sourcehut](https://git.sr.ht/~klardotsh) and [GitHub](https://github.com/klardotsh)

Support / Contributing
----------------------
### Support
A Matrix room will exist... eventually.

### Bugs and other issues
File them [on the sourcehut tracker](https://todo.sr.ht/~klardotsh/s4m), or you
can email the [official mailing list](https://lists.sr.ht/~klardotsh/s4m).

### Contributing
s⁴m is hosted on [sourcehut](https://git.sr.ht/~klardotsh/s4m), with an official
read-only mirror on [GitHub](https://github.com/klardotsh/s4m). Issues and
patches are accepted only on sourcehut - _GitHub pull requests will be
automatically closed_. Use the [Git email workflow](https://git-send-email.io)
against the [official mailing list](https://lists.sr.ht/~klardotsh/s4m).

Legal
-----
s⁴m's code is released under the [GNU General Public License, version
3](https://tldrlegal.com/license/gnu-general-public-license-v3-(gpl-3)). All
documentation and other copyrightable non-code assets are released under the
[Creative Commons Attribution-ShareAlike 4.0 International
License](https://tldrlegal.com/license/creative-commons-attribution-sharealike-4.0-international-(cc-by-sa-4.0)).

