---
layout: page
title: The Referral WHOIS page
permalink: /rwhois/
---

This is a release of the Referral Whois (RWhois) server developed
by the Network Solutions, Incorporated, Directory Services group.  The
documentation for RWhois will continue to be updated to reflect
enhancements to RWhois.  Additional documentation will be available
throughout the evolution of RWhois and as RWhois is deployed on a
larger scale.

This server is a reference implementation of the server side of the
RWhois protocol, first described in RFC 1714.  This server attempts to
implement concepts and practices in accordance with version 1.5 of the
protocol, described in doc/rfc2167.txt. This server should work
on most versions of UNIX.

The primary difference between this server and previous versions is
the treatment of authority areas.  The server now supports multiple
authority areas and is more strict in its management of those
authority areas.  The inclusion of multiple authority areas has forced
a marked change upon the location and usage of the rwhoisd
configuration files.  Please see the operations guide
(doc/operations-guide.txt) for further information.  See the
doc/UPGRADE file for notes on upgrading from the 1.0 server.

RWHOIS can be downloaded from [here](https://github.com/arineng/rwhoisd)
or from the following links:

* [Git](https://github.com/arineng/rwhoisd.git)
* [Zip](https://github.com/arineng/rwhoisd/archive/master.zip)
