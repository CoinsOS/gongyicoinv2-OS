Introduction
===========================

The GongYiCoin Project  is a decentralized peer-to-peer platform, created under an open source license, featuring a built-in cryptocurrency, end-to-end encrypted messaging and decentralized marketplace. The decentralized network aims to provide anonymity and privacy for everyone through a simple user-friendly interface by taking care of all the advanced cryptography in the background. 

"They who can give up essential liberty to obtain a little temporary safety deserve neither liberty nor safety." 

Releases
===========================

Supported Operating Systems:
* Linux (64 bit)
* ~~Linux (32 bit)~~
* Windows (32 bit)
* Windows (64 bit)
* OSX 


Linux releases will not work out of the box on the Raspberry Pi, you'll have to compile from source.

Development process
===========================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of GongYiCoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'.

Building GongYiCoin
===========================

See [doc/readme-qt.rst] for instructions on building **GongYiCoin QT** | *the intended-for-end-users, nice-graphical-interface, reference implementation of GongYiCoin.*

See [doc/build-msw.txt] for instructions on building **gongyicoind (Windows)** | *the intended-for-services, no-graphical-interface, reference implementation of GongYiCoin.*

See [doc/build-osx.txt] for instructions on building **gongyicoind (Mac)**

See [doc/build-unix.txt] for instructions on building **gongyicoind (UNIX)**
