Icemon
======

Introduction
------------

Icemon is an Icecream GUI monitor.

![Screenshot: Star View](https://github.com/icecc/icemon/wiki/screenshots/icemon-starview.png)

[![Build Status](https://travis-ci.org/icecc/icemon.svg?branch=master)](https://travis-ci.org/icecc/icemon)

Installation
------------

To compile icemon, install, the icecc development package, e.g. for Debian/Ubuntu:

    $ apt-get install libicecc-dev

Finally, make sure you have g++, Qt and cmake installed

    $ apt-get install build-essential qtbase5-dev cmake

Finally, compile and install the application:

    $ mkdir build
    $ cd build
    $ cmake -DCMAKE_INSTALL_PREFIX=/usr ..
    $ make
    $ make install

Run:

    $ icemon

Bug tracker
-----------

Create a github issue on https://github.com/icecc/icemon

Repository
----------

The git repository lives at https://github.com/icecc/icemon

Contact
-------

- Current maintainer: Kevin Funk \<kfunk@kde.org\>
