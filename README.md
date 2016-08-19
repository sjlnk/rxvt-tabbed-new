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

Configure
--------------------

add this params to ``~/.Xresources`` file (tabs colors):

```
URxvt.tabbed_new.tabren-bg: 3
URxvt.tabbed_new.tabdiv-fg: 8
URxvt.tabbed_new.tabbar-fg: 8
URxvt.tabbed_new.tabbar-bg: 0
URxvt.tabbed_new.tabsel-fg: 1
URxvt.tabbed_new.tabsel-bg: 8
URxvt.tabbed_new.tab-fg:    0
URxvt.tabbed_new.tab-bg:    8
```

Usage
--------------------
```
Shift+Down          - create new tab
Mod4+N              - rename corrent tab (keys for control renaming:
                      Esc, Enter, Left, Right, Home, End, Backspace, Delete)
Shift+Left          - move to previous tab
Shift+Right         - move to next tab
Shift+NumPadLeft    - move current tab to left
Shift+NumPaRight    - move current tab to right
```


