# Sailfish branch

This is a fork from https://github.com/Framstag/libosmscout that closely follows the upstream. The only changes introduced in this branch are related to Sailfish releases. In particular, versions are released and, through the versions, its possible to recompile packages with the older versions. In addition, when changes are needed to make project compile on Sailfish, they are made here.

Current build status:
* Linux, OS X: [![Build Status](https://travis-ci.org/rinigus/libosmscout.svg?branch=master)](https://travis-ci.org/rinigus/libosmscout)
* Windows: [![Build status](https://ci.appveyor.com/api/projects/status/7mg7ad2qyyqgum54?svg=true)](https://ci.appveyor.com/project/rinigus/libosmscout)


Below, is the original README from upstream.

# About

Libosmscout is a C++ library for offline map rendering, routing and location lookup
based on OpenStreetMap data.

Supported platforms:
* 32bit or 64 bit platforms in general are supported.
* Requires a compiler that supports C++11.
* Linux using recent versions of gcc or clang.
* Mac OS X and iOS using XCode/clang.
* Windows using MinGW-based gcc compiler or Visual Studio 2015.
* Android did work a while ago but is currently untested. Should work, if the
 compiler is C++11 aware.

# License

The libraries itself are under LGPL. For details see the [LICENSE](/LICENSE) file.

# Homepage

The official homepage is at: http://libosmscout.sourceforge.net/.

# Support

Please subscribe to the [mailing list](https://sourceforge.net/p/libosmscout/mailman/libosmscout-development/)
and ask your questions. English is the preferred language but other languages might be supported,
too.

# Installation

You can find detailed instruction how to get libraries and applications
build and working and other introductory documentation on the
[homepage](http://libosmscout.sourceforge.net/documentation/).

The documentation in the [OpenStreepMap Wiki](http://wiki.openstreetmap.org/wiki/Libosmscout)
is currently still correct but is not activily maintained by the
libosmscout team.

# Features

You can find a list of features [here](http://libosmscout.sourceforge.net/features/).
Note that the features pages are currently not up to date. We are unsure how to
best represent all the features of libosmscout.

# Documentation

You can find some documentation and tutorials on the [homepage](http://libosmscout.sourceforge.net)
and some other documentation in the [git repository](/Documentation/).

There are a number of demo applications that show how to make use of the various
features of the library.

We plan to move all documentation for the repository to the homepage.

# Automatic builds

Automatic builds for Linux and Mac OS X can be found at
[Travis](https://travis-ci.org/Framstag/libosmscout). The Linux builds are currently based on
Ubuntu 14.04. For both operating systems clang and gcc is used as compiler.

You can find automatic builds for Windows at
[Appveyor](https://ci.appveyor.com/project/Framstag/libosmscout). There are builds
for using MinGW (autoconf, cmake) and VisualStudio (cmake).
