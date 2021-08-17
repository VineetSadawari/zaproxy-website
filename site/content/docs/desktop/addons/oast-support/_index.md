---
# This page was generated from the add-on.
title: Out-of-band Application Security Testing Support
type: userguide
weight: 1
cascade:
  addon:
    id: oast
    version: 0.2.0
---

# Out-of-band Application Security Testing Support

The OAST Support add-on allows you to detect and exploit out-of-band vulnerabilities in web applications.

## Services

It currently supports the following services:

* [BOAST](/docs/desktop/addons/oast-support/services/boast/)
* [Callbacks](/docs/desktop/addons/oast-support/services/callbacks/)

## Scripts

If the *Script Console* and the *GraalVM JavaScript* add-ons are installed, a new script template called "OAST Register Request Handler.js" is added to ZAP. Using this template, you can create a script that performs an action whenever an out-of-bound request is discovered. This action could be anything like sending yourself an email or executing another script in ZAP.

## See also

|   |                                                              |   |
|---|--------------------------------------------------------------|---|
|   | [OAST Callbacks Tab](/docs/desktop/addons/oast-support/tab/) |   |