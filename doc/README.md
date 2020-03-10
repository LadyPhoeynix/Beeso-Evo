Beeso Core
==============

Setup
---------------------
[Beeso Core](http://beeso.org/) is the official Beeso client and it builds the backbone of the network. However, it downloads and stores the entire history of Beeso transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Beeso Core, visit [beeso.org](https://beeso.org/download/).

Running
---------------------
The following are some helpful notes on how to run Beeso Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/beeso-qt` (GUI) or
- `bin/beesod` (headless)

### Windows

Unpack the files into a directory, and then run beeso-qt.exe.

### macOS

Drag Beeso-Qt to your applications folder, and then run Beeso-Qt.

### Need Help?

* See the documentation at the [Beeso Site](https://beeso.org) for help and more information.
* Ask for help on [#beeso](http://webchat.freenode.net?channels=beeso) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=beeso).
* Ask for help on the [Beeso forums](https://forum.beeso.info/index.php), in the [Technical Support board](https://forum.beeso.info/viewforum.php?f=7).

Building
---------------------
The following are developer notes on how to build Bitcoin Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide (External Link)](https://github.com/bitcoin-core/docs/blob/master/gitian-building.md)

Development
---------------------
The Beeso repo's [root README](https://github.com/beeso/namecore/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://doxygen.bitcoincore.org/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [Beeso forums](https://forum.beeso.info/index.php), in the [Development & Technical Discussion board](https://forum.beeso.info/viewforum.php?f=8).
* Discuss on [#beeso-dev](http://webchat.freenode.net/?channels=beeso-dev) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=beeso-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
