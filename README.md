New tabs perl plugin for rxvt-unicode
=========================================

Diff with original 'tabbed' plugin:
* better tab looking
* better tab controlling
* tab renaming
* default tab name is user@host.

Installation
--------------------

```bash
$ make install
```

The command above will copy the tabbed_new inside ``~/.urxvt/ext/`` folder

Run
--------------------

```bash
$ urxvt -pe tabbed_new
```

or add ``tabbed_new`` to ``URxvt.perl-ext-common`` param in ``~/.Xresources`` file
and execute ``xrdb .Xresources``.

Screen
----------------------

![Alt text](./screen/1.png?raw=true "Simple Screen")
