## BBC, RAI & RTVE Radio Player

radio.py is a simple Internet radio script written in Python and Qt (using the [PyQt5][0] bindings). It was tested with python-3.8.2 and PyQt5.14.2 .

VLC is used by default but you can specify another player along with some arguments for it, like this:

`./radio.py -p mplayer -- -cache 60 -cache-min 20 -playlist`

Since you'd be doing this from a terminal emulator, remember to quit mplayer before closing radio.py window (radio.py will leave the player running upon exit, by design).

[0]: https://www.riverbankcomputing.com/software/pyqt/intro

