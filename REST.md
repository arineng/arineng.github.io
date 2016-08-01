---
layout: page
title: REST @ ARIN
permalink: /rest/
---

ARIN operates several RESTful web services:

* **RDAP** is a standardized, Whois replacement protocol using JSON over HTTP. All 5 RIRs operate RDAP services. More information on RDAP may be found [here](/rdap/).
* **Whois-RWS** is a proprietary protocol specific to ARIN and predates RDAP. The specification for Whois-RWS can be found [here](https://www.arin.net/resources/whoisrws/index.html).
* **Reg-RWS** is a proprietary protocol for registering IP address assignments with ARIN by ARIN customers. The specification for Reg-RWS can be found [here](https://www.arin.net/resources/restful-interfaces.html).

A list of ARIN authored software for RDAP can be found on the [RDAP page](/rdap/).

In addition, ARIN has authored a set of command-line Ruby clients which utilize both Reg-RWS and Whois-RWS. These scripts are known collectively as **ARINCli**. More information can be found on these scripts on the [ARINCli project page](https://github.com/arineng/arincli), and information on each script may be found [here](/arincli_html/arincli.7.html).

**ARINWhois.NET** is a .NET client library for Whois-RWs written by Max Hortsmann. More information can be found on [it's GitHub project page](https://github.com/MaxHorstmann/ArinWhois.NET).