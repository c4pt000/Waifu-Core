*The release notes draft is a temporary file that can be added to by anyone. See
[/doc/developer-notes.md#release-notes](/doc/developer-notes.md#release-notes)
for the process.*

*version* Release Notes Draft
===============================

Waifu Core version *version* is now available from:

  <https://waifucore.org/bin/waifu-core-*version*/>

This release includes new features, various bug fixes and performance
improvements, as well as updated translations.

Please report bugs using the issue tracker at GitHub:

  <https://github.com/waifu/waifu/issues>

To receive security and update notifications, please subscribe to:

  <https://waifucore.org/en/list/announcements/join/>

How to Upgrade
==============

If you are running an older version, shut it down. Wait until it has completely
shut down (which might take a few minutes in some cases), then run the
installer (on Windows) or just copy over `/Applications/Waifu-Qt` (on macOS)
or `waifud`/`waifu-qt` (on Linux).

Upgrading directly from a version of Waifu Core that has reached its EOL is
possible, but it might take some time if the data directory needs to be migrated. Old
wallet versions of Waifu Core are generally supported.

Compatibility
==============

Waifu Core is supported and extensively tested on operating systems
using the Linux kernel, macOS 10.15+, and Windows 7 and newer.  Waifu
Core should also work on most other Unix-like systems but is not as
frequently tested on them.  It is not recommended to use Waifu Core on
unsupported systems.

Notable changes
===============

P2P and network changes
-----------------------

Updated RPCs
------------


Changes to wallet related RPCs can be found in the Wallet section below.

New RPCs
--------

Build System
------------

Updated settings
----------------


Changes to GUI or wallet related settings can be found in the GUI or Wallet section below.

New settings
------------

Tools and Utilities
-------------------

Wallet
------

GUI changes
-----------

Low-level changes
=================

RPC
---

Tests
-----

*version* change log
====================

Credits
=======

Thanks to everyone who directly contributed to this release:


As well as to everyone that helped with translations on
[Transifex](https://www.transifex.com/waifu/waifu/).
