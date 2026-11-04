---
title: A local catch-all DNS domain
---

#### local names with zero setup

A zero setup local catch-all. No dnsmasq setup, no Acrylic DNS setup.

Just use `anything.localdev.it`, IPv4 and IPv6, it will resolve to `127.0.0.1` or `::1`.

It is the domain the localdev.it stack uses for its project names: with
`SUFFIX=localdev.it`, `projecta.localdev.it` and `clientportal.localdev.it`
answer on the machine that runs the stack, with no `/etc/hosts` line.

You are welcome.

