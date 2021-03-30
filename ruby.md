## Intent

This challenge intends to get a sense of how do you solve certain architectural and design
 problems, and how well do you document and test your work.

## The Challenge

Implement a Memcached server (TCP/IP socket) that complies with the specified protocol.

About Memcached:

> Free & open-source, high-performance, distributed memory object caching system, generic in nature,
> but intended for use in speeding up dynamic web applications by alleviating database load.

The server must listen for new connections on a given TCP port. The implementation must accept
connections and commands from any Memcached client and respond appropriately.

### Requirements

A subset of Memcached commands, with all of their allowed options, must be supported.

Retrieval commands:
* get
* gets

Storage commands:
* set
* add
* replace
* append
* prepend
* cas

Find the details about each command in the protocol's documentation (see the
[References](#references) section)

Each command should have a set of unit tests covering each case.

The project should have a `README.md` describing how to run the server, run a demo client, and issue
sample commands, and how to run the tests.

### Extras

* Purge expired keys
* Manage multiple clients
* Design and include architectural diagrams

## Deliverables

The codebase must be published on GitHub.

Gems can't be used, the only exception to this is `rspec`.

After completing the challenge, send an email to coding-challenge@moove-it.com including the
GitHub’s repository url. Tag the version you want to deliver as `1.0.0`.

### References

Full list of commands: http://lzone.de/cheat-sheet/memcached

The protocol specification: https://github.com/memcached/memcached/blob/master/doc/protocol.txt

