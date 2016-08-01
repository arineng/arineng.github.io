---
layout: page
title: The Registry Data Access Protocol
permalink: /rdap/
---

The Registry Data Access Protocol (RDAP) is a successor protocol to Whois, ratified by the Internet Engineering Task Force (IETF) in March, 2015. At present, all 5 Regional Internet Registries (RIRs) operate RDAP services, and ICANN is finalizing plans for operation of RDAP services by all domain registries. More information on RDAP can be found [here](https://www.arin.net/resources/rdap.html).

ARIN has played a major role in the standardization of RDAP, and as a consequence developed some open source software for RDAP:

* [**NicInfo**](https://github.com/arineng/nicinfo) is a command line RDAP client.
* The [**RDAP Bootstrap Server**](https://github.com/arineng/rdap_bootstrap_server) is a server that issues HTTP redirects based on the IANA RDAP bootstrap files. This server is useful for simple RDAP clients and scripts that do not wish to incorporate RDAP bootstrap processes.
* The [**RDAP WebSPA**](https://github.com/arineng/rdap_webspa) is a prototype web-based RDAP client written in Javascript.

