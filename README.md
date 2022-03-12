![alt text](https://miro.medium.com/max/1400/1*h6BUy3nfno18axUmv41DyQ.jpeg)

Lood Core integration/staging tree
=====================================

[![Build Status](https://travis-ci.org/lood-project/lood.svg?branch=master)](https://travis-ci.org/lood-project/lood)


Lood Adult Gaming
----------------

We are a small network of adult performers and studios with a love for technology and decentralized finance.

The Lood project is dedicated to creating fun and unique spaces for fans to engage with their favorite adult talent. While collectively solving the issues we face as an industry.

For more information about our project and history, check out this announcement post(https://dooplejoy.medium.com/creating-the-first-adult-blockchain-game-c30a549d91ad).

Adult Cryptocurrency
----------------

The LOOD cryptocurrency was built on the idea that simplicity is the key to adoption and that people in this market prefer software that just works.

We needed a cryptocurrency to work with existing technologies in a way that was seamless.  
Too many blockchains emphasize functions that only serve to enrich the developers (and to be fair, investors) 
not make the software itself easier to use. We believe that it is for this reason that many projects languish. 
Worse, the industries often loosely targeted simply aren't willing to adapt to such learning curves as the room 
for error is slim when it comes to financial technologies. This project aims to simplify the blockchain.

LOOD ultimately uses peer-to-peer technology to operate independently of its the native blockchain game Triple X Tycoon.
Enabling users to independently mine, verify and initiate global transactions outside of the game.

For more information, as well as an immediately functional wallet, visit Lood.Cash(https://lood.cash/triplextycoon).

Technical Overview
-------

![alt text](https://ip.bitcointalk.org/?u=https%3A%2F%2Flood.cash%2F1%2Flood_cloud_txt.png&t=635&c=M8iypAeqqhkekA)


LOOD can be described as Litecoin stripped down to its core mechanics.  This means that even the standard QT wallet will be removed in favor of a vaguely retro but sexier user interface (SUI).  At which point additional features may be added using the C programming language. In the meantime, a cloud wallet exists and the coin works as a method of exchange within an existing blockchain game (Triple X Tycoon). Which has been in first-party development for over 7 years and operates entirely on it own game engine and the Lood cloud.

![alt text](https://ip.bitcointalk.org/?u=https%3A%2F%2Fmiro.medium.com%2Fmax%2F1280%2F1%2A0pXBhutWbfHTgUIkELcq-A.png&t=635&c=2YY6DvNdYoSjGQ)

License
-------

LOOD is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

The Lood Engine (which powers the cloud wallet) is proprietary middleware, parts of which will be rolled out into the open-source domain over time.

Development Process
-------------------

The `master` branch is regularly built and tested as it must always remain compatible
with the cloud wallet. [Tags](https://github.com/lood-project/lood/tags) are created
regularly to indicate new official, stable release versions of LOOD.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

The LoodSpace forum should be used to discuss complicated or controversial changes before working
on a patch set.

Testing
-------

This is a security-critical project where any mistake might cost people lots of money.  As such we'd like to 
minimize the amount of minor or aesthetic fixes and only focus on core mechanics. 

### Automated Testing

LOOD testing occurs in-house using proprietary tools. But developers are encouraged 
to write [unit tests](src/test/README.md) for new code, and to submit new unit tests for old code. 
Unit tests can be compiled and run (assuming they weren't disabled in configure) with: `make check`. 
Further details on running and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and OS X, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

We acknowledge that changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.  

Translations
------------

As a temporary solution, translation requests can be submitted via the [LOOD Telegram](http://t.me/loodcrypto).
