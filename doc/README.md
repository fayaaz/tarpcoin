TarpCoin Core
=============

Setup
---------------------
TarpCoin Core is the original TarpCoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of TarpCoin transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download TarpCoin Core, visit [TarpCoin.org](https://TarpCoin.org/).

Running
---------------------
The following are some helpful notes on how to run TarpCoin Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/TarpCoin-qt` (GUI) or
- `bin/TarpCoind` (headless)

### Windows

Unpack the files into a directory, and then run TarpCoin-qt.exe.

### macOS

Drag TarpCoin Core to your applications folder, and then run TarpCoin Core.

### Need Help?

* See the documentation at the [TarpCoin Wiki](https://TarpCoin.info/)
for help and more information.
* Ask for help on [#TarpCoin](http://webchat.freenode.net?channels=TarpCoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=TarpCoin).
* Ask for help on the [TarpCoinTalk](https://TarpCointalk.io/) forums, in the [Technical Support section](https://TarpCointalk.io/c/technical-support).

Building
---------------------
The following are developer notes on how to build TarpCoin Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

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
The TarpCoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [TarpCoinTalk](https://TarpCointalk.io/) forums.
* Discuss general TarpCoin development on #TarpCoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=TarpCoin-dev.

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
