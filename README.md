us_alive - an international keyboard layout without dead keys
=============================================================

This layout extends the basic US English layout with a few additional
letters for usage in (european) international texts.

US English was used as the base because of convenient access to
punctuation and stuff for programming. Dead keys are avoided, to keep
compatibility to the base layout.

At the moment, only German and French language is supported,
i.e., the letters

    ä Ä ö Ö ü Ü ß
    à À â Â æ Æ ç Ç é É è È ê Ê ë Ë î Î ï Ï ô Ô œ Œ ù Ù û Û ÿ Ÿ

are made available.

Additionally, the currencies

    ¢ £ € ¥ ฿

as well as mathematical and scientific symbols

    ° ≠ ≈ ≤ ≥ ∪ ∩

are set up.


The layout can be activated from this directory (`HERE=$(pwd)`) with

    $ setxkbmap -I${HERE} us_alive -print | xkbcomp -I${HERE} - $DISPLAY

which can be automated by putting this line into `~/.xinitrc`.
