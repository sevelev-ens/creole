[![PyPI version](https://badge.fury.io/py/creole.svg)](https://badge.fury.io/py/creole)

# creole

Creole wiki markup parser in python.

This is a backup repository of the (legacy) package `creole` available at [pypi](https://pypi.org/project/creole/).

See http://wikicreole.org/ for latest specs.

Notes:

* No markup allowed in headings.
Creole 1.0 does not require us to support this.
* No markup allowed in table headings.
Creole 1.0 does not require us to support this.
* No (non-bracketed) generic url recognition: this is "mission impossible"
except if you want to risk lots of false positives. Only known protocols
are recognized.
* We do not allow ":" before "//" italic markup to avoid urls with
unrecognized schemes (like wtf://server/path) triggering italic rendering
for the rest of the paragraph.


@copyright: 2007 MoinMoin:RadomirDopieralski (creole 0.5 implementation),
2007 MoinMoin:ThomasWaldmann (updates)
@license: GNU GPL, see COPYING for details.
@license: BSD, see COPYING for details.
