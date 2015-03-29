qtpass
======

QtPass is a gui for [pass](http://www.passwordstore.org/)

Current state
-------------
Read only access to password-store content.

* Using pass or directly with git and gpg2
* Configurable
* Cross platform (\*nix only at this point)

TODO
----
1. ~~non-blocking actions~~
2. ~~multi-lingual~~
3. ~~filtering and autocomplete~~
5. gpg-id management (per-folder)

Instalation
-----------
On most systems all you need is:
`qmake && make && make install`

On MacOsX:
`qmake && make && macdeployqt QtPass.app -dmg `

Further reading
---------------
[Documentation](http://ijhack.github.io/qtpass/)

[Source code](https://github.com/IJHack/qtpass)
