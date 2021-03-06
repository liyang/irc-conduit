[irc-conduit][] [![Build Status][build-status]][build-log]
============

Streaming IRC message library using conduits.

 - Provides [conduits][conduit] for translating bytestrings into
   "events", and "messages" into bytestrings.

 - Provides a sum type for all IRC messages you're likely to want to
   deal with in a client.

 - Provides two helper functions for connecting to IRC servers
   directly.

 - Manages flood protection when connecting to a server directly.

The documentation of the latest developmental version is
[available online][docs].

Note
----

This used to be a part of [yukibot][], so if you want the history from
before this was split out into its own library, check there.

Contributing
------------

Bug reports, pull requests, and comments are very welcome!

Feel free to contact me on GitHub, through IRC (#haskell on freenode),
or email (mike@barrucadu.co.uk).

[irc-conduit]:  http://hackage.haskell.org/package/irc-conduit
[build-status]: https://travis-ci.org/barrucadu/irc-conduit.svg?branch=master
[build-log]:    https://travis-ci.org/barrucadu/irc-conduit
[docs]:         https://docs.barrucadu.co.uk/irc-conduit
[conduit]:      https://hackage.haskell.org/package/conduit
[yukibot]:      https://github.com/barrucadu/yukibot
