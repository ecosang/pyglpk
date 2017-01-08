pyglpk
======
[![Build Status](https://travis-ci.org/bradfordboyle/pyglpk.svg?branch=v0.5.0-dev)](https://travis-ci.org/bradfordboyle/pyglpk)
[![Coverage Status](https://coveralls.io/repos/github/bradfordboyle/pyglpk/badge.svg?branch=v0.5.0-dev)](https://coveralls.io/github/bradfordboyle/pyglpk?branch=v0.5.0-dev)

Updated fork of T. Finley's PyGLPK module

Overview
--------

PyGLPK is a [Python][0] module which encapsulates the functionality of the [GNU
Linear Programming Kit][1] (GLPK). The GLPK allows one to specify linear
programs (LPs) and mixed integer programs (MIPs), and to solve them with either
simplex, interior-point, or branch-and-bound algorithms. The goal of PyGLPK is
to give one access to all documented functionality of GLPK.

This program is free software; you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation; either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.

Availability
------------

To get the lastest version, see: [http://tfinley.net/software/pyglpk/][2].

Documentation
-------------

The HTML documentation included with the release in the directory [html](html)
contains information on building, testing, installation and documentation of all
features of the module.

Building and Installing
-----------------------

Building this module requires that the user have installed the [GLPK][1] 4.18 or
later and [GMP][3] libraries. The module builds and appears to work on my test
files in Python 2.4, and 2.5, with GLPK 4.18 through 4.31. Earlier versions of
Python and GLPK will not work.

Ideally, the following will work:
- `make`
- `make test`
- `make install`, or perhaps `sudo make install`

See the HTML documentation for troubleshooting information.

Bugs and Commentary
-------------------

Please send information on issues of usage to Thomas Finley at
[tfinley@gmail.com</a></code>][4].

* * *
Thomas Finley, 2007, 2008

[0]: http://www.python.org/
[1]: http://www.gnu.org/software/glpk/
[2]: http://tfinley.net/software/pyglpk/
[3]: http://gmplib.org/
[4]: mailto:tfinley@gmail.com